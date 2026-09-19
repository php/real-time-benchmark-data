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
| Time          |2026-09-19 01:05:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35411508506 ([Artifacts](https://github.com/php/php-src/actions/runs/35411508506/artifacts/10574761208))|
| Changeset  |https://github.com/php/php-src/compare/703b5bb37a..cc781b9c65|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40046|0.40206|0.00031|0.08%|0.40096|0.00%|0.40090|0.00%|1.470|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/703b5bb37a)|0.37580|0.37742|0.00031|0.08%|0.37615|-6.19%|0.37608|-6.19%|2.012|8.614|0.000|25.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/cc781b9c65)|0.37614|0.37766|0.00035|0.09%|0.37651|-6.10%|0.37644|-6.10%|1.834|8.614|0.000|26.16 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68209|0.68598|0.00082|0.12%|0.68356|0.00%|0.68345|0.00%|0.727|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/703b5bb37a)|0.67083|0.67306|0.00049|0.07%|0.67150|-1.76%|0.67148|-1.75%|0.866|8.614|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/cc781b9c65)|0.67858|0.68209|0.00068|0.10%|0.67963|-0.57%|0.67955|-0.57%|1.617|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59237|0.59645|0.00089|0.15%|0.59399|0.00%|0.59389|0.00%|0.317|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/703b5bb37a)|0.59118|0.59846|0.00110|0.19%|0.59209|-0.32%|0.59176|-0.36%|4.282|7.725|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/cc781b9c65)|0.58938|0.59343|0.00084|0.14%|0.59069|-0.56%|0.59059|-0.56%|1.425|8.424|0.000|26.17 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44341|0.45231|0.00115|0.26%|0.44495|0.00%|0.44475|0.00%|5.514|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/703b5bb37a)|0.45146|0.45387|0.00052|0.11%|0.45266|1.73%|0.45255|1.75%|0.478|-8.552|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/cc781b9c65)|0.45088|0.45413|0.00067|0.15%|0.45242|1.68%|0.45243|1.72%|0.146|-8.455|0.000|26.17 MB|
