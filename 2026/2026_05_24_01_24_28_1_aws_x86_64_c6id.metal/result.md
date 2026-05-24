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
| Time          |2026-05-24 01:24:28 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26348472665 ([Artifacts](https://github.com/php/php-src/actions/runs/26348472665/artifacts/7181493237))|
| Changeset  |https://github.com/php/php-src/compare/e22ba55be1..e22ba55be1|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39634|0.39750|0.00020|0.05%|0.39679|0.00%|0.39678|0.00%|0.839|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e22ba55be1)|0.38758|0.39045|0.00050|0.13%|0.38822|-2.16%|0.38809|-2.19%|2.548|8.614|0.000|25.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/e22ba55be1)|0.38759|0.38923|0.00042|0.11%|0.38812|-2.18%|0.38802|-2.21%|0.958|8.614|0.000|25.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e22ba55be1)|0.35998|0.36312|0.00063|0.18%|0.36062|-9.12%|0.36044|-9.16%|2.733|8.614|0.000|25.21 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67635|0.68224|0.00105|0.15%|0.67726|0.00%|0.67690|0.00%|2.837|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e22ba55be1)|0.67243|0.67486|0.00043|0.06%|0.67298|-0.63%|0.67292|-0.59%|2.029|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/e22ba55be1)|0.67266|0.67461|0.00036|0.05%|0.67311|-0.61%|0.67302|-0.57%|1.943|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e22ba55be1)|0.63940|0.67746|0.00554|0.86%|0.64100|-5.35%|0.63990|-5.47%|6.156|8.359|0.000|25.75 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59015|0.59598|0.00112|0.19%|0.59206|0.00%|0.59194|0.00%|0.886|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e22ba55be1)|0.58704|0.59013|0.00061|0.10%|0.58793|-0.70%|0.58787|-0.69%|2.012|8.614|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/e22ba55be1)|0.58682|0.58948|0.00055|0.09%|0.58765|-0.75%|0.58752|-0.75%|1.401|8.614|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e22ba55be1)|0.51739|0.52071|0.00083|0.16%|0.51816|-12.48%|0.51791|-12.51%|1.990|8.614|0.000|25.77 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44169|0.44424|0.00058|0.13%|0.44288|0.00%|0.44288|0.00%|0.137|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e22ba55be1)|0.44967|0.45414|0.00075|0.17%|0.45084|1.80%|0.45084|1.80%|1.890|-8.614|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/e22ba55be1)|0.44947|0.45330|0.00060|0.13%|0.45047|1.72%|0.45044|1.71%|2.048|-8.614|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e22ba55be1)|0.14363|0.14610|0.00045|0.31%|0.14398|-67.49%|0.14388|-67.51%|3.883|8.614|0.000|25.77 MB|
