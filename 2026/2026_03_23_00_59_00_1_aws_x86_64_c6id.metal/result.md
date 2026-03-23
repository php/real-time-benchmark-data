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
| Time          |2026-03-23 00:59:00 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23416890590 ([Artifacts](https://github.com/php/php-src/actions/runs/23416890590/artifacts/6051064280))|
| Changeset  |https://github.com/php/php-src/compare/61c83f8af5..00c0a9ba30|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39806|0.40022|0.00065|0.16%|0.39868|0.00%|0.39839|0.00%|1.289|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61c83f8af5)|0.39153|0.39285|0.00027|0.07%|0.39195|-1.69%|0.39189|-1.63%|1.389|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/00c0a9ba30)|0.39102|0.39621|0.00076|0.20%|0.39161|-1.77%|0.39143|-1.75%|4.696|8.614|0.000|25.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00c0a9ba30)|0.36469|0.36703|0.00036|0.10%|0.36516|-8.41%|0.36510|-8.36%|2.947|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67103|0.67352|0.00059|0.09%|0.67194|0.00%|0.67174|0.00%|0.996|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61c83f8af5)|0.66976|0.67341|0.00089|0.13%|0.67062|-0.20%|0.67028|-0.22%|2.043|6.780|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/00c0a9ba30)|0.66694|0.67007|0.00057|0.09%|0.66763|-0.64%|0.66748|-0.63%|2.174|8.614|0.000|25.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00c0a9ba30)|0.63576|0.65013|0.00220|0.35%|0.63686|-5.22%|0.63633|-5.27%|4.995|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59124|0.59640|0.00118|0.20%|0.59324|0.00%|0.59326|0.00%|0.566|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61c83f8af5)|0.58870|0.59269|0.00068|0.12%|0.58935|-0.65%|0.58920|-0.68%|3.802|8.448|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/00c0a9ba30)|0.58763|0.59144|0.00074|0.13%|0.58842|-0.81%|0.58824|-0.85%|2.672|8.600|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00c0a9ba30)|0.51882|0.52956|0.00154|0.30%|0.51980|-12.38%|0.51941|-12.45%|5.474|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44202|0.44446|0.00055|0.12%|0.44296|0.00%|0.44286|0.00%|0.492|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61c83f8af5)|0.44378|0.44662|0.00069|0.16%|0.44520|0.51%|0.44522|0.53%|-0.093|-8.524|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/00c0a9ba30)|0.44414|0.44644|0.00056|0.12%|0.44542|0.55%|0.44551|0.60%|-0.584|-8.593|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/00c0a9ba30)|0.14343|0.14548|0.00035|0.25%|0.14389|-67.52%|0.14383|-67.52%|2.078|8.614|0.000|25.36 MB|
