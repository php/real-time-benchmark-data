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
| Time          |2026-07-03 07:27:49 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28631619981 ([Artifacts](https://github.com/php/php-src/actions/runs/28631619981/artifacts/8061420077))|
| Changeset  |https://github.com/php/php-src/compare/ae00731fd2..092de40341|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39956|0.40078|0.00022|0.06%|0.39991|0.00%|0.39987|0.00%|1.354|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ae00731fd2)|0.38962|0.39135|0.00045|0.11%|0.39016|-2.44%|0.39004|-2.46%|1.562|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/092de40341)|0.39141|0.39357|0.00042|0.11%|0.39209|-1.95%|0.39202|-1.96%|1.646|8.614|0.000|25.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/092de40341)|0.36693|0.36875|0.00040|0.11%|0.36775|-8.04%|0.36770|-8.04%|0.766|8.614|0.000|25.74 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67898|0.68157|0.00064|0.09%|0.67973|0.00%|0.67956|0.00%|1.044|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ae00731fd2)|0.66998|0.67470|0.00086|0.13%|0.67084|-1.31%|0.67054|-1.33%|2.540|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/092de40341)|0.66891|0.67062|0.00044|0.07%|0.66944|-1.51%|0.66931|-1.51%|1.329|8.614|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/092de40341)|0.63866|0.64024|0.00033|0.05%|0.63914|-5.97%|0.63911|-5.95%|1.330|8.614|0.000|26.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59383|0.59774|0.00096|0.16%|0.59555|0.00%|0.59556|0.00%|0.251|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ae00731fd2)|0.59119|0.59636|0.00127|0.22%|0.59240|-0.53%|0.59200|-0.60%|2.015|7.594|0.000|26.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/092de40341)|0.59115|0.59483|0.00072|0.12%|0.59208|-0.58%|0.59188|-0.62%|2.478|8.428|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/092de40341)|0.52400|0.53522|0.00170|0.32%|0.52500|-11.85%|0.52450|-11.93%|4.807|8.614|0.000|26.29 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44352|0.44725|0.00068|0.15%|0.44472|0.00%|0.44459|0.00%|1.326|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ae00731fd2)|0.44996|0.45232|0.00055|0.12%|0.45111|1.44%|0.45113|1.47%|-0.027|-8.614|0.000|26.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/092de40341)|0.44991|0.45250|0.00058|0.13%|0.45117|1.45%|0.45117|1.48%|0.012|-8.614|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/092de40341)|0.14425|0.14510|0.00017|0.12%|0.14463|-67.48%|0.14465|-67.46%|-0.025|8.614|0.000|26.29 MB|
