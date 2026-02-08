### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-08 01:08:09 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21789862243 ([Artifacts](https://github.com/php/php-src/actions/runs/21789862243/artifacts/5420053978))|
| Changeset  |https://github.com/php/php-src/compare/52e9436629..52e9436629|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39625|0.39924|0.00057|0.14%|0.39783|0.00%|0.39791|0.00%|-0.983|0.000|1.000|26.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/52e9436629)|0.39013|0.39269|0.00054|0.14%|0.39083|-1.76%|0.39063|-1.83%|2.039|8.614|0.000|25.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/52e9436629)|0.39001|0.39192|0.00045|0.12%|0.39055|-1.83%|0.39046|-1.87%|1.848|8.614|0.000|25.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/52e9436629)|0.36270|0.36555|0.00052|0.14%|0.36336|-8.66%|0.36323|-8.71%|2.545|8.614|0.000|25.59 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67653|0.67912|0.00064|0.10%|0.67721|0.00%|0.67700|0.00%|1.725|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/52e9436629)|0.67421|0.67952|0.00087|0.13%|0.67517|-0.30%|0.67493|-0.31%|3.245|7.773|0.000|25.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/52e9436629)|0.67418|0.67878|0.00107|0.16%|0.67548|-0.26%|0.67517|-0.27%|1.560|6.573|0.000|25.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/52e9436629)|0.64193|0.65381|0.00171|0.27%|0.64274|-5.09%|0.64240|-5.11%|5.929|8.614|0.000|25.68 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58708|0.59326|0.00129|0.22%|0.58996|0.00%|0.58999|0.00%|0.158|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/52e9436629)|0.58784|0.58954|0.00033|0.06%|0.58855|-0.24%|0.58848|-0.26%|0.747|6.184|0.000|25.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/52e9436629)|0.58723|0.59161|0.00091|0.15%|0.58836|-0.27%|0.58814|-0.31%|2.552|6.091|0.000|25.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/52e9436629)|0.51696|0.52040|0.00057|0.11%|0.51781|-12.23%|0.51775|-12.24%|2.383|8.614|0.000|25.77 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44097|0.45408|0.00236|0.53%|0.44286|0.00%|0.44243|0.00%|4.285|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/52e9436629)|0.44170|0.44599|0.00113|0.25%|0.44343|0.13%|0.44312|0.16%|0.739|-4.140|0.000|25.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/52e9436629)|0.44091|0.44591|0.00090|0.20%|0.44324|0.09%|0.44320|0.17%|0.580|-4.333|0.000|25.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/52e9436629)|0.14304|0.14418|0.00023|0.16%|0.14347|-67.60%|0.14342|-67.58%|0.795|8.614|0.000|25.77 MB|
