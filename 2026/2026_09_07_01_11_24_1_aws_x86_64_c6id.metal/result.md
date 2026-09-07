### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-09-07 01:11:24 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34072178513 ([Artifacts](https://github.com/php/php-src/actions/runs/34072178513/artifacts/10001349386))|
| Changeset  |https://github.com/php/php-src/compare/5be4de10e7..810a9e58dc|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39896|0.40092|0.00029|0.07%|0.39957|0.00%|0.39954|0.00%|2.061|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5be4de10e7)|0.37341|0.37459|0.00022|0.06%|0.37377|-6.46%|0.37372|-6.46%|1.148|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/810a9e58dc)|0.37311|0.37423|0.00021|0.06%|0.37349|-6.53%|0.37346|-6.53%|0.931|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68011|0.68371|0.00067|0.10%|0.68193|0.00%|0.68189|0.00%|0.139|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5be4de10e7)|0.67180|0.67570|0.00070|0.10%|0.67267|-1.36%|0.67240|-1.39%|2.002|8.614|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/810a9e58dc)|0.67498|0.67920|0.00075|0.11%|0.67591|-0.88%|0.67587|-0.88%|2.844|8.614|0.000|26.18 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59089|0.59465|0.00082|0.14%|0.59223|0.00%|0.59205|0.00%|0.847|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5be4de10e7)|0.59075|0.59409|0.00069|0.12%|0.59161|-0.10%|0.59134|-0.12%|1.319|4.047|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/810a9e58dc)|0.59098|0.59506|0.00079|0.13%|0.59195|-0.05%|0.59178|-0.05%|2.225|2.161|0.031|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44334|0.44790|0.00070|0.16%|0.44471|0.00%|0.44467|0.00%|1.777|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5be4de10e7)|0.45048|0.45248|0.00047|0.11%|0.45160|1.55%|0.45152|1.54%|-0.027|-8.614|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/810a9e58dc)|0.45058|0.45305|0.00050|0.11%|0.45141|1.51%|0.45137|1.51%|0.791|-8.614|0.000|26.23 MB|
