### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-09-08 01:07:42 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34175585045 ([Artifacts](https://github.com/php/php-src/actions/runs/34175585045/artifacts/10037668969))|
| Changeset  |https://github.com/php/php-src/compare/810a9e58dc..1364de0472|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39903|0.40003|0.00018|0.04%|0.39941|0.00%|0.39942|0.00%|0.500|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/810a9e58dc)|0.37282|0.37407|0.00022|0.06%|0.37336|-6.52%|0.37333|-6.53%|0.689|8.614|0.000|25.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/1364de0472)|0.37375|0.37665|0.00042|0.11%|0.37421|-6.31%|0.37411|-6.34%|4.184|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68016|0.68418|0.00086|0.13%|0.68183|0.00%|0.68168|0.00%|0.664|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/810a9e58dc)|0.67515|0.67868|0.00056|0.08%|0.67601|-0.85%|0.67594|-0.84%|2.509|8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/1364de0472)|0.67518|0.67746|0.00042|0.06%|0.67584|-0.88%|0.67580|-0.86%|1.127|8.614|0.000|26.20 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59104|0.59441|0.00082|0.14%|0.59239|0.00%|0.59228|0.00%|0.452|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/810a9e58dc)|0.59102|0.59446|0.00067|0.11%|0.59187|-0.09%|0.59182|-0.08%|1.893|3.699|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/1364de0472)|0.59106|0.59615|0.00085|0.14%|0.59205|-0.06%|0.59190|-0.06%|2.904|2.747|0.006|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44341|0.44590|0.00058|0.13%|0.44469|0.00%|0.44471|0.00%|-0.042|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/810a9e58dc)|0.45009|0.45264|0.00055|0.12%|0.45143|1.51%|0.45139|1.50%|0.132|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/1364de0472)|0.45079|0.45281|0.00050|0.11%|0.45200|1.64%|0.45202|1.64%|-0.357|-8.614|0.000|26.24 MB|
