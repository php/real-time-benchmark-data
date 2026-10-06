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
| Time          |2026-10-06 01:13:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/37398024464 ([Artifacts](https://github.com/php/php-src/actions/runs/37398024464/artifacts/11385540535))|
| Changeset  |https://github.com/php/php-src/compare/d6288f77eb..9cd641febc|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39903|0.40017|0.00029|0.07%|0.39944|0.00%|0.39938|0.00%|0.807|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6288f77eb)|0.37931|0.38102|0.00033|0.09%|0.37980|-4.92%|0.37973|-4.92%|2.048|8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/9cd641febc)|0.37894|0.38081|0.00041|0.11%|0.37983|-4.91%|0.37986|-4.89%|-0.276|8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9cd641febc)|0.35507|0.35748|0.00044|0.12%|0.35562|-10.97%|0.35553|-10.98%|2.443|8.614|0.000|26.12 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68064|0.68375|0.00072|0.10%|0.68188|0.00%|0.68185|0.00%|0.852|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6288f77eb)|0.67615|0.67793|0.00036|0.05%|0.67674|-0.75%|0.67668|-0.76%|1.183|8.614|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/9cd641febc)|0.67271|0.67453|0.00039|0.06%|0.67316|-1.28%|0.67310|-1.28%|2.198|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9cd641febc)|0.64040|0.64274|0.00043|0.07%|0.64122|-5.96%|0.64116|-5.97%|1.273|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59107|0.59404|0.00068|0.11%|0.59213|0.00%|0.59201|0.00%|0.389|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6288f77eb)|0.59505|0.59853|0.00062|0.10%|0.59590|0.64%|0.59582|0.64%|2.223|-8.614|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/9cd641febc)|0.59368|0.59559|0.00049|0.08%|0.59448|0.40%|0.59444|0.41%|0.473|-8.538|0.000|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9cd641febc)|0.52013|0.52331|0.00057|0.11%|0.52106|-12.00%|0.52099|-12.00%|1.318|8.614|0.000|26.22 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44367|0.44604|0.00050|0.11%|0.44485|0.00%|0.44486|0.00%|-0.122|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6288f77eb)|0.45331|0.45578|0.00063|0.14%|0.45439|2.15%|0.45434|2.13%|0.370|-8.614|0.000|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/9cd641febc)|0.45024|0.45409|0.00089|0.20%|0.45213|1.64%|0.45206|1.62%|0.252|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9cd641febc)|0.14386|0.14473|0.00019|0.13%|0.14436|-67.55%|0.14434|-67.55%|-0.335|8.614|0.000|26.24 MB|
