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
| Time          |2026-06-09 01:22:36 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27177750132 ([Artifacts](https://github.com/php/php-src/actions/runs/27177750132/artifacts/7497007859))|
| Changeset  |https://github.com/php/php-src/compare/a7223e73a8..e9e2418d1c|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39471|0.39622|0.00026|0.07%|0.39512|0.00%|0.39510|0.00%|2.142|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7223e73a8)|0.38290|0.38455|0.00032|0.08%|0.38340|-2.97%|0.38333|-2.98%|1.502|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/e9e2418d1c)|0.38287|0.38470|0.00033|0.09%|0.38330|-2.99%|0.38325|-3.00%|2.540|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e9e2418d1c)|0.35884|0.36068|0.00033|0.09%|0.35938|-9.04%|0.35932|-9.05%|1.782|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67288|0.67553|0.00064|0.10%|0.67370|0.00%|0.67347|0.00%|1.238|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7223e73a8)|0.66566|0.66949|0.00065|0.10%|0.66659|-1.05%|0.66652|-1.03%|2.052|8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/e9e2418d1c)|0.66577|0.66970|0.00077|0.12%|0.66710|-0.98%|0.66705|-0.95%|1.018|8.614|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e9e2418d1c)|0.63581|0.63885|0.00064|0.10%|0.63660|-5.51%|0.63644|-5.50%|2.043|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58852|0.59256|0.00104|0.18%|0.59045|0.00%|0.59036|0.00%|0.080|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7223e73a8)|0.58519|0.59402|0.00128|0.22%|0.58618|-0.72%|0.58589|-0.76%|4.972|8.269|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/e9e2418d1c)|0.58520|0.58689|0.00036|0.06%|0.58592|-0.77%|0.58592|-0.75%|0.413|8.614|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e9e2418d1c)|0.51598|0.51987|0.00078|0.15%|0.51673|-12.49%|0.51650|-12.51%|2.841|8.614|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44334|0.44558|0.00057|0.13%|0.44454|0.00%|0.44454|0.00%|-0.078|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7223e73a8)|0.44996|0.45246|0.00062|0.14%|0.45126|1.51%|0.45121|1.50%|0.053|-8.614|0.000|25.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/e9e2418d1c)|0.44992|0.45246|0.00059|0.13%|0.45126|1.51%|0.45134|1.53%|-0.223|-8.614|0.000|25.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e9e2418d1c)|0.14541|0.14923|0.00081|0.55%|0.14605|-67.15%|0.14586|-67.19%|3.453|8.614|0.000|26.21 MB|
