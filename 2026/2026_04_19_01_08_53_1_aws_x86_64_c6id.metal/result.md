### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-04-19 01:08:53 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24617850079 ([Artifacts](https://github.com/php/php-src/actions/runs/24617850079/artifacts/6514942956))|
| Changeset  |https://github.com/php/php-src/compare/60314974f9..b40cae2b1f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39657|0.39882|0.00075|0.19%|0.39735|0.00%|0.39706|0.00%|0.920|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60314974f9)|0.38849|0.38984|0.00031|0.08%|0.38891|-2.12%|0.38885|-2.07%|1.349|8.614|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/b40cae2b1f)|0.38830|0.39205|0.00060|0.16%|0.38887|-2.13%|0.38867|-2.11%|3.370|8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b40cae2b1f)|0.36175|0.36368|0.00037|0.10%|0.36228|-8.83%|0.36221|-8.78%|2.172|8.614|0.000|25.39 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66994|0.67206|0.00044|0.07%|0.67072|0.00%|0.67057|0.00%|1.415|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60314974f9)|0.66978|0.67282|0.00054|0.08%|0.67056|-0.02%|0.67043|-0.02%|2.020|2.647|0.008|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/b40cae2b1f)|0.66428|0.66657|0.00039|0.06%|0.66486|-0.87%|0.66477|-0.87%|2.195|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b40cae2b1f)|0.63210|0.63466|0.00053|0.08%|0.63282|-5.65%|0.63268|-5.65%|1.559|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58940|0.59440|0.00101|0.17%|0.59142|0.00%|0.59129|0.00%|0.518|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60314974f9)|0.58807|0.59119|0.00055|0.09%|0.58877|-0.45%|0.58875|-0.43%|1.856|8.428|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/b40cae2b1f)|0.58729|0.59075|0.00060|0.10%|0.58814|-0.55%|0.58798|-0.56%|2.668|8.504|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b40cae2b1f)|0.51778|0.52110|0.00081|0.16%|0.51874|-12.29%|0.51850|-12.31%|1.882|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44151|0.44455|0.00069|0.16%|0.44298|0.00%|0.44292|0.00%|0.046|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60314974f9)|0.44486|0.44781|0.00057|0.13%|0.44650|0.79%|0.44643|0.79%|0.052|-8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/b40cae2b1f)|0.44556|0.45035|0.00070|0.16%|0.44664|0.83%|0.44662|0.83%|2.865|-8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b40cae2b1f)|0.14319|0.14387|0.00016|0.11%|0.14358|-67.59%|0.14361|-67.58%|-0.476|8.614|0.000|25.39 MB|
