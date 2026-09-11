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
| Time          |2026-09-11 01:05:02 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34549183115 ([Artifacts](https://github.com/php/php-src/actions/runs/34549183115/artifacts/10180858390))|
| Changeset  |https://github.com/php/php-src/compare/89687719b4..ac53f14223|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39895|0.40072|0.00032|0.08%|0.39948|0.00%|0.39939|0.00%|2.029|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89687719b4)|0.37505|0.37676|0.00034|0.09%|0.37541|-6.03%|0.37533|-6.03%|2.373|8.614|0.000|25.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac53f14223)|0.37445|0.37638|0.00033|0.09%|0.37497|-6.13%|0.37490|-6.13%|2.196|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67961|0.68363|0.00075|0.11%|0.68108|0.00%|0.68107|0.00%|0.450|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89687719b4)|0.67009|0.67145|0.00037|0.05%|0.67072|-1.52%|0.67070|-1.52%|0.389|8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac53f14223)|0.66833|0.67211|0.00062|0.09%|0.66908|-1.76%|0.66902|-1.77%|3.511|8.614|0.000|26.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59049|0.59426|0.00086|0.15%|0.59213|0.00%|0.59211|0.00%|0.179|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89687719b4)|0.59265|0.60016|0.00126|0.21%|0.59398|0.31%|0.59365|0.26%|2.784|-7.466|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac53f14223)|0.59142|0.59596|0.00107|0.18%|0.59292|0.13%|0.59264|0.09%|1.193|-3.502|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44346|0.44560|0.00048|0.11%|0.44453|0.00%|0.44454|0.00%|-0.062|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89687719b4)|0.45043|0.45220|0.00042|0.09%|0.45117|1.49%|0.45120|1.50%|0.384|-8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac53f14223)|0.44987|0.45293|0.00064|0.14%|0.45130|1.52%|0.45128|1.52%|0.141|-8.614|0.000|26.23 MB|
