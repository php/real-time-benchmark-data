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
| Time          |2026-10-13 01:20:03 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/38331588603 ([Artifacts](https://github.com/php/php-src/actions/runs/38331588603/artifacts/11784008147))|
| Changeset  |https://github.com/php/php-src/compare/4a41768eec..8db886e419|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39925|0.40062|0.00023|0.06%|0.39962|0.00%|0.39957|0.00%|1.991|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a41768eec)|0.38008|0.38143|0.00031|0.08%|0.38050|-4.78%|0.38044|-4.79%|1.097|8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/8db886e419)|0.37724|0.38007|0.00045|0.12%|0.37775|-5.47%|0.37761|-5.50%|3.113|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8db886e419)|0.35495|0.35602|0.00024|0.07%|0.35538|-11.07%|0.35533|-11.07%|0.529|8.614|0.000|26.18 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68015|0.68552|0.00095|0.14%|0.68184|0.00%|0.68178|0.00%|1.491|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a41768eec)|0.67460|0.67814|0.00065|0.10%|0.67519|-0.98%|0.67502|-0.99%|2.785|8.614|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/8db886e419)|0.67995|0.68271|0.00064|0.09%|0.68086|-0.14%|0.68067|-0.16%|1.413|5.749|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8db886e419)|0.64725|0.66967|0.00338|0.52%|0.64876|-4.85%|0.64795|-4.96%|5.322|8.614|0.000|26.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59058|0.59534|0.00094|0.16%|0.59245|0.00%|0.59245|0.00%|0.648|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a41768eec)|0.59050|0.59887|0.00121|0.20%|0.59149|-0.16%|0.59134|-0.19%|5.060|6.201|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/8db886e419)|0.59155|0.59884|0.00116|0.20%|0.59242|-0.01%|0.59211|-0.06%|3.897|0.986|0.324|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8db886e419)|0.52004|0.52403|0.00077|0.15%|0.52083|-12.09%|0.52069|-12.11%|2.648|8.614|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44358|0.44913|0.00078|0.18%|0.44473|0.00%|0.44465|0.00%|3.619|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a41768eec)|0.45126|0.45296|0.00035|0.08%|0.45213|1.66%|0.45211|1.68%|-0.059|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/8db886e419)|0.45209|0.45453|0.00046|0.10%|0.45362|2.00%|0.45362|2.02%|-0.775|-8.614|0.000|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8db886e419)|0.14348|0.14468|0.00024|0.17%|0.14421|-67.57%|0.14424|-67.56%|-0.451|8.614|0.000|26.23 MB|
