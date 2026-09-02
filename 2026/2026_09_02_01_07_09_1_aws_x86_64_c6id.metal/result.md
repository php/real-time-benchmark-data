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
| Time          |2026-09-02 01:07:09 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33578071809 ([Artifacts](https://github.com/php/php-src/actions/runs/33578071809/artifacts/9828062368))|
| Changeset  |https://github.com/php/php-src/compare/4923c6079e..759829bc2f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39911|0.40060|0.00024|0.06%|0.39952|0.00%|0.39949|0.00%|1.810|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4923c6079e)|0.37365|0.37560|0.00038|0.10%|0.37405|-6.38%|0.37391|-6.40%|2.343|8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/759829bc2f)|0.37336|0.37565|0.00049|0.13%|0.37386|-6.42%|0.37370|-6.45%|2.300|8.614|0.000|25.83 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67996|0.68319|0.00081|0.12%|0.68135|0.00%|0.68140|0.00%|0.341|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4923c6079e)|0.67266|0.67510|0.00050|0.07%|0.67356|-1.14%|0.67349|-1.16%|1.036|8.614|0.000|25.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/759829bc2f)|0.67214|0.67592|0.00065|0.10%|0.67277|-1.26%|0.67256|-1.30%|2.726|8.614|0.000|25.91 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59105|0.59421|0.00085|0.14%|0.59232|0.00%|0.59223|0.00%|0.601|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4923c6079e)|0.58904|0.60033|0.00183|0.31%|0.59050|-0.31%|0.58999|-0.38%|3.640|7.056|0.000|25.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/759829bc2f)|0.58915|0.59394|0.00074|0.13%|0.59004|-0.39%|0.58980|-0.41%|3.105|8.283|0.000|25.95 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44346|0.44592|0.00054|0.12%|0.44470|0.00%|0.44468|0.00%|0.012|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4923c6079e)|0.44977|0.45299|0.00070|0.16%|0.45129|1.48%|0.45123|1.47%|0.157|-8.614|0.000|25.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/759829bc2f)|0.44978|0.45289|0.00061|0.14%|0.45110|1.44%|0.45105|1.43%|0.214|-8.614|0.000|25.95 MB|
