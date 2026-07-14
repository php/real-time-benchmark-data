### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-07-14 00:59:08 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29297359934 ([Artifacts](https://github.com/php/php-src/actions/runs/29297359934/artifacts/8298037913))|
| Changeset  |https://github.com/php/php-src/compare/75cdbcd40b..2c7c630e28|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39519|0.39617|0.00019|0.05%|0.39554|0.00%|0.39552|0.00%|0.801|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75cdbcd40b)|0.38530|0.38813|0.00042|0.11%|0.38581|-2.46%|0.38569|-2.49%|3.755|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c7c630e28)|0.38670|0.38998|0.00059|0.15%|0.38725|-2.10%|0.38714|-2.12%|3.177|8.614|0.000|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c7c630e28)|0.36060|0.36364|0.00059|0.16%|0.36131|-8.66%|0.36111|-8.70%|1.973|8.614|0.000|25.72 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67313|0.67614|0.00065|0.10%|0.67404|0.00%|0.67391|0.00%|1.446|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75cdbcd40b)|0.66660|0.66947|0.00050|0.07%|0.66759|-0.96%|0.66744|-0.96%|1.292|8.614|0.000|25.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c7c630e28)|0.66359|0.66884|0.00082|0.12%|0.66430|-1.44%|0.66412|-1.45%|3.855|8.614|0.000|25.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c7c630e28)|0.63606|0.63799|0.00045|0.07%|0.63698|-5.50%|0.63705|-5.47%|-0.045|8.614|0.000|26.18 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58852|0.59417|0.00126|0.21%|0.59090|0.00%|0.59087|0.00%|0.520|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75cdbcd40b)|0.58567|0.59091|0.00083|0.14%|0.58652|-0.74%|0.58634|-0.77%|3.405|8.441|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c7c630e28)|0.58266|0.58666|0.00087|0.15%|0.58352|-1.25%|0.58318|-1.30%|2.585|8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c7c630e28)|0.51351|0.51866|0.00103|0.20%|0.51428|-12.97%|0.51396|-13.02%|2.776|8.614|0.000|26.27 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44336|0.44605|0.00065|0.15%|0.44456|0.00%|0.44458|0.00%|0.077|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75cdbcd40b)|0.44973|0.45371|0.00065|0.14%|0.45089|1.42%|0.45081|1.40%|1.629|-8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c7c630e28)|0.44961|0.45231|0.00064|0.14%|0.45103|1.45%|0.45104|1.45%|-0.111|-8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c7c630e28)|0.14408|0.14490|0.00019|0.13%|0.14449|-67.50%|0.14451|-67.50%|-0.163|8.614|0.000|26.29 MB|
