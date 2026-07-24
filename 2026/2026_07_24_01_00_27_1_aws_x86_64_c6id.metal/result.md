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
| Time          |2026-07-24 01:00:27 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30057738920 ([Artifacts](https://github.com/php/php-src/actions/runs/30057738920/artifacts/8584220209))|
| Changeset  |https://github.com/php/php-src/compare/28dab5fafb..1f4a88c5c3|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39831|0.40084|0.00077|0.19%|0.39907|0.00%|0.39873|0.00%|1.053|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/28dab5fafb)|0.39136|0.39251|0.00022|0.06%|0.39168|-1.85%|0.39163|-1.78%|1.459|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/1f4a88c5c3)|0.39150|0.39400|0.00045|0.11%|0.39214|-1.74%|0.39201|-1.69%|2.081|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1f4a88c5c3)|0.36327|0.36645|0.00051|0.14%|0.36376|-8.85%|0.36364|-8.80%|3.564|8.614|0.000|25.74 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67721|0.68170|0.00081|0.12%|0.67816|0.00%|0.67788|0.00%|2.253|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/28dab5fafb)|0.67425|0.67673|0.00050|0.07%|0.67493|-0.48%|0.67478|-0.46%|1.549|8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/1f4a88c5c3)|0.67369|0.67753|0.00063|0.09%|0.67441|-0.55%|0.67435|-0.52%|2.542|8.579|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1f4a88c5c3)|0.64501|0.65489|0.00132|0.20%|0.64619|-4.71%|0.64597|-4.71%|6.124|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59152|0.59628|0.00109|0.18%|0.59391|0.00%|0.59395|0.00%|0.229|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/28dab5fafb)|0.58837|0.59149|0.00058|0.10%|0.58907|-0.81%|0.58899|-0.84%|1.778|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/1f4a88c5c3)|0.58923|0.59432|0.00101|0.17%|0.59049|-0.58%|0.59033|-0.61%|1.447|8.242|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1f4a88c5c3)|0.51876|0.52290|0.00080|0.15%|0.51980|-12.48%|0.51967|-12.51%|1.908|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44354|0.44514|0.00041|0.09%|0.44444|0.00%|0.44453|0.00%|-0.375|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/28dab5fafb)|0.44812|0.44963|0.00036|0.08%|0.44902|1.03%|0.44903|1.01%|-0.460|-8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/1f4a88c5c3)|0.44828|0.45059|0.00038|0.08%|0.44913|1.06%|0.44914|1.04%|1.030|-8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1f4a88c5c3)|0.14424|0.14503|0.00017|0.12%|0.14463|-67.46%|0.14464|-67.46%|-0.015|8.614|0.000|26.28 MB|
