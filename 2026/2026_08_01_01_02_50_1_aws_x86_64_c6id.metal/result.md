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
| Time          |2026-08-01 01:02:50 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30676982647 ([Artifacts](https://github.com/php/php-src/actions/runs/30676982647/artifacts/8811503195))|
| Changeset  |https://github.com/php/php-src/compare/7b78eb4fcc..949fdc41d9|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40021|0.40111|0.00020|0.05%|0.40056|0.00%|0.40053|0.00%|0.596|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7b78eb4fcc)|0.38967|0.39206|0.00039|0.10%|0.39002|-2.63%|0.38994|-2.64%|3.310|8.614|0.000|25.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/949fdc41d9)|0.39305|0.39558|0.00046|0.12%|0.39376|-1.70%|0.39362|-1.73%|2.305|8.614|0.000|25.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/949fdc41d9)|0.36585|0.36820|0.00046|0.13%|0.36663|-8.47%|0.36654|-8.49%|1.510|8.614|0.000|25.76 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67986|0.69188|0.00163|0.24%|0.68167|0.00%|0.68144|0.00%|5.127|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7b78eb4fcc)|0.67644|0.68017|0.00057|0.08%|0.67710|-0.67%|0.67697|-0.66%|3.398|8.607|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/949fdc41d9)|0.67053|0.67221|0.00040|0.06%|0.67130|-1.52%|0.67127|-1.49%|0.319|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/949fdc41d9)|0.63869|0.64403|0.00094|0.15%|0.63929|-6.22%|0.63899|-6.23%|3.437|8.614|0.000|26.16 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59202|0.59754|0.00111|0.19%|0.59417|0.00%|0.59414|0.00%|0.582|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7b78eb4fcc)|0.58705|0.59086|0.00080|0.14%|0.58837|-0.98%|0.58813|-1.01%|1.676|8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/949fdc41d9)|0.58953|0.59737|0.00128|0.22%|0.59041|-0.63%|0.59004|-0.69%|3.853|8.166|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/949fdc41d9)|0.52164|0.53276|0.00179|0.34%|0.52301|-11.98%|0.52246|-12.07%|3.809|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44327|0.44722|0.00069|0.15%|0.44467|0.00%|0.44462|0.00%|0.928|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7b78eb4fcc)|0.44898|0.45207|0.00048|0.11%|0.44957|1.10%|0.44956|1.11%|2.956|-8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/949fdc41d9)|0.44945|0.45092|0.00033|0.07%|0.45010|1.22%|0.45003|1.22%|0.364|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/949fdc41d9)|0.14413|0.14496|0.00018|0.13%|0.14461|-67.48%|0.14460|-67.48%|-0.274|8.614|0.000|26.24 MB|
