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
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250818|
| GCC           |14.2.1|
| Time          |2025-09-03 00:49:48 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47185|0.47685|0.00066|0.14%|0.47296|0.00%|0.47289|0.00%|2.560|0.999|181231308|43.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c6b83887e)|0.46672|0.46872|0.00040|0.09%|0.46755|-1.14%|0.46748|-1.14%|0.625|0.000|176637935|44.02 MB|
|[PHP - master](https://github.com/php/php-src/commit/d85662d6cc)|0.46250|0.46823|0.00058|0.12%|0.46694|-1.27%|0.46695|-1.26%|-4.429|0.000|176633344|44.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d85662d6cc)|0.45201|0.45383|0.00037|0.08%|0.45284|-4.25%|0.45280|-4.25%|0.459|0.000|149309067|53.94 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74069|0.74603|0.00091|0.12%|0.74262|0.00%|0.74244|0.00%|0.949|0.999|291550434|39.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c6b83887e)|0.73342|0.74434|0.00209|0.28%|0.73525|-0.99%|0.73464|-1.05%|2.755|0.000|287306741|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/d85662d6cc)|0.72388|0.74376|0.00221|0.30%|0.73432|-1.12%|0.73394|-1.14%|0.886|0.000|287306748|40.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d85662d6cc)|0.70599|0.71484|0.00125|0.18%|0.70756|-4.72%|0.70724|-4.74%|2.821|0.000|267610224|47.55 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57928|0.58406|0.00083|0.14%|0.58082|0.00%|0.58063|0.00%|1.632|0.999|1122999844|43.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c6b83887e)|0.58131|0.58604|0.00090|0.15%|0.58300|0.38%|0.58281|0.38%|1.273|0.000|1119164992|43.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/d85662d6cc)|0.58060|0.59113|0.00126|0.22%|0.58265|0.32%|0.58233|0.29%|3.624|0.000|1119163573|43.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d85662d6cc)|0.51341|0.52088|0.00088|0.17%|0.51841|-10.74%|0.51827|-10.74%|-1.025|0.000|865524628|61.45 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42823|0.44573|0.00201|0.47%|0.43143|0.00%|0.43106|0.00%|3.849|0.999|2020733083|26.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c6b83887e)|0.42302|0.55509|0.01939|4.52%|0.42906|-0.55%|0.42548|-1.30%|5.736|0.000|2020744417|27.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/d85662d6cc)|0.42248|0.54516|0.02793|6.46%|0.43232|0.20%|0.42522|-1.36%|3.753|0.000|2020744494|27.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d85662d6cc)|0.14757|0.15139|0.00097|0.65%|0.14950|-65.35%|0.14942|-65.34%|0.158|0.000|536712494|28.07 MB|
