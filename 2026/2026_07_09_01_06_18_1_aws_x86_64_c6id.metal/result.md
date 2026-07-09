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
| Time          |2026-07-09 01:06:18 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28986748256 ([Artifacts](https://github.com/php/php-src/actions/runs/28986748256/artifacts/8186992259))|
| Changeset  |https://github.com/php/php-src/compare/9390b68d5d..9dc29aafa5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39627|0.39783|0.00026|0.07%|0.39673|0.00%|0.39666|0.00%|2.365|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9390b68d5d)|0.38685|0.38846|0.00036|0.09%|0.38732|-2.37%|0.38719|-2.39%|1.337|8.614|0.000|25.74 MB|
|[PHP - master](https://github.com/php/php-src/commit/9dc29aafa5)|0.38697|0.38848|0.00028|0.07%|0.38747|-2.33%|0.38741|-2.33%|1.812|8.614|0.000|25.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9dc29aafa5)|0.36373|0.36663|0.00048|0.13%|0.36439|-8.15%|0.36432|-8.15%|2.238|8.614|0.000|25.74 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67479|0.67765|0.00071|0.10%|0.67559|0.00%|0.67533|0.00%|1.445|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9390b68d5d)|0.66677|0.67003|0.00067|0.10%|0.66746|-1.20%|0.66727|-1.19%|1.886|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/9dc29aafa5)|0.66629|0.66953|0.00064|0.10%|0.66701|-1.27%|0.66684|-1.26%|1.923|8.614|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9dc29aafa5)|0.63634|0.63797|0.00039|0.06%|0.63691|-5.73%|0.63685|-5.70%|1.018|8.614|0.000|26.19 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59063|0.59532|0.00109|0.18%|0.59218|0.00%|0.59204|0.00%|0.864|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9390b68d5d)|0.58809|0.59313|0.00096|0.16%|0.58938|-0.47%|0.58908|-0.50%|2.405|8.021|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/9dc29aafa5)|0.58792|0.59128|0.00063|0.11%|0.58877|-0.57%|0.58859|-0.58%|1.918|8.517|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9dc29aafa5)|0.51849|0.52976|0.00188|0.36%|0.51973|-12.23%|0.51912|-12.32%|3.583|8.614|0.000|26.29 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44323|0.45210|0.00138|0.31%|0.44480|0.00%|0.44464|0.00%|3.385|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9390b68d5d)|0.44921|0.45364|0.00074|0.16%|0.45076|1.34%|0.45074|1.37%|1.431|-8.283|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/9dc29aafa5)|0.44951|0.45216|0.00059|0.13%|0.45081|1.35%|0.45069|1.36%|0.259|-8.276|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9dc29aafa5)|0.14426|0.14495|0.00017|0.12%|0.14456|-67.50%|0.14458|-67.48%|0.192|8.614|0.000|26.29 MB|
