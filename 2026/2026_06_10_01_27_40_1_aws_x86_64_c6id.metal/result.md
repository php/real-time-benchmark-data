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
| Time          |2026-06-10 01:27:40 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27246903309 ([Artifacts](https://github.com/php/php-src/actions/runs/27246903309/artifacts/7524994906))|
| Changeset  |https://github.com/php/php-src/compare/e9e2418d1c..a7f40d12a2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39641|0.39825|0.00031|0.08%|0.39698|0.00%|0.39691|0.00%|2.180|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e9e2418d1c)|0.38492|0.38637|0.00029|0.08%|0.38539|-2.92%|0.38537|-2.91%|1.694|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7f40d12a2)|0.38462|0.38805|0.00050|0.13%|0.38526|-2.95%|0.38516|-2.96%|4.052|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7f40d12a2)|0.36086|0.36339|0.00059|0.16%|0.36155|-8.93%|0.36135|-8.96%|1.673|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67517|0.67828|0.00065|0.10%|0.67594|0.00%|0.67572|0.00%|1.742|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e9e2418d1c)|0.66763|0.67178|0.00079|0.12%|0.66858|-1.09%|0.66848|-1.07%|2.122|8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7f40d12a2)|0.66759|0.67035|0.00056|0.08%|0.66834|-1.12%|0.66828|-1.10%|1.392|8.614|0.000|25.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7f40d12a2)|0.63769|0.64356|0.00112|0.17%|0.63895|-5.47%|0.63861|-5.49%|2.419|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59030|0.59536|0.00124|0.21%|0.59266|0.00%|0.59253|0.00%|0.036|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e9e2418d1c)|0.58707|0.59227|0.00086|0.15%|0.58794|-0.80%|0.58774|-0.81%|3.429|8.462|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7f40d12a2)|0.58721|0.59155|0.00090|0.15%|0.58805|-0.78%|0.58775|-0.81%|2.448|8.483|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7f40d12a2)|0.51833|0.52219|0.00065|0.12%|0.51893|-12.44%|0.51877|-12.45%|3.564|8.614|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44342|0.44755|0.00073|0.16%|0.44459|0.00%|0.44440|0.00%|1.889|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e9e2418d1c)|0.44960|0.45282|0.00060|0.13%|0.45137|1.52%|0.45127|1.55%|-0.019|-8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7f40d12a2)|0.45033|0.45428|0.00081|0.18%|0.45143|1.54%|0.45125|1.54%|1.254|-8.614|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7f40d12a2)|0.14552|0.14734|0.00027|0.18%|0.14590|-67.18%|0.14587|-67.18%|3.099|8.614|0.000|26.19 MB|
