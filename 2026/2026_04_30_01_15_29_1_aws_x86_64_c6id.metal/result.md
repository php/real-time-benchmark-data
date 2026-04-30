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
| Time          |2026-04-30 01:15:29 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25142249509 ([Artifacts](https://github.com/php/php-src/actions/runs/25142249509/artifacts/6721489989))|
| Changeset  |https://github.com/php/php-src/compare/9e529f4eef..14624997bb|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39957|0.40266|0.00071|0.18%|0.40028|0.00%|0.40002|0.00%|1.889|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9e529f4eef)|0.45537|0.45721|0.00036|0.08%|0.45585|13.88%|0.45578|13.94%|1.427|-8.614|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/14624997bb)|0.45733|0.46050|0.00059|0.13%|0.45805|14.43%|0.45793|14.48%|2.657|-8.614|0.000|25.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/14624997bb)|0.42724|0.42874|0.00036|0.08%|0.42772|6.85%|0.42767|6.91%|1.198|-8.614|0.000|25.38 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67483|0.67883|0.00067|0.10%|0.67561|0.00%|0.67544|0.00%|2.546|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9e529f4eef)|0.67225|0.67649|0.00063|0.09%|0.67283|-0.41%|0.67267|-0.41%|4.355|8.290|0.000|25.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/14624997bb)|0.68082|0.68552|0.00090|0.13%|0.68179|0.92%|0.68152|0.90%|2.526|-8.614|0.000|25.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/14624997bb)|0.64596|0.65640|0.00141|0.22%|0.64707|-4.22%|0.64689|-4.23%|6.068|8.614|0.000|25.29 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59226|0.59628|0.00104|0.17%|0.59409|0.00%|0.59407|0.00%|0.215|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9e529f4eef)|0.58815|0.59737|0.00129|0.22%|0.58943|-0.78%|0.58911|-0.84%|5.043|8.269|0.000|25.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/14624997bb)|0.58916|0.59144|0.00047|0.08%|0.58988|-0.71%|0.58978|-0.72%|1.606|8.614|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/14624997bb)|0.52175|0.52550|0.00073|0.14%|0.52250|-12.05%|0.52231|-12.08%|2.887|8.614|0.000|25.29 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44183|0.44457|0.00058|0.13%|0.44297|0.00%|0.44296|0.00%|0.474|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9e529f4eef)|0.44555|0.44981|0.00079|0.18%|0.44673|0.85%|0.44667|0.84%|2.261|-8.614|0.000|25.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/14624997bb)|0.44587|0.44916|0.00058|0.13%|0.44685|0.87%|0.44681|0.87%|1.303|-8.614|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/14624997bb)|0.14344|0.14487|0.00024|0.17%|0.14377|-67.54%|0.14373|-67.55%|1.978|8.614|0.000|25.29 MB|
