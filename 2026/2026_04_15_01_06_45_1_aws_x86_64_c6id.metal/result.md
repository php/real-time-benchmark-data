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
| Time          |2026-04-15 01:06:45 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24430982781 ([Artifacts](https://github.com/php/php-src/actions/runs/24430982781/artifacts/6441619809))|
| Changeset  |https://github.com/php/php-src/compare/d648cc1087..1195f271d0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39950|0.40195|0.00060|0.15%|0.40016|0.00%|0.39992|0.00%|1.795|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d648cc1087)|0.39168|0.39350|0.00030|0.08%|0.39210|-2.01%|0.39205|-1.97%|2.240|8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/1195f271d0)|0.39103|0.39265|0.00042|0.11%|0.39158|-2.14%|0.39141|-2.13%|1.230|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1195f271d0)|0.36480|0.36728|0.00056|0.15%|0.36553|-8.65%|0.36537|-8.64%|1.756|8.614|0.000|25.32 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67307|0.67765|0.00078|0.12%|0.67394|0.00%|0.67370|0.00%|2.655|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d648cc1087)|0.67199|0.67545|0.00059|0.09%|0.67256|-0.20%|0.67237|-0.20%|2.787|7.842|0.000|25.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/1195f271d0)|0.67149|0.67481|0.00066|0.10%|0.67215|-0.26%|0.67195|-0.26%|2.458|7.911|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1195f271d0)|0.63853|0.64090|0.00054|0.09%|0.63928|-5.14%|0.63913|-5.13%|1.452|8.614|0.000|25.19 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59292|0.59745|0.00094|0.16%|0.59483|0.00%|0.59496|0.00%|0.113|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d648cc1087)|0.59080|0.59361|0.00048|0.08%|0.59183|-0.50%|0.59177|-0.54%|1.441|8.559|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/1195f271d0)|0.59018|0.59793|0.00138|0.23%|0.59184|-0.50%|0.59156|-0.57%|3.678|7.842|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1195f271d0)|0.52127|0.52511|0.00063|0.12%|0.52233|-12.19%|0.52225|-12.22%|2.744|8.614|0.000|25.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44185|0.44426|0.00058|0.13%|0.44294|0.00%|0.44289|0.00%|0.326|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d648cc1087)|0.44579|0.44855|0.00058|0.13%|0.44683|0.88%|0.44676|0.87%|0.552|-8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/1195f271d0)|0.44521|0.45019|0.00071|0.16%|0.44642|0.79%|0.44637|0.78%|3.039|-8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1195f271d0)|0.14323|0.14666|0.00046|0.32%|0.14371|-67.55%|0.14366|-67.56%|5.441|8.614|0.000|25.21 MB|
