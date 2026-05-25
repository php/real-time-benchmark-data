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
| Time          |2026-05-25 01:26:32 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26378470241 ([Artifacts](https://github.com/php/php-src/actions/runs/26378470241/artifacts/7190538979))|
| Changeset  |https://github.com/php/php-src/compare/e22ba55be1..d8a5aec1cc|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39284|0.39415|0.00023|0.06%|0.39320|0.00%|0.39316|0.00%|1.731|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e22ba55be1)|0.38384|0.38581|0.00042|0.11%|0.38451|-2.21%|0.38437|-2.24%|1.363|8.614|0.000|25.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8a5aec1cc)|0.38567|0.38760|0.00039|0.10%|0.38618|-1.78%|0.38607|-1.80%|1.315|8.614|0.000|25.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8a5aec1cc)|0.35618|0.35955|0.00047|0.13%|0.35672|-9.28%|0.35663|-9.29%|4.485|8.614|0.000|25.77 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67032|0.67304|0.00060|0.09%|0.67131|0.00%|0.67116|0.00%|1.012|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e22ba55be1)|0.66704|0.66993|0.00050|0.07%|0.66785|-0.52%|0.66777|-0.51%|1.795|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8a5aec1cc)|0.67067|0.67365|0.00056|0.08%|0.67117|-0.02%|0.67096|-0.03%|2.561|1.179|0.238|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8a5aec1cc)|0.63343|0.63848|0.00072|0.11%|0.63407|-5.55%|0.63388|-5.55%|4.872|8.614|0.000|26.19 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58641|0.59114|0.00123|0.21%|0.58819|0.00%|0.58811|0.00%|0.630|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e22ba55be1)|0.58312|0.58629|0.00067|0.12%|0.58400|-0.71%|0.58391|-0.71%|1.911|8.614|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8a5aec1cc)|0.58491|0.59199|0.00119|0.20%|0.58593|-0.38%|0.58562|-0.42%|3.316|7.490|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8a5aec1cc)|0.51400|0.51714|0.00080|0.16%|0.51503|-12.44%|0.51480|-12.47%|1.493|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44148|0.44423|0.00054|0.12%|0.44285|0.00%|0.44288|0.00%|-0.334|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e22ba55be1)|0.44868|0.45325|0.00071|0.16%|0.45049|1.72%|0.45049|1.72%|1.077|-8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8a5aec1cc)|0.44918|0.45161|0.00050|0.11%|0.45033|1.69%|0.45031|1.68%|0.131|-8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8a5aec1cc)|0.14342|0.14591|0.00048|0.33%|0.14388|-67.51%|0.14379|-67.53%|3.393|8.614|0.000|26.30 MB|
