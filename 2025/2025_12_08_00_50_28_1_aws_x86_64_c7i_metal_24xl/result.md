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
| Time          |2025-12-08 00:50:28 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47491|0.47748|0.00055|0.12%|0.47571|0.00%|0.47560|0.00%|1.098|0.999|180943426|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fb4e573ff)|0.46944|0.47578|0.00081|0.17%|0.47072|-1.05%|0.47058|-1.06%|2.854|0.000|176334005|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f1300011)|0.46956|0.47209|0.00056|0.12%|0.47046|-1.10%|0.47037|-1.10%|0.539|0.000|176406196|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f1300011)|0.44391|0.45226|0.00088|0.19%|0.45078|-5.24%|0.45077|-5.22%|-4.729|0.000|147897170|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74186|0.74524|0.00073|0.10%|0.74324|0.00%|0.74316|0.00%|0.520|0.999|291621072|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fb4e573ff)|0.74119|0.75003|0.00138|0.19%|0.74541|0.29%|0.74517|0.27%|1.108|0.000|290398092|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f1300011)|0.74383|0.75627|0.00209|0.28%|0.74578|0.34%|0.74511|0.26%|2.721|0.000|290398802|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f1300011)|0.71580|0.71899|0.00071|0.10%|0.71705|-3.52%|0.71696|-3.53%|0.600|0.000|270760995|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57608|0.58877|0.00239|0.41%|0.57925|0.00%|0.57816|0.00%|0.908|0.999|1123346515|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fb4e573ff)|0.57575|0.58322|0.00220|0.38%|0.57868|-0.10%|0.57760|-0.10%|0.362|0.009|1119625188|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f1300011)|0.57612|0.59138|0.00240|0.41%|0.57908|-0.03%|0.57815|-0.00%|1.418|0.302|1119633643|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f1300011)|0.51336|0.51880|0.00165|0.32%|0.51557|-10.99%|0.51472|-10.97%|0.298|0.000|865685519|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42344|0.44008|0.00357|0.83%|0.43213|0.00%|0.43277|0.00%|-0.378|0.999|2020638183|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fb4e573ff)|0.42161|0.44265|0.00350|0.82%|0.42725|-1.13%|0.42701|-1.33%|1.641|0.000|2020586618|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f1300011)|0.42119|0.43887|0.00296|0.69%|0.42678|-1.24%|0.42632|-1.49%|1.479|0.000|2020586717|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f1300011)|0.13952|0.15170|0.00367|2.50%|0.14671|-66.05%|0.14827|-65.74%|-0.784|0.000|536605611|27.74 MB|
