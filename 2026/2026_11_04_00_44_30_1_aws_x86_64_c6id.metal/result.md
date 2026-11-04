### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-04 00:44:30 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/41749030387 ([Artifacts](https://github.com/php/php-src/actions/runs/41749030387/artifacts/13286523867))|
| Changeset  |https://github.com/php/php-src/compare/0c7255dc52..e78d4e6a06|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39335|0.39426|0.00018|0.05%|0.39379|0.00%|0.39378|0.00%|0.309|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c7255dc52)|0.37684|0.37810|0.00022|0.06%|0.37717|-4.22%|0.37712|-4.23%|2.102|8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/e78d4e6a06)|0.37561|0.37762|0.00033|0.09%|0.37604|-4.51%|0.37599|-4.52%|3.177|8.614|0.000|25.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e78d4e6a06)|0.35014|0.35184|0.00029|0.08%|0.35068|-10.95%|0.35060|-10.96%|1.745|8.614|0.000|26.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67111|0.68725|0.00230|0.34%|0.67217|0.00%|0.67160|0.00%|6.029|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c7255dc52)|0.67612|0.69181|0.00225|0.33%|0.67697|0.71%|0.67649|0.73%|6.128|-8.276|0.000|26.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/e78d4e6a06)|0.68012|0.68416|0.00077|0.11%|0.68112|1.33%|0.68090|1.38%|2.540|-8.269|0.000|26.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e78d4e6a06)|0.64707|0.66599|0.00276|0.43%|0.64843|-3.53%|0.64772|-3.56%|5.591|8.614|0.000|26.33 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58727|0.58993|0.00059|0.10%|0.58877|0.00%|0.58878|0.00%|-0.265|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c7255dc52)|0.59306|0.59636|0.00066|0.11%|0.59375|0.85%|0.59355|0.81%|2.424|-8.614|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/e78d4e6a06)|0.59365|0.60135|0.00126|0.21%|0.59472|1.01%|0.59431|0.94%|3.492|-8.614|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e78d4e6a06)|0.51892|0.52182|0.00043|0.08%|0.51944|-11.77%|0.51939|-11.79%|3.711|8.614|0.000|26.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44312|0.45120|0.00140|0.32%|0.44495|0.00%|0.44469|0.00%|3.561|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c7255dc52)|0.45327|0.45604|0.00064|0.14%|0.45427|2.09%|0.45413|2.12%|0.479|-8.614|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/e78d4e6a06)|0.45335|0.45618|0.00066|0.14%|0.45492|2.24%|0.45490|2.30%|-0.281|-8.614|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e78d4e6a06)|0.14435|0.14717|0.00039|0.27%|0.14495|-67.42%|0.14492|-67.41%|3.802|8.614|0.000|26.40 MB|
