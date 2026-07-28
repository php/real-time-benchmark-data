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
| Time          |2026-07-28 00:59:50 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30318921953 ([Artifacts](https://github.com/php/php-src/actions/runs/30318921953/artifacts/8674145467))|
| Changeset  |https://github.com/php/php-src/compare/7ad79be655..c5cdea5ada|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39954|0.40178|0.00072|0.18%|0.40036|0.00%|0.40001|0.00%|1.060|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ad79be655)|0.39306|0.39462|0.00035|0.09%|0.39348|-1.72%|0.39342|-1.65%|1.576|8.614|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5cdea5ada)|0.39225|0.39390|0.00034|0.09%|0.39271|-1.91%|0.39260|-1.85%|2.172|8.614|0.000|25.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5cdea5ada)|0.36550|0.36728|0.00036|0.10%|0.36628|-8.51%|0.36622|-8.45%|0.841|8.614|0.000|25.84 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67852|0.68555|0.00101|0.15%|0.67928|0.00%|0.67912|0.00%|5.107|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ad79be655)|0.67170|0.67395|0.00049|0.07%|0.67239|-1.01%|0.67225|-1.01%|1.604|8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5cdea5ada)|0.67629|0.68717|0.00151|0.22%|0.67700|-0.34%|0.67675|-0.35%|6.487|8.269|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5cdea5ada)|0.64323|0.64612|0.00057|0.09%|0.64389|-5.21%|0.64375|-5.21%|2.287|8.614|0.000|26.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59324|0.59677|0.00087|0.15%|0.59502|0.00%|0.59496|0.00%|0.101|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ad79be655)|0.58927|0.59766|0.00127|0.21%|0.59036|-0.78%|0.59014|-0.81%|4.380|8.255|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5cdea5ada)|0.58746|0.59089|0.00082|0.14%|0.58854|-1.09%|0.58835|-1.11%|1.666|8.614|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5cdea5ada)|0.52052|0.52471|0.00077|0.15%|0.52146|-12.36%|0.52139|-12.37%|2.315|8.614|0.000|26.16 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44334|0.44587|0.00054|0.12%|0.44462|0.00%|0.44456|0.00%|0.237|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ad79be655)|0.44847|0.45015|0.00037|0.08%|0.44949|1.10%|0.44950|1.11%|-0.268|-8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5cdea5ada)|0.44883|0.45195|0.00057|0.13%|0.44957|1.11%|0.44948|1.11%|1.601|-8.614|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5cdea5ada)|0.14424|0.14782|0.00049|0.34%|0.14470|-67.45%|0.14467|-67.46%|5.306|8.614|0.000|26.16 MB|
