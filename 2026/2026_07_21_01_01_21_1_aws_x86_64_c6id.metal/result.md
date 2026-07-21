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
| Time          |2026-07-21 01:01:21 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29791939864 ([Artifacts](https://github.com/php/php-src/actions/runs/29791939864/artifacts/8481434515))|
| Changeset  |https://github.com/php/php-src/compare/5c4bff6578..d0f00ccd98|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39461|0.39725|0.00082|0.21%|0.39534|0.00%|0.39493|0.00%|1.156|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c4bff6578)|0.38684|0.38818|0.00026|0.07%|0.38731|-2.03%|0.38726|-1.94%|0.949|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0f00ccd98)|0.38886|0.39377|0.00077|0.20%|0.38945|-1.49%|0.38930|-1.43%|4.385|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0f00ccd98)|0.35885|0.36059|0.00034|0.09%|0.35947|-9.07%|0.35936|-9.01%|1.234|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67248|0.67513|0.00058|0.09%|0.67337|0.00%|0.67318|0.00%|1.266|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c4bff6578)|0.66010|0.66516|0.00080|0.12%|0.66120|-1.81%|0.66103|-1.81%|2.774|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0f00ccd98)|0.66560|0.66946|0.00091|0.14%|0.66664|-1.00%|0.66634|-1.02%|1.492|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0f00ccd98)|0.63862|0.64340|0.00095|0.15%|0.63955|-5.02%|0.63938|-5.02%|2.862|8.614|0.000|26.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58866|0.59337|0.00100|0.17%|0.59047|0.00%|0.59049|0.00%|0.204|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c4bff6578)|0.58567|0.58901|0.00074|0.13%|0.58646|-0.68%|0.58622|-0.72%|1.726|8.579|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0f00ccd98)|0.58423|0.58832|0.00114|0.19%|0.58505|-0.92%|0.58461|-1.00%|2.119|8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0f00ccd98)|0.51369|0.51815|0.00071|0.14%|0.51455|-12.86%|0.51446|-12.88%|2.785|8.614|0.000|26.29 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44348|0.44539|0.00047|0.10%|0.44440|0.00%|0.44444|0.00%|-0.062|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c4bff6578)|0.44870|0.44991|0.00027|0.06%|0.44915|1.07%|0.44910|1.05%|0.443|-8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0f00ccd98)|0.44697|0.44995|0.00050|0.11%|0.44893|1.02%|0.44893|1.01%|-1.083|-8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0f00ccd98)|0.14424|0.14505|0.00021|0.15%|0.14457|-67.47%|0.14457|-67.47%|0.254|8.614|0.000|26.29 MB|
