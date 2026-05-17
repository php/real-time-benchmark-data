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
| Time          |2026-05-17 01:21:14 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25977862019 ([Artifacts](https://github.com/php/php-src/actions/runs/25977862019/artifacts/7038533545))|
| Changeset  |https://github.com/php/php-src/compare/b89e0ef305..51911cc1c6|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39277|0.39426|0.00029|0.07%|0.39316|0.00%|0.39311|0.00%|2.203|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b89e0ef305)|0.38541|0.38900|0.00074|0.19%|0.38608|-1.80%|0.38585|-1.85%|2.298|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/51911cc1c6)|0.38528|0.38762|0.00059|0.15%|0.38590|-1.85%|0.38570|-1.88%|1.215|8.614|0.000|25.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51911cc1c6)|0.35695|0.35988|0.00048|0.14%|0.35757|-9.05%|0.35746|-9.07%|2.662|8.614|0.000|25.51 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67071|0.67349|0.00066|0.10%|0.67149|0.00%|0.67124|0.00%|1.691|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b89e0ef305)|0.66161|0.66369|0.00050|0.07%|0.66255|-1.33%|0.66249|-1.30%|0.462|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/51911cc1c6)|0.66521|0.66682|0.00039|0.06%|0.66586|-0.84%|0.66581|-0.81%|0.689|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51911cc1c6)|0.63182|0.65233|0.00313|0.50%|0.63311|-5.72%|0.63235|-5.79%|5.296|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58618|0.59144|0.00120|0.20%|0.58884|0.00%|0.58880|0.00%|-0.075|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b89e0ef305)|0.58329|0.58622|0.00081|0.14%|0.58430|-0.77%|0.58392|-0.83%|0.758|8.607|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/51911cc1c6)|0.58373|0.58640|0.00071|0.12%|0.58439|-0.76%|0.58417|-0.79%|1.710|8.579|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51911cc1c6)|0.51398|0.51789|0.00093|0.18%|0.51535|-12.48%|0.51517|-12.50%|0.988|8.614|0.000|25.83 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44151|0.44421|0.00052|0.12%|0.44285|0.00%|0.44286|0.00%|0.067|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b89e0ef305)|0.44517|0.44795|0.00055|0.12%|0.44623|0.76%|0.44626|0.77%|0.387|-8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/51911cc1c6)|0.44615|0.44852|0.00048|0.11%|0.44710|0.96%|0.44706|0.95%|0.596|-8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51911cc1c6)|0.14326|0.14595|0.00049|0.34%|0.14382|-67.52%|0.14372|-67.55%|3.237|8.614|0.000|25.83 MB|
