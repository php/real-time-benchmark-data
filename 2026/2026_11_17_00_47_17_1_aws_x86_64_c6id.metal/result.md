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
| Time          |2026-11-17 00:47:17 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/43990392911 ([Artifacts](https://github.com/php/php-src/actions/runs/43990392911/artifacts/14290250824))|
| Changeset  |https://github.com/php/php-src/compare/90628d5ab3..4bc158b509|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39743|0.39966|0.00072|0.18%|0.39818|0.00%|0.39783|0.00%|1.133|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90628d5ab3)|0.37908|0.38022|0.00023|0.06%|0.37953|-4.68%|0.37948|-4.61%|0.889|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/4bc158b509)|0.38128|0.38353|0.00048|0.13%|0.38182|-4.11%|0.38168|-4.06%|1.853|8.614|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4bc158b509)|0.35387|0.35586|0.00033|0.09%|0.35424|-11.03%|0.35420|-10.97%|3.047|8.614|0.000|26.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67676|0.68741|0.00155|0.23%|0.67782|0.00%|0.67746|0.00%|5.150|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90628d5ab3)|0.67859|0.68461|0.00093|0.14%|0.67940|0.23%|0.67915|0.25%|4.193|-7.931|0.000|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/4bc158b509)|0.68007|0.68545|0.00076|0.11%|0.68078|0.44%|0.68065|0.47%|4.948|-8.138|0.000|26.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4bc158b509)|0.65990|0.66765|0.00104|0.16%|0.66070|-2.53%|0.66055|-2.50%|6.318|8.614|0.000|26.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59097|0.59491|0.00079|0.13%|0.59240|0.00%|0.59240|0.00%|0.610|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90628d5ab3)|0.58853|0.59107|0.00057|0.10%|0.58917|-0.54%|0.58903|-0.57%|2.239|8.572|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/4bc158b509)|0.58984|0.59229|0.00057|0.10%|0.59059|-0.31%|0.59043|-0.33%|1.200|8.076|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4bc158b509)|0.51554|0.51678|0.00029|0.06%|0.51614|-12.87%|0.51607|-12.89%|0.411|8.614|0.000|26.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44365|0.44734|0.00066|0.15%|0.44477|0.00%|0.44465|0.00%|1.299|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90628d5ab3)|0.45282|0.45555|0.00055|0.12%|0.45398|2.07%|0.45399|2.10%|0.313|-8.614|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/4bc158b509)|0.45285|0.45574|0.00065|0.14%|0.45412|2.10%|0.45408|2.12%|0.236|-8.614|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4bc158b509)|0.14499|0.14897|0.00053|0.36%|0.14571|-67.24%|0.14567|-67.24%|4.793|8.614|0.000|26.39 MB|
