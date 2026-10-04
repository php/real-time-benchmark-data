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
| Time          |2026-10-04 01:40:37 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/37168711157 ([Artifacts](https://github.com/php/php-src/actions/runs/37168711157/artifacts/11290324572))|
| Changeset  |https://github.com/php/php-src/compare/459f8cb22b..63b0af4a5c|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39635|0.39743|0.00020|0.05%|0.39662|0.00%|0.39659|0.00%|1.849|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459f8cb22b)|0.37656|0.37776|0.00029|0.08%|0.37697|-4.96%|0.37690|-4.96%|1.491|8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/63b0af4a5c)|0.37714|0.37856|0.00024|0.06%|0.37761|-4.79%|0.37757|-4.79%|1.057|8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63b0af4a5c)|0.35225|0.35322|0.00022|0.06%|0.35274|-11.06%|0.35272|-11.06%|0.189|8.614|0.000|26.19 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67717|0.68473|0.00117|0.17%|0.67882|0.00%|0.67872|0.00%|2.759|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459f8cb22b)|0.67170|0.67635|0.00091|0.14%|0.67257|-0.92%|0.67223|-0.96%|2.567|8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/63b0af4a5c)|0.67250|0.67918|0.00104|0.15%|0.67317|-0.83%|0.67290|-0.86%|4.472|8.366|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63b0af4a5c)|0.63958|0.64409|0.00071|0.11%|0.64088|-5.59%|0.64082|-5.58%|1.812|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58796|0.59178|0.00082|0.14%|0.58935|0.00%|0.58939|0.00%|0.456|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459f8cb22b)|0.59175|0.59566|0.00062|0.10%|0.59256|0.55%|0.59245|0.52%|2.831|-8.607|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/63b0af4a5c)|0.59199|0.59516|0.00063|0.11%|0.59282|0.59%|0.59269|0.56%|1.629|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63b0af4a5c)|0.51636|0.52052|0.00087|0.17%|0.51753|-12.19%|0.51729|-12.23%|1.828|8.614|0.000|26.66 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44336|0.44579|0.00061|0.14%|0.44463|0.00%|0.44467|0.00%|-0.087|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/459f8cb22b)|0.45007|0.45630|0.00096|0.21%|0.45257|1.78%|0.45250|1.76%|0.981|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/63b0af4a5c)|0.45023|0.45410|0.00071|0.16%|0.45190|1.63%|0.45175|1.59%|0.603|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63b0af4a5c)|0.14354|0.14458|0.00025|0.17%|0.14413|-67.58%|0.14416|-67.58%|-0.386|8.614|0.000|26.66 MB|
