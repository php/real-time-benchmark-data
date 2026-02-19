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
| Time          |2026-02-19 00:56:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22164054280 ([Artifacts](https://github.com/php/php-src/actions/runs/22164054280/artifacts/5566010707))|
| Changeset  |https://github.com/php/php-src/compare/76445cabc0..fa2caa0403|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39453|0.39658|0.00041|0.10%|0.39503|0.00%|0.39496|0.00%|2.611|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/76445cabc0)|0.38909|0.39302|0.00084|0.21%|0.38985|-1.31%|0.38958|-1.36%|2.643|8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa2caa0403)|0.38941|0.39247|0.00060|0.15%|0.38993|-1.29%|0.38974|-1.32%|3.052|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa2caa0403)|0.36084|0.36290|0.00042|0.12%|0.36131|-8.54%|0.36115|-8.56%|1.840|8.614|0.000|25.37 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66783|0.67091|0.00059|0.09%|0.66858|0.00%|0.66840|0.00%|1.760|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/76445cabc0)|0.66016|0.66517|0.00070|0.11%|0.66064|-1.19%|0.66052|-1.18%|5.742|8.614|0.000|25.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa2caa0403)|0.66012|0.66273|0.00055|0.08%|0.66093|-1.15%|0.66077|-1.14%|1.317|8.614|0.000|25.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa2caa0403)|0.62916|0.63050|0.00032|0.05%|0.62966|-5.82%|0.62964|-5.80%|0.781|8.614|0.000|25.36 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58733|0.59325|0.00116|0.20%|0.58954|0.00%|0.58929|0.00%|0.578|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/76445cabc0)|0.58526|0.58908|0.00077|0.13%|0.58631|-0.55%|0.58608|-0.54%|2.751|8.245|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa2caa0403)|0.58559|0.59248|0.00101|0.17%|0.58649|-0.52%|0.58623|-0.52%|4.627|8.214|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa2caa0403)|0.51634|0.51974|0.00047|0.09%|0.51721|-12.27%|0.51713|-12.24%|3.078|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44173|0.44411|0.00056|0.13%|0.44285|0.00%|0.44281|0.00%|0.272|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/76445cabc0)|0.44451|0.44924|0.00068|0.15%|0.44579|0.66%|0.44573|0.66%|2.551|-8.614|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa2caa0403)|0.44435|0.44676|0.00053|0.12%|0.44569|0.64%|0.44569|0.65%|-0.315|-8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa2caa0403)|0.14339|0.14483|0.00027|0.19%|0.14375|-67.54%|0.14373|-67.54%|1.701|8.614|0.000|25.44 MB|
