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
| Time          |2026-06-12 01:34:15 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27388691296 ([Artifacts](https://github.com/php/php-src/actions/runs/27388691296/artifacts/7581689237))|
| Changeset  |https://github.com/php/php-src/compare/0e973e3792..8bbe4b4119|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39666|0.39895|0.00082|0.21%|0.39757|0.00%|0.39712|0.00%|0.416|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e973e3792)|0.38514|0.38609|0.00023|0.06%|0.38544|-3.05%|0.38540|-2.95%|1.220|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/8bbe4b4119)|0.38513|0.38698|0.00037|0.09%|0.38570|-2.98%|0.38565|-2.89%|2.024|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8bbe4b4119)|0.36045|0.36273|0.00053|0.15%|0.36128|-9.13%|0.36110|-9.07%|1.510|8.614|0.000|25.80 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67540|0.67756|0.00054|0.08%|0.67598|0.00%|0.67578|0.00%|1.529|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e973e3792)|0.66864|0.67093|0.00046|0.07%|0.66950|-0.96%|0.66950|-0.93%|0.502|8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/8bbe4b4119)|0.66943|0.67193|0.00046|0.07%|0.67003|-0.88%|0.66991|-0.87%|1.956|8.614|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8bbe4b4119)|0.63871|0.64596|0.00125|0.20%|0.63959|-5.38%|0.63926|-5.41%|3.805|8.614|0.000|25.93 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59069|0.59416|0.00079|0.13%|0.59239|0.00%|0.59229|0.00%|0.116|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e973e3792)|0.58731|0.59075|0.00063|0.11%|0.58791|-0.76%|0.58771|-0.77%|2.816|8.607|0.000|25.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/8bbe4b4119)|0.58735|0.59180|0.00112|0.19%|0.58872|-0.62%|0.58830|-0.67%|1.773|8.310|0.000|25.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8bbe4b4119)|0.51739|0.52202|0.00118|0.23%|0.51855|-12.46%|0.51813|-12.52%|1.685|8.614|0.000|26.32 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44357|0.44620|0.00057|0.13%|0.44455|0.00%|0.44455|0.00%|0.389|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e973e3792)|0.44990|0.45231|0.00067|0.15%|0.45121|1.50%|0.45130|1.52%|-0.211|-8.614|0.000|25.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/8bbe4b4119)|0.45028|0.45264|0.00058|0.13%|0.45140|1.54%|0.45137|1.53%|0.196|-8.614|0.000|25.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8bbe4b4119)|0.14547|0.15077|0.00093|0.64%|0.14610|-67.13%|0.14587|-67.19%|3.867|8.614|0.000|26.32 MB|
