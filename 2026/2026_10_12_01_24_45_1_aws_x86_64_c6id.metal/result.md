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
| Time          |2026-10-12 01:24:45 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/38191761743 ([Artifacts](https://github.com/php/php-src/actions/runs/38191761743/artifacts/11723045934))|
| Changeset  |https://github.com/php/php-src/compare/12df767920..4a41768eec|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39902|0.40036|0.00029|0.07%|0.39957|0.00%|0.39952|0.00%|0.877|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/12df767920)|0.37996|0.38172|0.00034|0.09%|0.38054|-4.76%|0.38044|-4.78%|1.314|8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a41768eec)|0.37826|0.38204|0.00063|0.17%|0.38020|-4.85%|0.38012|-4.86%|0.121|8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a41768eec)|0.35590|0.35777|0.00032|0.09%|0.35639|-10.81%|0.35632|-10.81%|2.159|8.614|0.000|26.19 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68018|0.68476|0.00094|0.14%|0.68170|0.00%|0.68155|0.00%|1.322|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/12df767920)|0.67234|0.67569|0.00051|0.08%|0.67298|-1.28%|0.67291|-1.27%|3.234|8.614|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a41768eec)|0.67324|0.67553|0.00034|0.05%|0.67410|-1.11%|0.67404|-1.10%|1.510|8.614|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a41768eec)|0.64128|0.65247|0.00174|0.27%|0.64229|-5.78%|0.64184|-5.83%|4.649|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59136|0.59583|0.00085|0.14%|0.59270|0.00%|0.59265|0.00%|1.135|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/12df767920)|0.59088|0.59975|0.00128|0.22%|0.59194|-0.13%|0.59173|-0.16%|4.979|5.563|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a41768eec)|0.59061|0.59519|0.00094|0.16%|0.59149|-0.20%|0.59129|-0.23%|3.100|7.145|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a41768eec)|0.51923|0.53042|0.00158|0.30%|0.52018|-12.23%|0.51983|-12.29%|5.823|8.614|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44382|0.44617|0.00054|0.12%|0.44486|0.00%|0.44483|0.00%|0.301|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/12df767920)|0.45098|0.45534|0.00070|0.16%|0.45199|1.60%|0.45187|1.58%|3.263|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a41768eec)|0.45106|0.45486|0.00062|0.14%|0.45209|1.63%|0.45200|1.61%|1.836|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a41768eec)|0.14346|0.14484|0.00033|0.23%|0.14412|-67.60%|0.14415|-67.60%|0.139|8.614|0.000|26.21 MB|
