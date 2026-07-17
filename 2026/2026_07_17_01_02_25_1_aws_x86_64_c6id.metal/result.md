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
| Time          |2026-07-17 01:02:25 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29546353245 ([Artifacts](https://github.com/php/php-src/actions/runs/29546353245/artifacts/8394910447))|
| Changeset  |https://github.com/php/php-src/compare/6441f89857..51300b7f59|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39820|0.39974|0.00025|0.06%|0.39867|0.00%|0.39863|0.00%|1.820|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6441f89857)|0.38894|0.39109|0.00037|0.10%|0.38949|-2.30%|0.38941|-2.31%|2.169|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/51300b7f59)|0.39073|0.39410|0.00074|0.19%|0.39132|-1.84%|0.39109|-1.89%|2.874|8.614|0.000|25.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51300b7f59)|0.36401|0.36762|0.00070|0.19%|0.36508|-8.43%|0.36487|-8.47%|2.006|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67808|0.67970|0.00042|0.06%|0.67870|0.00%|0.67862|0.00%|0.685|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6441f89857)|0.67052|0.67270|0.00050|0.07%|0.67119|-1.11%|0.67109|-1.11%|1.364|8.614|0.000|25.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/51300b7f59)|0.67048|0.67262|0.00041|0.06%|0.67127|-1.09%|0.67128|-1.08%|0.693|8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51300b7f59)|0.63958|0.64691|0.00102|0.16%|0.64050|-5.63%|0.64023|-5.66%|5.320|8.614|0.000|26.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59175|0.59700|0.00100|0.17%|0.59379|0.00%|0.59363|0.00%|0.830|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6441f89857)|0.58670|0.59817|0.00181|0.31%|0.58875|-0.85%|0.58844|-0.87%|3.335|8.221|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/51300b7f59)|0.58587|0.59438|0.00144|0.24%|0.58694|-1.15%|0.58653|-1.20%|3.421|8.345|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51300b7f59)|0.51750|0.52344|0.00120|0.23%|0.51845|-12.69%|0.51810|-12.72%|2.738|8.614|0.000|26.27 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44322|0.44854|0.00084|0.19%|0.44468|0.00%|0.44458|0.00%|2.017|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6441f89857)|0.44992|0.45286|0.00066|0.15%|0.45111|1.45%|0.45118|1.48%|0.190|-8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/51300b7f59)|0.44946|0.45195|0.00055|0.12%|0.45074|1.36%|0.45081|1.40%|-0.132|-8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51300b7f59)|0.14426|0.14532|0.00022|0.15%|0.14458|-67.49%|0.14451|-67.49%|0.865|8.614|0.000|26.27 MB|
