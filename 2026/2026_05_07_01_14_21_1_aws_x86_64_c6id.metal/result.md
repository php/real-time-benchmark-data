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
| Time          |2026-05-07 01:14:21 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25470291974 ([Artifacts](https://github.com/php/php-src/actions/runs/25470291974/artifacts/6845555100))|
| Changeset  |https://github.com/php/php-src/compare/e5fa4ec36a..0173ef4b84|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39638|0.39795|0.00024|0.06%|0.39677|0.00%|0.39673|0.00%|2.358|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e5fa4ec36a)|0.38876|0.39081|0.00036|0.09%|0.38924|-1.90%|0.38917|-1.90%|2.133|8.614|0.000|25.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/0173ef4b84)|0.38921|0.39194|0.00043|0.11%|0.38956|-1.82%|0.38951|-1.82%|3.962|8.614|0.000|25.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0173ef4b84)|0.36071|0.36310|0.00062|0.17%|0.36127|-8.95%|0.36113|-8.97%|1.860|8.614|0.000|25.52 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67589|0.68369|0.00113|0.17%|0.67666|0.00%|0.67638|0.00%|5.142|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e5fa4ec36a)|0.66949|0.67174|0.00040|0.06%|0.66989|-1.00%|0.66980|-0.97%|2.502|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/0173ef4b84)|0.66866|0.67032|0.00040|0.06%|0.66910|-1.12%|0.66899|-1.09%|1.258|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0173ef4b84)|0.63886|0.64272|0.00079|0.12%|0.63955|-5.48%|0.63934|-5.48%|2.501|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58980|0.59440|0.00106|0.18%|0.59187|0.00%|0.59190|0.00%|0.277|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e5fa4ec36a)|0.58642|0.59011|0.00074|0.13%|0.58736|-0.76%|0.58720|-0.79%|2.358|8.572|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/0173ef4b84)|0.58632|0.58939|0.00080|0.14%|0.58729|-0.77%|0.58706|-0.82%|1.585|8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0173ef4b84)|0.51762|0.52103|0.00084|0.16%|0.51868|-12.37%|0.51839|-12.42%|1.684|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44168|0.44607|0.00073|0.17%|0.44296|0.00%|0.44286|0.00%|1.665|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e5fa4ec36a)|0.44551|0.44791|0.00054|0.12%|0.44675|0.85%|0.44668|0.86%|0.154|-8.576|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/0173ef4b84)|0.44609|0.44859|0.00054|0.12%|0.44689|0.89%|0.44679|0.89%|0.801|-8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0173ef4b84)|0.14373|0.14575|0.00042|0.29%|0.14418|-67.45%|0.14409|-67.46%|2.615|8.614|0.000|25.39 MB|
