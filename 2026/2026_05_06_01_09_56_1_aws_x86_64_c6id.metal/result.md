### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-06 01:09:56 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25411060237 ([Artifacts](https://github.com/php/php-src/actions/runs/25411060237/artifacts/6821266005))|
| Changeset  |https://github.com/php/php-src/compare/c94cb02667..e5fa4ec36a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39278|0.39485|0.00052|0.13%|0.39319|0.00%|0.39304|0.00%|2.514|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c94cb02667)|0.38419|0.38566|0.00035|0.09%|0.38462|-2.18%|0.38452|-2.17%|1.702|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/e5fa4ec36a)|0.38482|0.38673|0.00046|0.12%|0.38534|-2.00%|0.38522|-1.99%|1.795|8.614|0.000|25.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e5fa4ec36a)|0.35650|0.35972|0.00049|0.14%|0.35726|-9.14%|0.35717|-9.12%|3.048|8.614|0.000|25.51 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67032|0.67274|0.00058|0.09%|0.67111|0.00%|0.67094|0.00%|1.297|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c94cb02667)|0.66606|0.66781|0.00033|0.05%|0.66653|-0.68%|0.66649|-0.66%|1.701|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/e5fa4ec36a)|0.66399|0.66732|0.00057|0.09%|0.66448|-0.99%|0.66433|-0.98%|3.111|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e5fa4ec36a)|0.63254|0.66811|0.00659|1.04%|0.63490|-5.39%|0.63309|-5.64%|4.030|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58654|0.59117|0.00104|0.18%|0.58840|0.00%|0.58825|0.00%|0.367|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c94cb02667)|0.58365|0.58648|0.00057|0.10%|0.58448|-0.67%|0.58438|-0.66%|1.802|8.614|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/e5fa4ec36a)|0.58320|0.58617|0.00064|0.11%|0.58417|-0.72%|0.58405|-0.72%|1.194|8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e5fa4ec36a)|0.51328|0.52474|0.00163|0.32%|0.51436|-12.58%|0.51407|-12.61%|5.597|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44158|0.44619|0.00074|0.17%|0.44282|0.00%|0.44279|0.00%|1.792|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c94cb02667)|0.44608|0.45016|0.00068|0.15%|0.44697|0.94%|0.44690|0.93%|2.311|-8.593|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/e5fa4ec36a)|0.44589|0.44809|0.00044|0.10%|0.44685|0.91%|0.44680|0.91%|0.358|-8.593|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e5fa4ec36a)|0.14354|0.14566|0.00035|0.25%|0.14418|-67.44%|0.14413|-67.45%|2.464|8.614|0.000|25.39 MB|
