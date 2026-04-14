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
| Time          |2026-04-14 01:06:53 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24375301296 ([Artifacts](https://github.com/php/php-src/actions/runs/24375301296/artifacts/6418868563))|
| Changeset  |https://github.com/php/php-src/compare/21811294fa..d648cc1087|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39438|0.39671|0.00061|0.15%|0.39509|0.00%|0.39485|0.00%|1.458|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/21811294fa)|0.38810|0.39007|0.00045|0.11%|0.38876|-1.60%|0.38868|-1.56%|1.390|8.614|0.000|24.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/d648cc1087)|0.38660|0.38811|0.00035|0.09%|0.38707|-2.03%|0.38697|-2.00%|1.601|8.614|0.000|24.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d648cc1087)|0.35966|0.36141|0.00037|0.10%|0.36031|-8.80%|0.36026|-8.76%|1.192|8.614|0.000|25.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66782|0.67141|0.00063|0.09%|0.66859|0.00%|0.66839|0.00%|2.575|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/21811294fa)|0.66413|0.67229|0.00148|0.22%|0.66534|-0.49%|0.66492|-0.52%|4.046|7.924|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/d648cc1087)|0.66631|0.66878|0.00045|0.07%|0.66696|-0.24%|0.66687|-0.23%|1.637|8.331|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d648cc1087)|0.63305|0.66270|0.00432|0.68%|0.63471|-5.07%|0.63381|-5.17%|6.008|8.614|0.000|25.18 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58761|0.59323|0.00118|0.20%|0.59033|0.00%|0.59007|0.00%|0.478|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/21811294fa)|0.58378|0.58545|0.00032|0.06%|0.58451|-0.99%|0.58446|-0.95%|0.486|8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/d648cc1087)|0.58593|0.58811|0.00042|0.07%|0.58688|-0.58%|0.58692|-0.53%|0.307|8.593|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d648cc1087)|0.51507|0.51862|0.00061|0.12%|0.51642|-12.52%|0.51629|-12.50%|1.573|8.614|0.000|25.20 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44093|0.44981|0.00128|0.29%|0.44292|0.00%|0.44275|0.00%|3.570|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/21811294fa)|0.44427|0.44671|0.00052|0.12%|0.44569|0.63%|0.44570|0.66%|-0.509|-7.980|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/d648cc1087)|0.44540|0.44794|0.00058|0.13%|0.44666|0.85%|0.44675|0.90%|-0.399|-8.193|0.000|25.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d648cc1087)|0.14312|0.14399|0.00020|0.14%|0.14347|-67.61%|0.14342|-67.61%|0.586|8.614|0.000|25.18 MB|
