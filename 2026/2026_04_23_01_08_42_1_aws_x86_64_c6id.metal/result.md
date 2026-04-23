### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-04-23 01:08:42 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24811042439 ([Artifacts](https://github.com/php/php-src/actions/runs/24811042439/artifacts/6592511466))|
| Changeset  |https://github.com/php/php-src/compare/239a8bed9b..a935460721|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39451|0.39684|0.00073|0.19%|0.39539|0.00%|0.39500|0.00%|0.647|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/239a8bed9b)|0.38733|0.38911|0.00037|0.09%|0.38780|-1.92%|0.38768|-1.85%|1.875|8.614|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/a935460721)|0.38724|0.38885|0.00033|0.09%|0.38770|-1.95%|0.38760|-1.87%|1.310|8.614|0.000|25.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a935460721)|0.35981|0.36128|0.00029|0.08%|0.36044|-8.84%|0.36041|-8.76%|0.398|8.614|0.000|25.42 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66700|0.66929|0.00059|0.09%|0.66778|0.00%|0.66762|0.00%|1.160|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/239a8bed9b)|0.66351|0.67027|0.00208|0.31%|0.66507|-0.41%|0.66418|-0.52%|1.665|5.891|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/a935460721)|0.66336|0.66517|0.00040|0.06%|0.66390|-0.58%|0.66382|-0.57%|1.510|8.614|0.000|25.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a935460721)|0.63241|0.63402|0.00028|0.04%|0.63288|-5.23%|0.63283|-5.21%|1.498|8.614|0.000|25.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58835|0.59293|0.00113|0.19%|0.59031|0.00%|0.59020|0.00%|0.451|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/239a8bed9b)|0.58571|0.58827|0.00050|0.09%|0.58640|-0.66%|0.58630|-0.66%|1.804|8.614|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/a935460721)|0.58403|0.58644|0.00052|0.09%|0.58471|-0.95%|0.58459|-0.95%|1.529|8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a935460721)|0.51504|0.51776|0.00049|0.10%|0.51596|-12.60%|0.51587|-12.59%|1.740|8.614|0.000|25.68 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44125|0.44541|0.00074|0.17%|0.44273|0.00%|0.44272|0.00%|1.061|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/239a8bed9b)|0.44575|0.44743|0.00043|0.10%|0.44657|0.87%|0.44659|0.88%|0.060|-8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/a935460721)|0.44569|0.44761|0.00043|0.10%|0.44670|0.90%|0.44672|0.90%|-0.358|-8.614|0.000|25.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a935460721)|0.14308|0.14393|0.00018|0.13%|0.14349|-67.59%|0.14354|-67.58%|-0.253|8.614|0.000|25.72 MB|
