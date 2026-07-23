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
| Time          |2026-07-23 01:02:21 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29970697765 ([Artifacts](https://github.com/php/php-src/actions/runs/29970697765/artifacts/8550385014))|
| Changeset  |https://github.com/php/php-src/compare/786e42386d..28dab5fafb|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39475|0.39852|0.00089|0.22%|0.39577|0.00%|0.39534|0.00%|0.959|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/786e42386d)|0.38836|0.38992|0.00034|0.09%|0.38901|-1.71%|0.38893|-1.62%|1.072|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/28dab5fafb)|0.38807|0.39323|0.00095|0.25%|0.38864|-1.80%|0.38842|-1.75%|4.127|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/28dab5fafb)|0.36067|0.36340|0.00049|0.14%|0.36130|-8.71%|0.36118|-8.64%|2.245|8.614|0.000|25.74 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67342|0.67618|0.00059|0.09%|0.67426|0.00%|0.67410|0.00%|1.154|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/786e42386d)|0.66653|0.66889|0.00057|0.09%|0.66733|-1.03%|0.66716|-1.03%|1.146|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/28dab5fafb)|0.66987|0.67145|0.00040|0.06%|0.67039|-0.57%|0.67026|-0.57%|1.001|8.614|0.000|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/28dab5fafb)|0.63990|0.64313|0.00051|0.08%|0.64045|-5.01%|0.64029|-5.02%|3.179|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58836|0.59265|0.00096|0.16%|0.59052|0.00%|0.59051|0.00%|-0.057|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/786e42386d)|0.58444|0.58859|0.00078|0.13%|0.58545|-0.86%|0.58533|-0.88%|1.461|8.607|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/28dab5fafb)|0.58489|0.58825|0.00076|0.13%|0.58561|-0.83%|0.58548|-0.85%|2.550|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/28dab5fafb)|0.51356|0.51711|0.00081|0.16%|0.51448|-12.88%|0.51425|-12.92%|2.087|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44335|0.44680|0.00066|0.15%|0.44451|0.00%|0.44451|0.00%|0.736|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/786e42386d)|0.44798|0.44984|0.00043|0.10%|0.44901|1.01%|0.44903|1.02%|-0.216|-8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/28dab5fafb)|0.44816|0.45133|0.00052|0.11%|0.44892|0.99%|0.44894|1.00%|1.943|-8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/28dab5fafb)|0.14387|0.14501|0.00021|0.15%|0.14448|-67.50%|0.14448|-67.50%|-0.066|8.614|0.000|26.28 MB|
