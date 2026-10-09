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
| Time          |2026-10-09 01:18:41 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/37869112905 ([Artifacts](https://github.com/php/php-src/actions/runs/37869112905/artifacts/11590347622))|
| Changeset  |https://github.com/php/php-src/compare/60702faf6a..c79284711b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39897|0.40061|0.00026|0.07%|0.39941|0.00%|0.39939|0.00%|2.025|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60702faf6a)|0.37939|0.38115|0.00026|0.07%|0.37983|-4.90%|0.37975|-4.92%|2.809|8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/c79284711b)|0.37977|0.38169|0.00036|0.09%|0.38020|-4.81%|0.38013|-4.82%|1.929|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c79284711b)|0.35680|0.35825|0.00024|0.07%|0.35711|-10.59%|0.35710|-10.59%|2.450|8.614|0.000|26.24 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68009|0.68426|0.00098|0.14%|0.68146|0.00%|0.68128|0.00%|1.029|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60702faf6a)|0.67551|0.67819|0.00047|0.07%|0.67617|-0.78%|0.67607|-0.77%|2.111|8.614|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/c79284711b)|0.67592|0.67983|0.00063|0.09%|0.67677|-0.69%|0.67664|-0.68%|2.681|8.614|0.000|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c79284711b)|0.64502|0.64935|0.00080|0.12%|0.64591|-5.22%|0.64583|-5.20%|2.977|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59093|0.59561|0.00107|0.18%|0.59265|0.00%|0.59251|0.00%|0.531|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60702faf6a)|0.59411|0.59857|0.00077|0.13%|0.59517|0.43%|0.59500|0.42%|2.392|-8.214|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/c79284711b)|0.59348|0.60176|0.00117|0.20%|0.59445|0.30%|0.59430|0.30%|5.317|-7.145|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c79284711b)|0.52017|0.52397|0.00058|0.11%|0.52104|-12.08%|0.52094|-12.08%|2.816|8.614|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44345|0.44627|0.00061|0.14%|0.44460|0.00%|0.44456|0.00%|0.546|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60702faf6a)|0.45293|0.45684|0.00066|0.15%|0.45484|2.30%|0.45476|2.29%|0.416|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/c79284711b)|0.45048|0.45431|0.00084|0.19%|0.45241|1.76%|0.45236|1.75%|-0.017|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c79284711b)|0.14362|0.14514|0.00028|0.19%|0.14434|-67.54%|0.14438|-67.52%|-0.234|8.614|0.000|26.23 MB|
