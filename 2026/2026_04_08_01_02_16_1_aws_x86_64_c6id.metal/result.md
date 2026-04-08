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
| Time          |2026-04-08 01:02:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24112029571 ([Artifacts](https://github.com/php/php-src/actions/runs/24112029571/artifacts/6318906956))|
| Changeset  |https://github.com/php/php-src/compare/4cc691ae46..961355c13d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39684|0.39865|0.00025|0.06%|0.39734|0.00%|0.39731|0.00%|2.849|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4cc691ae46)|0.38808|0.38941|0.00022|0.06%|0.38850|-2.22%|0.38852|-2.21%|1.225|8.614|0.000|24.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/961355c13d)|0.39033|0.39171|0.00033|0.09%|0.39083|-1.64%|0.39075|-1.65%|1.200|8.614|0.000|25.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/961355c13d)|0.36493|0.36685|0.00042|0.12%|0.36553|-8.00%|0.36544|-8.02%|1.308|8.614|0.000|25.23 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67253|0.67453|0.00041|0.06%|0.67311|0.00%|0.67301|0.00%|1.442|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4cc691ae46)|0.66990|0.67167|0.00045|0.07%|0.67063|-0.37%|0.67054|-0.37%|0.795|8.614|0.000|25.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/961355c13d)|0.67774|0.68118|0.00084|0.12%|0.67874|0.84%|0.67853|0.82%|1.373|-8.614|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/961355c13d)|0.64549|0.65209|0.00102|0.16%|0.64640|-3.97%|0.64616|-3.99%|3.965|8.614|0.000|25.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58989|0.59377|0.00100|0.17%|0.59155|0.00%|0.59148|0.00%|0.347|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4cc691ae46)|0.58653|0.58982|0.00057|0.10%|0.58751|-0.68%|0.58735|-0.70%|2.261|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/961355c13d)|0.58848|0.59209|0.00083|0.14%|0.58939|-0.37%|0.58903|-0.41%|1.682|7.642|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/961355c13d)|0.51838|0.52191|0.00075|0.15%|0.51938|-12.20%|0.51920|-12.22%|2.334|8.614|0.000|25.31 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44229|0.45095|0.00120|0.27%|0.44324|0.00%|0.44303|0.00%|5.543|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4cc691ae46)|0.44507|0.44723|0.00054|0.12%|0.44603|0.63%|0.44597|0.66%|0.206|-8.269|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/961355c13d)|0.44556|0.44734|0.00048|0.11%|0.44642|0.72%|0.44647|0.78%|-0.050|-8.269|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/961355c13d)|0.14350|0.14480|0.00026|0.18%|0.14389|-67.54%|0.14388|-67.52%|1.140|8.614|0.000|25.31 MB|
