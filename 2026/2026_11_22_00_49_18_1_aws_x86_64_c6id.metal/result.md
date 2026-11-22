### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-22 00:49:18 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/44968435677 ([Artifacts](https://github.com/php/php-src/actions/runs/44968435677/artifacts/14733113901))|
| Changeset  |https://github.com/php/php-src/compare/95bca157ab..6e4c78a172|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39739|0.39849|0.00020|0.05%|0.39780|0.00%|0.39779|0.00%|1.142|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95bca157ab)|0.37858|0.38003|0.00030|0.08%|0.37907|-4.71%|0.37901|-4.72%|1.526|8.614|0.000|25.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e4c78a172)|0.37934|0.38037|0.00021|0.05%|0.37974|-4.54%|0.37973|-4.54%|0.569|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e4c78a172)|0.35229|0.35306|0.00018|0.05%|0.35267|-11.35%|0.35266|-11.35%|0.331|8.614|0.000|26.24 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67656|0.70672|0.00510|0.75%|0.67856|0.00%|0.67729|0.00%|4.473|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95bca157ab)|0.67870|0.68174|0.00060|0.09%|0.67950|0.14%|0.67934|0.30%|2.163|-7.345|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e4c78a172)|0.67859|0.68432|0.00085|0.12%|0.67944|0.13%|0.67922|0.29%|4.170|-7.338|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e4c78a172)|0.65356|0.66924|0.00305|0.46%|0.65513|-3.45%|0.65409|-3.42%|3.313|8.614|0.000|26.36 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59046|0.59462|0.00089|0.15%|0.59250|0.00%|0.59246|0.00%|0.418|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95bca157ab)|0.59076|0.59329|0.00057|0.10%|0.59137|-0.19%|0.59125|-0.20%|2.402|6.815|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e4c78a172)|0.58978|0.59254|0.00071|0.12%|0.59053|-0.33%|0.59031|-0.36%|1.435|7.704|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e4c78a172)|0.51683|0.51915|0.00049|0.09%|0.51739|-12.68%|0.51732|-12.68%|2.339|8.614|0.000|26.48 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44352|0.44830|0.00074|0.17%|0.44470|0.00%|0.44460|0.00%|2.349|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95bca157ab)|0.45295|0.45581|0.00056|0.12%|0.45398|2.09%|0.45394|2.10%|0.740|-8.614|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e4c78a172)|0.45275|0.45504|0.00055|0.12%|0.45392|2.08%|0.45389|2.09%|0.043|-8.614|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e4c78a172)|0.14498|0.14925|0.00073|0.50%|0.14578|-67.22%|0.14568|-67.23%|3.924|8.614|0.000|26.48 MB|
