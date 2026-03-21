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
| Time          |2026-03-21 00:51:57 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23368399900 ([Artifacts](https://github.com/php/php-src/actions/runs/23368399900/artifacts/6036121591))|
| Changeset  |https://github.com/php/php-src/compare/38cbbee4aa..30b2d77cd3|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39443|0.39660|0.00052|0.13%|0.39499|0.00%|0.39485|0.00%|2.366|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/38cbbee4aa)|0.38774|0.38973|0.00044|0.11%|0.38819|-1.72%|0.38811|-1.71%|2.348|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/30b2d77cd3)|0.38750|0.38889|0.00029|0.08%|0.38789|-1.80%|0.38782|-1.78%|1.982|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30b2d77cd3)|0.36025|0.36320|0.00060|0.17%|0.36100|-8.60%|0.36083|-8.62%|1.790|8.614|0.000|25.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66645|0.67103|0.00088|0.13%|0.66722|0.00%|0.66688|0.00%|2.196|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/38cbbee4aa)|0.66185|0.66679|0.00096|0.14%|0.66269|-0.68%|0.66242|-0.67%|3.290|8.469|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/30b2d77cd3)|0.66167|0.66413|0.00048|0.07%|0.66214|-0.76%|0.66198|-0.73%|2.362|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30b2d77cd3)|0.63123|0.64529|0.00195|0.31%|0.63192|-5.29%|0.63156|-5.30%|6.796|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58714|0.59324|0.00119|0.20%|0.58972|0.00%|0.58954|0.00%|0.784|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/38cbbee4aa)|0.58485|0.58886|0.00091|0.15%|0.58586|-0.65%|0.58559|-0.67%|2.219|8.428|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/30b2d77cd3)|0.58498|0.59194|0.00110|0.19%|0.58570|-0.68%|0.58542|-0.70%|4.211|8.262|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30b2d77cd3)|0.51381|0.52430|0.00145|0.28%|0.51469|-12.72%|0.51444|-12.74%|6.183|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44148|0.44404|0.00059|0.13%|0.44276|0.00%|0.44271|0.00%|0.228|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/38cbbee4aa)|0.44440|0.44722|0.00062|0.14%|0.44580|0.69%|0.44583|0.71%|-0.061|-8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/30b2d77cd3)|0.44476|0.44726|0.00044|0.10%|0.44592|0.71%|0.44590|0.72%|0.266|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30b2d77cd3)|0.14345|0.14458|0.00027|0.19%|0.14394|-67.49%|0.14392|-67.49%|0.532|8.614|0.000|25.33 MB|
