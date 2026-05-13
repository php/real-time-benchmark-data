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
| Time          |2026-05-13 01:19:24 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25772138357 ([Artifacts](https://github.com/php/php-src/actions/runs/25772138357/artifacts/6960154279))|
| Changeset  |https://github.com/php/php-src/compare/10dad92c8b..c0af26858a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39281|0.39494|0.00068|0.17%|0.39349|0.00%|0.39319|0.00%|1.197|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10dad92c8b)|0.38620|0.38920|0.00079|0.20%|0.38687|-1.68%|0.38656|-1.69%|1.694|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0af26858a)|0.38575|0.38735|0.00041|0.11%|0.38620|-1.85%|0.38607|-1.81%|1.723|8.614|0.000|25.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0af26858a)|0.35741|0.35976|0.00048|0.13%|0.35819|-8.97%|0.35813|-8.92%|1.398|8.614|0.000|25.44 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67095|0.67460|0.00065|0.10%|0.67161|0.00%|0.67145|0.00%|2.506|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10dad92c8b)|0.66130|0.66423|0.00057|0.09%|0.66202|-1.43%|0.66193|-1.42%|1.427|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0af26858a)|0.66403|0.66644|0.00050|0.08%|0.66475|-1.02%|0.66464|-1.01%|1.766|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0af26858a)|0.62983|0.63380|0.00060|0.10%|0.63081|-6.08%|0.63078|-6.06%|2.515|8.614|0.000|25.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58614|0.59081|0.00107|0.18%|0.58823|0.00%|0.58818|0.00%|0.194|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10dad92c8b)|0.58328|0.58570|0.00046|0.08%|0.58402|-0.72%|0.58396|-0.72%|1.723|8.614|0.000|25.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0af26858a)|0.58255|0.58967|0.00123|0.21%|0.58364|-0.78%|0.58317|-0.85%|2.908|8.283|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0af26858a)|0.51247|0.52296|0.00160|0.31%|0.51352|-12.70%|0.51308|-12.77%|4.540|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44160|0.44535|0.00075|0.17%|0.44303|0.00%|0.44290|0.00%|0.615|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10dad92c8b)|0.44569|0.45186|0.00098|0.22%|0.44699|0.89%|0.44684|0.89%|3.198|-8.614|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0af26858a)|0.44445|0.44696|0.00048|0.11%|0.44570|0.60%|0.44571|0.64%|-0.342|-8.552|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0af26858a)|0.14313|0.14540|0.00032|0.23%|0.14355|-67.60%|0.14353|-67.59%|3.859|8.614|0.000|25.40 MB|
