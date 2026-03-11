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
| Time          |2026-03-11 00:52:07 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22931288781 ([Artifacts](https://github.com/php/php-src/actions/runs/22931288781/artifacts/5861914315))|
| Changeset  |https://github.com/php/php-src/compare/f93b17076a..ed887241be|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39650|0.39782|0.00023|0.06%|0.39682|0.00%|0.39678|0.00%|2.501|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f93b17076a)|0.38999|0.39184|0.00035|0.09%|0.39058|-1.57%|0.39054|-1.57%|2.309|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed887241be)|0.38958|0.39210|0.00048|0.12%|0.39002|-1.71%|0.38989|-1.73%|3.257|8.614|0.000|25.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed887241be)|0.36222|0.36440|0.00035|0.10%|0.36263|-8.62%|0.36254|-8.63%|2.888|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66945|0.67438|0.00082|0.12%|0.67020|0.00%|0.66994|0.00%|3.165|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f93b17076a)|0.66815|0.67018|0.00043|0.06%|0.66884|-0.20%|0.66878|-0.17%|1.292|8.073|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed887241be)|0.66486|0.66659|0.00047|0.07%|0.66551|-0.70%|0.66533|-0.69%|0.876|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed887241be)|0.63604|0.63962|0.00075|0.12%|0.63729|-4.91%|0.63722|-4.88%|1.014|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58996|0.59402|0.00098|0.17%|0.59165|0.00%|0.59154|0.00%|0.352|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f93b17076a)|0.58623|0.59407|0.00126|0.21%|0.58714|-0.76%|0.58680|-0.80%|3.937|8.269|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed887241be)|0.58716|0.59504|0.00126|0.21%|0.58812|-0.60%|0.58780|-0.63%|3.970|8.111|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed887241be)|0.51719|0.52111|0.00087|0.17%|0.51822|-12.41%|0.51793|-12.44%|2.244|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44151|0.44412|0.00053|0.12%|0.44286|0.00%|0.44284|0.00%|-0.193|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f93b17076a)|0.44398|0.44665|0.00056|0.12%|0.44539|0.57%|0.44545|0.59%|-0.244|-8.607|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed887241be)|0.44315|0.44635|0.00074|0.17%|0.44490|0.46%|0.44498|0.48%|-0.189|-8.366|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed887241be)|0.14331|0.14549|0.00037|0.26%|0.14393|-67.50%|0.14386|-67.51%|1.969|8.614|0.000|25.27 MB|
