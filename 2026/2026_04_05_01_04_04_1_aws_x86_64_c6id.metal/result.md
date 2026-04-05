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
| Time          |2026-04-05 01:04:04 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23991262520 ([Artifacts](https://github.com/php/php-src/actions/runs/23991262520/artifacts/6274444036))|
| Changeset  |https://github.com/php/php-src/compare/b7c855f4c2..4cc691ae46|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39656|0.39881|0.00070|0.18%|0.39737|0.00%|0.39701|0.00%|0.890|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b7c855f4c2)|0.38770|0.38952|0.00035|0.09%|0.38814|-2.32%|0.38806|-2.25%|1.979|8.614|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/4cc691ae46)|0.38771|0.39002|0.00045|0.12%|0.38822|-2.30%|0.38811|-2.24%|2.353|8.614|0.000|24.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4cc691ae46)|0.36178|0.36400|0.00050|0.14%|0.36231|-8.82%|0.36216|-8.78%|1.839|8.614|0.000|25.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67203|0.67417|0.00045|0.07%|0.67267|0.00%|0.67257|0.00%|1.232|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b7c855f4c2)|0.66569|0.66724|0.00039|0.06%|0.66616|-0.97%|0.66601|-0.98%|1.134|8.614|0.000|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/4cc691ae46)|0.66910|0.67273|0.00055|0.08%|0.66975|-0.43%|0.66965|-0.43%|3.475|8.379|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4cc691ae46)|0.63923|0.64836|0.00127|0.20%|0.63988|-4.88%|0.63969|-4.89%|6.392|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58994|0.59446|0.00113|0.19%|0.59157|0.00%|0.59130|0.00%|0.841|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b7c855f4c2)|0.58676|0.58948|0.00055|0.09%|0.58739|-0.71%|0.58725|-0.69%|1.866|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/4cc691ae46)|0.58671|0.59427|0.00127|0.22%|0.58774|-0.65%|0.58736|-0.67%|3.372|8.235|0.000|25.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4cc691ae46)|0.51714|0.52027|0.00078|0.15%|0.51805|-12.43%|0.51780|-12.43%|1.924|8.614|0.000|25.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44195|0.44458|0.00063|0.14%|0.44305|0.00%|0.44296|0.00%|0.572|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b7c855f4c2)|0.44507|0.44908|0.00062|0.14%|0.44615|0.70%|0.44616|0.72%|1.944|-8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/4cc691ae46)|0.44512|0.44758|0.00047|0.11%|0.44611|0.69%|0.44612|0.71%|0.139|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4cc691ae46)|0.14333|0.14743|0.00056|0.39%|0.14384|-67.53%|0.14378|-67.54%|5.432|8.614|0.000|25.32 MB|
