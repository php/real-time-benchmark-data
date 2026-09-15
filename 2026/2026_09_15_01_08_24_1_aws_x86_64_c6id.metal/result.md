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
| Time          |2026-09-15 01:08:24 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34916035552 ([Artifacts](https://github.com/php/php-src/actions/runs/34916035552/artifacts/10377146615))|
| Changeset  |https://github.com/php/php-src/compare/e783539fe5..100e8f353e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39605|0.39773|0.00024|0.06%|0.39646|0.00%|0.39646|0.00%|3.088|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e783539fe5)|0.37148|0.37259|0.00021|0.06%|0.37181|-6.22%|0.37180|-6.22%|1.285|8.614|0.000|25.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/100e8f353e)|0.37119|0.37327|0.00036|0.10%|0.37166|-6.26%|0.37160|-6.27%|2.126|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67596|0.68017|0.00085|0.13%|0.67746|0.00%|0.67727|0.00%|1.076|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e783539fe5)|0.66882|0.67335|0.00090|0.14%|0.66985|-1.12%|0.66957|-1.14%|1.993|8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/100e8f353e)|0.67011|0.67430|0.00080|0.12%|0.67120|-0.92%|0.67107|-0.91%|2.164|8.614|0.000|26.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58765|0.59098|0.00087|0.15%|0.58899|0.00%|0.58880|0.00%|0.635|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e783539fe5)|0.58651|0.59024|0.00102|0.17%|0.58779|-0.20%|0.58740|-0.24%|0.977|5.429|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/100e8f353e)|0.58497|0.58824|0.00058|0.10%|0.58585|-0.53%|0.58576|-0.52%|2.005|8.531|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44369|0.44612|0.00053|0.12%|0.44467|0.00%|0.44466|0.00%|0.529|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e783539fe5)|0.45121|0.45462|0.00076|0.17%|0.45238|1.73%|0.45223|1.70%|1.381|-8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/100e8f353e)|0.45097|0.45316|0.00049|0.11%|0.45202|1.65%|0.45206|1.66%|-0.273|-8.614|0.000|26.24 MB|
