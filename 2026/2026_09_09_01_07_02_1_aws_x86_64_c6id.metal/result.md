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
| Time          |2026-09-09 01:07:02 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34297836323 ([Artifacts](https://github.com/php/php-src/actions/runs/34297836323/artifacts/10084512637))|
| Changeset  |https://github.com/php/php-src/compare/1364de0472..82a15338e2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39554|0.39712|0.00026|0.07%|0.39597|0.00%|0.39592|0.00%|2.236|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1364de0472)|0.37009|0.37131|0.00023|0.06%|0.37057|-6.41%|0.37055|-6.41%|0.578|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/82a15338e2)|0.36979|0.37215|0.00040|0.11%|0.37013|-6.53%|0.37004|-6.54%|3.440|8.614|0.000|25.86 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67517|0.67892|0.00086|0.13%|0.67673|0.00%|0.67660|0.00%|0.365|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1364de0472)|0.66989|0.67422|0.00081|0.12%|0.67096|-0.85%|0.67090|-0.84%|1.891|8.614|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/82a15338e2)|0.66357|0.66596|0.00045|0.07%|0.66422|-1.85%|0.66411|-1.85%|1.382|8.614|0.000|26.18 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58749|0.59175|0.00082|0.14%|0.58903|0.00%|0.58891|0.00%|1.012|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1364de0472)|0.58747|0.59156|0.00078|0.13%|0.58886|-0.03%|0.58869|-0.04%|1.907|1.599|0.110|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/82a15338e2)|0.58753|0.59163|0.00102|0.17%|0.58899|-0.01%|0.58872|-0.03%|1.291|1.027|0.304|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44364|0.45249|0.00120|0.27%|0.44478|0.00%|0.44469|0.00%|5.542|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1364de0472)|0.45090|0.45359|0.00060|0.13%|0.45197|1.62%|0.45192|1.62%|0.623|-8.331|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/82a15338e2)|0.45082|0.45270|0.00046|0.10%|0.45167|1.55%|0.45162|1.56%|0.371|-8.290|0.000|26.24 MB|
