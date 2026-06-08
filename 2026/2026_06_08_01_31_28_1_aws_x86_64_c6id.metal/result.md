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
| Time          |2026-06-08 01:31:28 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27111062346 ([Artifacts](https://github.com/php/php-src/actions/runs/27111062346/artifacts/7470475753))|
| Changeset  |https://github.com/php/php-src/compare/95b5b48799..a7223e73a8|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39821|0.39911|0.00019|0.05%|0.39868|0.00%|0.39863|0.00%|0.493|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95b5b48799)|0.38717|0.38863|0.00029|0.08%|0.38763|-2.77%|0.38758|-2.77%|1.245|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7223e73a8)|0.38672|0.38848|0.00039|0.10%|0.38720|-2.88%|0.38710|-2.89%|1.585|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7223e73a8)|0.36257|0.36522|0.00059|0.16%|0.36337|-8.86%|0.36320|-8.89%|2.023|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67754|0.68143|0.00067|0.10%|0.67825|0.00%|0.67808|0.00%|2.516|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95b5b48799)|0.67112|0.67434|0.00073|0.11%|0.67270|-0.82%|0.67257|-0.81%|0.325|8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7223e73a8)|0.67026|0.67428|0.00082|0.12%|0.67124|-1.03%|0.67101|-1.04%|1.941|8.614|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7223e73a8)|0.63990|0.65754|0.00325|0.51%|0.64150|-5.42%|0.64070|-5.51%|4.197|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59195|0.59694|0.00118|0.20%|0.59391|0.00%|0.59366|0.00%|0.824|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95b5b48799)|0.58880|0.59325|0.00087|0.15%|0.58981|-0.69%|0.58956|-0.69%|2.364|8.435|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7223e73a8)|0.58890|0.59271|0.00083|0.14%|0.58968|-0.71%|0.58943|-0.71%|2.711|8.538|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7223e73a8)|0.52051|0.53189|0.00162|0.31%|0.52153|-12.19%|0.52125|-12.20%|5.614|8.614|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44291|0.45136|0.00130|0.29%|0.44475|0.00%|0.44464|0.00%|3.392|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95b5b48799)|0.45003|0.45249|0.00061|0.14%|0.45138|1.49%|0.45130|1.50%|-0.026|-8.435|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7223e73a8)|0.45001|0.45309|0.00064|0.14%|0.45143|1.50%|0.45147|1.54%|0.101|-8.462|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7223e73a8)|0.14547|0.14938|0.00102|0.70%|0.14627|-67.11%|0.14601|-67.16%|2.556|8.614|0.000|26.19 MB|
