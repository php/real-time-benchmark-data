### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2025-12-17 00:50:07 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47405|0.48003|0.00080|0.17%|0.47751|0.00%|0.47752|0.00%|-0.166|0.999|180945861|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7dd5f31dde)|0.47099|0.47781|0.00107|0.23%|0.47237|-1.08%|0.47221|-1.11%|2.865|0.000|176327235|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/aee5fce6ff)|0.46953|0.47506|0.00089|0.19%|0.47102|-1.36%|0.47091|-1.38%|1.672|0.000|176398219|44.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aee5fce6ff)|0.44463|0.45267|0.00087|0.19%|0.45074|-5.61%|0.45081|-5.59%|-3.365|0.000|147877977|53.52 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74540|0.76069|0.00189|0.25%|0.74701|0.00%|0.74671|0.00%|5.767|0.999|291622017|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7dd5f31dde)|0.74509|0.75641|0.00138|0.18%|0.74675|-0.03%|0.74656|-0.02%|3.775|0.082|290423210|40.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/aee5fce6ff)|0.73786|0.75879|0.00221|0.30%|0.74827|0.17%|0.74778|0.14%|0.839|0.000|290419860|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aee5fce6ff)|0.71869|0.72209|0.00071|0.10%|0.72031|-3.57%|0.72030|-3.54%|0.057|0.000|270764336|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57651|0.58410|0.00208|0.36%|0.58030|0.00%|0.58122|0.00%|-0.459|0.999|1123346897|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7dd5f31dde)|0.57920|0.58656|0.00204|0.35%|0.58292|0.45%|0.58394|0.47%|-0.484|0.000|1119519954|44.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/aee5fce6ff)|0.57807|0.58919|0.00216|0.37%|0.58198|0.29%|0.58275|0.26%|-0.131|0.000|1119538617|44.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aee5fce6ff)|0.51371|0.51875|0.00159|0.31%|0.51662|-10.97%|0.51735|-10.99%|-0.573|0.000|865598690|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42521|0.43859|0.00403|0.93%|0.43145|0.00%|0.43208|0.00%|-0.011|0.999|2020638143|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7dd5f31dde)|0.42123|0.43851|0.00319|0.75%|0.42594|-1.28%|0.42530|-1.57%|1.848|0.000|2020586445|27.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/aee5fce6ff)|0.42140|0.47709|0.00589|1.38%|0.42670|-1.10%|0.42575|-1.47%|6.589|0.000|2020586574|27.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aee5fce6ff)|0.13716|0.14964|0.00369|2.57%|0.14390|-66.65%|0.14547|-66.33%|-0.232|0.000|536605492|27.87 MB|
