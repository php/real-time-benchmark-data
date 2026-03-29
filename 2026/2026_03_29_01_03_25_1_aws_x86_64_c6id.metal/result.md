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
| Time          |2026-03-29 01:03:25 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23698219147 ([Artifacts](https://github.com/php/php-src/actions/runs/23698219147/artifacts/6162646730))|
| Changeset  |https://github.com/php/php-src/compare/83b8a895a5..c45b2bec75|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39601|0.39895|0.00074|0.19%|0.39664|0.00%|0.39634|0.00%|1.716|0.000|1.000|26.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/83b8a895a5)|0.38923|0.39168|0.00069|0.18%|0.39025|-1.61%|0.39006|-1.58%|0.495|8.614|0.000|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/c45b2bec75)|0.38941|0.39220|0.00041|0.11%|0.39010|-1.65%|0.39002|-1.60%|2.707|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c45b2bec75)|0.36276|0.36517|0.00039|0.11%|0.36316|-8.44%|0.36309|-8.39%|3.445|8.614|0.000|25.38 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66843|0.67003|0.00045|0.07%|0.66903|0.00%|0.66888|0.00%|0.642|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/83b8a895a5)|0.66900|0.67093|0.00039|0.06%|0.66972|0.10%|0.66969|0.12%|1.064|-6.229|0.000|25.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/c45b2bec75)|0.66480|0.66865|0.00070|0.10%|0.66593|-0.46%|0.66572|-0.47%|1.941|8.531|0.000|25.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c45b2bec75)|0.63385|0.63567|0.00038|0.06%|0.63447|-5.17%|0.63439|-5.16%|1.359|8.614|0.000|25.34 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58987|0.59449|0.00097|0.16%|0.59163|0.00%|0.59158|0.00%|0.440|0.000|1.000|26.76 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/83b8a895a5)|0.58666|0.59031|0.00089|0.15%|0.58751|-0.70%|0.58722|-0.74%|2.192|8.517|0.000|25.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/c45b2bec75)|0.58758|0.59204|0.00076|0.13%|0.58858|-0.51%|0.58834|-0.55%|2.448|8.283|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c45b2bec75)|0.51665|0.51970|0.00052|0.10%|0.51743|-12.54%|0.51735|-12.55%|2.932|8.614|0.000|25.31 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44184|0.44463|0.00060|0.13%|0.44289|0.00%|0.44280|0.00%|0.502|0.000|1.000|26.76 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/83b8a895a5)|0.44340|0.44626|0.00057|0.13%|0.44530|0.54%|0.44543|0.59%|-0.910|-8.517|0.000|25.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/c45b2bec75)|0.44335|0.44685|0.00078|0.17%|0.44526|0.54%|0.44518|0.54%|0.041|-8.455|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c45b2bec75)|0.14346|0.14491|0.00027|0.19%|0.14388|-67.51%|0.14386|-67.51%|1.465|8.614|0.000|25.31 MB|
