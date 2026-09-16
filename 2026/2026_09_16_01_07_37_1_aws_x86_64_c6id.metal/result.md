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
| Time          |2026-09-16 01:07:37 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35042813563 ([Artifacts](https://github.com/php/php-src/actions/runs/35042813563/artifacts/10426098270))|
| Changeset  |https://github.com/php/php-src/compare/100e8f353e..38956a3f3e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39907|0.40037|0.00024|0.06%|0.39949|0.00%|0.39947|0.00%|1.144|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/100e8f353e)|0.37453|0.37605|0.00025|0.07%|0.37484|-6.17%|0.37478|-6.18%|2.746|8.614|0.000|25.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/38956a3f3e)|0.37428|0.37549|0.00023|0.06%|0.37475|-6.19%|0.37472|-6.20%|0.642|8.614|0.000|25.83 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68033|0.68420|0.00084|0.12%|0.68174|0.00%|0.68151|0.00%|0.883|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/100e8f353e)|0.67485|0.67703|0.00043|0.06%|0.67542|-0.93%|0.67534|-0.91%|1.716|8.614|0.000|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/38956a3f3e)|0.67730|0.68041|0.00061|0.09%|0.67825|-0.51%|0.67813|-0.50%|0.993|8.607|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59110|0.59562|0.00086|0.14%|0.59290|0.00%|0.59278|0.00%|0.409|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/100e8f353e)|0.58895|0.59199|0.00063|0.11%|0.58995|-0.50%|0.58979|-0.50%|1.218|8.538|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/38956a3f3e)|0.58903|0.59297|0.00073|0.12%|0.59008|-0.48%|0.58997|-0.47%|1.412|8.386|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44329|0.44615|0.00064|0.14%|0.44478|0.00%|0.44477|0.00%|0.066|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/100e8f353e)|0.45123|0.45332|0.00041|0.09%|0.45210|1.64%|0.45210|1.65%|0.453|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/38956a3f3e)|0.45122|0.45388|0.00060|0.13%|0.45226|1.68%|0.45209|1.65%|0.982|-8.614|0.000|26.23 MB|
