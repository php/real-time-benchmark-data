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
| Time          |2026-06-30 01:23:33 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28413825955 ([Artifacts](https://github.com/php/php-src/actions/runs/28413825955/artifacts/7969351877))|
| Changeset  |https://github.com/php/php-src/compare/eaa6325959..ae00731fd2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39650|0.39765|0.00020|0.05%|0.39689|0.00%|0.39687|0.00%|0.966|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eaa6325959)|0.38839|0.39016|0.00044|0.11%|0.38890|-2.01%|0.38876|-2.04%|1.688|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/ae00731fd2)|0.38632|0.38785|0.00032|0.08%|0.38696|-2.50%|0.38691|-2.51%|1.137|8.614|0.000|25.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ae00731fd2)|0.36073|0.36292|0.00051|0.14%|0.36147|-8.92%|0.36133|-8.96%|1.223|8.614|0.000|25.83 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67560|0.67897|0.00075|0.11%|0.67648|0.00%|0.67624|0.00%|1.682|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eaa6325959)|0.66909|0.67155|0.00053|0.08%|0.66982|-0.98%|0.66969|-0.97%|1.317|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/ae00731fd2)|0.66724|0.66926|0.00045|0.07%|0.66788|-1.27%|0.66773|-1.26%|1.678|8.614|0.000|25.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ae00731fd2)|0.63706|0.63866|0.00033|0.05%|0.63766|-5.74%|0.63756|-5.72%|1.026|8.614|0.000|25.79 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59040|0.59471|0.00095|0.16%|0.59224|0.00%|0.59219|0.00%|0.567|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eaa6325959)|0.58778|0.59233|0.00069|0.12%|0.58860|-0.62%|0.58854|-0.62%|3.477|8.414|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/ae00731fd2)|0.58753|0.59110|0.00056|0.10%|0.58811|-0.70%|0.58795|-0.72%|3.487|8.586|0.000|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ae00731fd2)|0.51870|0.52999|0.00166|0.32%|0.51969|-12.25%|0.51938|-12.29%|5.230|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44349|0.44551|0.00049|0.11%|0.44463|0.00%|0.44462|0.00%|-0.188|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eaa6325959)|0.44952|0.45436|0.00077|0.17%|0.45065|1.36%|0.45056|1.33%|2.337|-8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/ae00731fd2)|0.44890|0.45272|0.00074|0.16%|0.45106|1.45%|0.45098|1.43%|-0.297|-8.614|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ae00731fd2)|0.14414|0.14497|0.00020|0.14%|0.14454|-67.49%|0.14456|-67.49%|-0.202|8.614|0.000|26.26 MB|
