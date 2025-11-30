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
| Time          |2025-11-30 00:50:28 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47441|0.47768|0.00060|0.13%|0.47556|0.00%|0.47546|0.00%|0.880|0.999|180944468|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56795d2810)|0.46419|0.47305|0.00091|0.19%|0.47019|-1.13%|0.47012|-1.12%|-2.396|0.000|176404873|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/71d11bdb16)|0.46743|0.47478|0.00090|0.19%|0.47026|-1.12%|0.47008|-1.13%|1.437|0.000|176401947|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/71d11bdb16)|0.45035|0.45511|0.00062|0.14%|0.45125|-5.11%|0.45117|-5.11%|3.633|0.000|147887754|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74143|0.74557|0.00087|0.12%|0.74320|0.00%|0.74309|0.00%|0.678|0.999|291625346|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56795d2810)|0.74283|0.74852|0.00109|0.15%|0.74437|0.16%|0.74409|0.13%|1.447|0.000|290398893|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/71d11bdb16)|0.74173|0.75336|0.00180|0.24%|0.74396|0.10%|0.74370|0.08%|3.776|0.000|290399520|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/71d11bdb16)|0.71537|0.71903|0.00076|0.11%|0.71671|-3.56%|0.71669|-3.55%|0.848|0.000|270758464|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57951|0.59204|0.00131|0.22%|0.58133|0.00%|0.58109|0.00%|5.757|0.999|1123344419|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56795d2810)|0.58034|0.59145|0.00110|0.19%|0.58175|0.07%|0.58163|0.09%|6.938|0.000|1119631170|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/71d11bdb16)|0.57851|0.58926|0.00122|0.21%|0.57984|-0.26%|0.57963|-0.25%|4.913|0.000|1119631494|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/71d11bdb16)|0.51527|0.51797|0.00050|0.10%|0.51646|-11.16%|0.51640|-11.13%|0.412|0.000|865681849|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42984|0.44033|0.00233|0.54%|0.43421|0.00%|0.43400|0.00%|0.451|0.999|2020638225|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56795d2810)|0.42399|0.44957|0.00369|0.86%|0.42790|-1.45%|0.42707|-1.60%|2.956|0.000|2020586645|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/71d11bdb16)|0.42384|0.43816|0.00251|0.59%|0.42737|-1.57%|0.42682|-1.65%|2.153|0.000|2020586641|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/71d11bdb16)|0.14684|0.15210|0.00110|0.74%|0.14882|-65.73%|0.14866|-65.75%|0.548|0.000|536605636|27.75 MB|
