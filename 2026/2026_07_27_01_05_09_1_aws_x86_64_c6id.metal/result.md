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
| Time          |2026-07-27 01:05:09 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30228906351 ([Artifacts](https://github.com/php/php-src/actions/runs/30228906351/artifacts/8640070976))|
| Changeset  |https://github.com/php/php-src/compare/f465d35334..7ad79be655|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39649|0.39875|0.00077|0.19%|0.39740|0.00%|0.39697|0.00%|0.732|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f465d35334)|0.38997|0.39200|0.00042|0.11%|0.39044|-1.75%|0.39039|-1.66%|1.917|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ad79be655)|0.39104|0.39337|0.00051|0.13%|0.39172|-1.43%|0.39156|-1.36%|2.125|8.614|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ad79be655)|0.36245|0.36582|0.00057|0.16%|0.36326|-8.59%|0.36318|-8.51%|2.424|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67532|0.67940|0.00071|0.10%|0.67617|0.00%|0.67604|0.00%|2.131|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f465d35334)|0.66635|0.67048|0.00072|0.11%|0.66710|-1.34%|0.66690|-1.35%|2.908|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ad79be655)|0.66804|0.67433|0.00097|0.14%|0.66892|-1.07%|0.66858|-1.10%|4.050|8.614|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ad79be655)|0.63673|0.64516|0.00120|0.19%|0.63758|-5.71%|0.63734|-5.73%|5.482|8.614|0.000|26.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59117|0.59537|0.00107|0.18%|0.59300|0.00%|0.59297|0.00%|0.399|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f465d35334)|0.58698|0.59106|0.00066|0.11%|0.58769|-0.90%|0.58755|-0.91%|3.126|8.614|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ad79be655)|0.58654|0.59000|0.00065|0.11%|0.58721|-0.98%|0.58707|-1.00%|2.590|8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ad79be655)|0.51644|0.52095|0.00108|0.21%|0.51746|-12.74%|0.51716|-12.78%|2.130|8.614|0.000|26.15 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44349|0.44568|0.00055|0.12%|0.44440|0.00%|0.44433|0.00%|0.407|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f465d35334)|0.44840|0.45236|0.00069|0.15%|0.44932|1.11%|0.44924|1.11%|3.169|-8.614|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/7ad79be655)|0.44858|0.44996|0.00033|0.07%|0.44940|1.13%|0.44944|1.15%|-0.411|-8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7ad79be655)|0.14406|0.14603|0.00031|0.21%|0.14452|-67.48%|0.14450|-67.48%|2.415|8.614|0.000|26.15 MB|
