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
| Time          |2026-10-07 01:16:50 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/37556265414 ([Artifacts](https://github.com/php/php-src/actions/runs/37556265414/artifacts/11455872784))|
| Changeset  |https://github.com/php/php-src/compare/9cd641febc..fb6435df56|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39923|0.40060|0.00025|0.06%|0.39954|0.00%|0.39949|0.00%|2.272|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9cd641febc)|0.37883|0.38048|0.00042|0.11%|0.37960|-4.99%|0.37968|-4.96%|0.054|8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/fb6435df56)|0.37942|0.38249|0.00060|0.16%|0.38026|-4.83%|0.38012|-4.85%|1.336|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fb6435df56)|0.35657|0.35903|0.00036|0.10%|0.35702|-10.64%|0.35696|-10.65%|3.627|8.614|0.000|26.23 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68003|0.69826|0.00251|0.37%|0.68215|0.00%|0.68167|0.00%|5.666|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9cd641febc)|0.67168|0.67316|0.00030|0.05%|0.67212|-1.47%|0.67208|-1.41%|1.469|8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/fb6435df56)|0.67383|0.67537|0.00036|0.05%|0.67436|-1.14%|0.67428|-1.08%|1.032|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fb6435df56)|0.64237|0.66192|0.00335|0.52%|0.64431|-5.55%|0.64346|-5.60%|4.062|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59078|0.59569|0.00110|0.19%|0.59259|0.00%|0.59238|0.00%|0.893|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9cd641febc)|0.59391|0.59850|0.00104|0.18%|0.59513|0.43%|0.59491|0.43%|1.587|-7.718|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/fb6435df56)|0.59245|0.59601|0.00072|0.12%|0.59325|0.11%|0.59300|0.11%|2.121|-4.367|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fb6435df56)|0.52025|0.52349|0.00060|0.12%|0.52109|-12.07%|0.52095|-12.06%|2.518|8.614|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44282|0.44683|0.00061|0.14%|0.44467|0.00%|0.44467|0.00%|0.147|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9cd641febc)|0.45002|0.45389|0.00083|0.18%|0.45212|1.68%|0.45213|1.68%|0.040|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/fb6435df56)|0.45124|0.45489|0.00075|0.17%|0.45270|1.81%|0.45265|1.80%|0.343|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fb6435df56)|0.14360|0.14727|0.00049|0.34%|0.14436|-67.53%|0.14431|-67.55%|4.128|8.614|0.000|26.21 MB|
