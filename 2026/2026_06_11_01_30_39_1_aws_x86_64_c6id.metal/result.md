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
| Time          |2026-06-11 01:30:39 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27317702455 ([Artifacts](https://github.com/php/php-src/actions/runs/27317702455/artifacts/7553291826))|
| Changeset  |https://github.com/php/php-src/compare/a7f40d12a2..0e973e3792|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39459|0.39651|0.00031|0.08%|0.39498|0.00%|0.39491|0.00%|3.052|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7f40d12a2)|0.38293|0.38405|0.00023|0.06%|0.38322|-2.98%|0.38322|-2.96%|1.307|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e973e3792)|0.38257|0.38604|0.00053|0.14%|0.38313|-3.00%|0.38299|-3.02%|3.944|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e973e3792)|0.35862|0.36105|0.00050|0.14%|0.35925|-9.05%|0.35916|-9.05%|2.396|8.614|0.000|25.76 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67156|0.67548|0.00068|0.10%|0.67228|0.00%|0.67206|0.00%|2.407|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7f40d12a2)|0.66428|0.66697|0.00060|0.09%|0.66527|-1.04%|0.66511|-1.03%|1.187|8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e973e3792)|0.66443|0.66744|0.00060|0.09%|0.66535|-1.03%|0.66521|-1.02%|1.081|8.614|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e973e3792)|0.63447|0.65962|0.00346|0.54%|0.63585|-5.42%|0.63530|-5.47%|6.908|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58853|0.59257|0.00103|0.18%|0.59043|0.00%|0.59043|0.00%|0.154|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7f40d12a2)|0.58504|0.58910|0.00082|0.14%|0.58590|-0.77%|0.58570|-0.80%|2.420|8.559|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e973e3792)|0.58507|0.58946|0.00090|0.15%|0.58584|-0.78%|0.58558|-0.82%|2.847|8.497|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e973e3792)|0.51590|0.51943|0.00093|0.18%|0.51680|-12.47%|0.51649|-12.52%|1.939|8.614|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44305|0.44545|0.00055|0.12%|0.44442|0.00%|0.44439|0.00%|-0.337|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7f40d12a2)|0.45019|0.45401|0.00067|0.15%|0.45125|1.54%|0.45118|1.53%|1.518|-8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e973e3792)|0.44963|0.45304|0.00069|0.15%|0.45125|1.54%|0.45130|1.55%|-0.217|-8.614|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e973e3792)|0.14524|0.14931|0.00100|0.68%|0.14616|-67.11%|0.14590|-67.17%|2.587|8.614|0.000|26.19 MB|
