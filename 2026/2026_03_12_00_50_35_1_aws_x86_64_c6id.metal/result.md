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
| Time          |2026-03-12 00:50:35 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22981565949 ([Artifacts](https://github.com/php/php-src/actions/runs/22981565949/artifacts/5882858201))|
| Changeset  |https://github.com/php/php-src/compare/ed887241be..113893b714|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39416|0.39750|0.00061|0.16%|0.39478|0.00%|0.39463|0.00%|2.799|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed887241be)|0.38711|0.39258|0.00080|0.21%|0.38772|-1.79%|0.38755|-1.79%|4.839|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/113893b714)|0.38794|0.39055|0.00041|0.11%|0.38867|-1.55%|0.38862|-1.52%|1.847|8.614|0.000|25.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113893b714)|0.35946|0.36139|0.00041|0.11%|0.35994|-8.82%|0.35986|-8.81%|1.798|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66701|0.67148|0.00079|0.12%|0.66784|0.00%|0.66764|0.00%|2.963|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed887241be)|0.66270|0.66673|0.00062|0.09%|0.66335|-0.67%|0.66321|-0.66%|3.478|8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/113893b714)|0.66595|0.66838|0.00046|0.07%|0.66648|-0.20%|0.66637|-0.19%|2.025|7.993|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113893b714)|0.63215|0.63522|0.00047|0.07%|0.63269|-5.26%|0.63260|-5.25%|3.370|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58784|0.59453|0.00118|0.20%|0.59032|0.00%|0.59031|0.00%|0.899|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed887241be)|0.58526|0.58836|0.00052|0.09%|0.58603|-0.73%|0.58594|-0.74%|3.087|8.600|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/113893b714)|0.58470|0.58786|0.00057|0.10%|0.58544|-0.83%|0.58537|-0.84%|2.949|8.607|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113893b714)|0.51474|0.52513|0.00158|0.31%|0.51567|-12.65%|0.51528|-12.71%|4.830|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44182|0.44577|0.00071|0.16%|0.44278|0.00%|0.44275|0.00%|1.631|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed887241be)|0.44245|0.44652|0.00094|0.21%|0.44480|0.46%|0.44488|0.48%|-0.435|-7.656|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/113893b714)|0.44376|0.44710|0.00074|0.17%|0.44548|0.61%|0.44549|0.62%|-0.328|-8.359|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/113893b714)|0.14335|0.14428|0.00024|0.17%|0.14376|-67.53%|0.14372|-67.54%|0.571|8.614|0.000|25.33 MB|
