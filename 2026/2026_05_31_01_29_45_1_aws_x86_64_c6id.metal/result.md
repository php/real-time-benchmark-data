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
| Time          |2026-05-31 01:29:45 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26699997863 ([Artifacts](https://github.com/php/php-src/actions/runs/26699997863/artifacts/7313101842))|
| Changeset  |https://github.com/php/php-src/compare/f2b371e747..7092ff5387|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39961|0.40187|0.00075|0.19%|0.40038|0.00%|0.40001|0.00%|0.890|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f2b371e747)|0.39423|0.39564|0.00028|0.07%|0.39465|-1.43%|0.39458|-1.36%|1.345|8.614|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/7092ff5387)|0.39169|0.39459|0.00052|0.13%|0.39218|-2.05%|0.39204|-1.99%|3.395|8.614|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7092ff5387)|0.36564|0.36741|0.00042|0.11%|0.36615|-8.55%|0.36605|-8.49%|1.714|8.614|0.000|25.82 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67902|0.68124|0.00056|0.08%|0.67990|0.00%|0.67977|0.00%|0.623|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f2b371e747)|0.67296|0.67624|0.00055|0.08%|0.67382|-0.89%|0.67368|-0.90%|2.222|8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/7092ff5387)|0.67854|0.68144|0.00070|0.10%|0.67941|-0.07%|0.67925|-0.08%|1.246|4.322|0.000|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7092ff5387)|0.64445|0.65204|0.00132|0.20%|0.64567|-5.03%|0.64527|-5.07%|2.826|8.614|0.000|26.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59316|0.59684|0.00089|0.15%|0.59502|0.00%|0.59517|0.00%|-0.278|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f2b371e747)|0.59253|0.59627|0.00072|0.12%|0.59334|-0.28%|0.59313|-0.34%|2.757|7.359|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/7092ff5387)|0.59159|0.59734|0.00138|0.23%|0.59288|-0.36%|0.59246|-0.46%|1.930|6.628|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7092ff5387)|0.52135|0.52573|0.00077|0.15%|0.52239|-12.21%|0.52225|-12.25%|2.298|8.614|0.000|26.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44341|0.44561|0.00055|0.12%|0.44464|0.00%|0.44470|0.00%|-0.548|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f2b371e747)|0.44989|0.45221|0.00054|0.12%|0.45097|1.43%|0.45092|1.40%|0.111|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/7092ff5387)|0.44962|0.45476|0.00080|0.18%|0.45136|1.51%|0.45126|1.48%|1.519|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7092ff5387)|0.14566|0.14960|0.00096|0.66%|0.14628|-67.10%|0.14602|-67.16%|2.972|8.614|0.000|26.26 MB|
