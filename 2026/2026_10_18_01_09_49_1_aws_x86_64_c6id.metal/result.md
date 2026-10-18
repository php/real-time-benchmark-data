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
| Time          |2026-10-18 01:09:49 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/39085438801 ([Artifacts](https://github.com/php/php-src/actions/runs/39085438801/artifacts/12121162555))|
| Changeset  |https://github.com/php/php-src/compare/070ce2f9d7..17b6575a3d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39600|0.39736|0.00025|0.06%|0.39650|0.00%|0.39648|0.00%|1.439|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/070ce2f9d7)|0.37298|0.37391|0.00021|0.06%|0.37332|-5.85%|0.37326|-5.86%|0.882|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/17b6575a3d)|0.37289|0.37549|0.00050|0.13%|0.37339|-5.83%|0.37324|-5.86%|2.874|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17b6575a3d)|0.34958|0.35058|0.00018|0.05%|0.35002|-11.72%|0.35002|-11.72%|0.430|8.614|0.000|26.19 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67557|0.67904|0.00077|0.11%|0.67689|0.00%|0.67673|0.00%|0.786|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/070ce2f9d7)|0.66525|0.66923|0.00063|0.09%|0.66591|-1.62%|0.66576|-1.62%|3.640|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/17b6575a3d)|0.66517|0.66807|0.00057|0.09%|0.66586|-1.63%|0.66572|-1.63%|2.312|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17b6575a3d)|0.63353|0.63485|0.00028|0.04%|0.63417|-6.31%|0.63413|-6.30%|0.303|8.614|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58766|0.59267|0.00089|0.15%|0.58946|0.00%|0.58950|0.00%|0.982|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/070ce2f9d7)|0.58758|0.59070|0.00077|0.13%|0.58848|-0.17%|0.58831|-0.20%|1.338|5.556|0.000|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/17b6575a3d)|0.58735|0.59089|0.00078|0.13%|0.58811|-0.23%|0.58787|-0.28%|2.136|6.835|0.000|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17b6575a3d)|0.51471|0.51785|0.00050|0.10%|0.51543|-12.56%|0.51535|-12.58%|2.356|8.614|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44352|0.44625|0.00055|0.12%|0.44470|0.00%|0.44469|0.00%|0.187|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/070ce2f9d7)|0.45046|0.45266|0.00048|0.11%|0.45184|1.61%|0.45182|1.60%|-0.486|-8.614|0.000|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/17b6575a3d)|0.45074|0.45326|0.00051|0.11%|0.45201|1.64%|0.45197|1.64%|0.242|-8.614|0.000|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17b6575a3d)|0.14337|0.14460|0.00028|0.19%|0.14412|-67.59%|0.14417|-67.58%|-1.011|8.614|0.000|26.23 MB|
