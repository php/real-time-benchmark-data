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
| Time          |2026-08-03 01:04:07 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30775930014 ([Artifacts](https://github.com/php/php-src/actions/runs/30775930014/artifacts/8842695429))|
| Changeset  |https://github.com/php/php-src/compare/b74e0f749d..bbf82d7a84|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40008|0.40079|0.00017|0.04%|0.40047|0.00%|0.40046|0.00%|-0.022|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b74e0f749d)|0.39145|0.39319|0.00034|0.09%|0.39186|-2.15%|0.39178|-2.17%|1.654|8.614|0.000|25.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/bbf82d7a84)|0.38976|0.39176|0.00046|0.12%|0.39018|-2.57%|0.39005|-2.60%|2.186|8.614|0.000|25.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bbf82d7a84)|0.36124|0.36389|0.00047|0.13%|0.36195|-9.62%|0.36181|-9.65%|1.901|8.614|0.000|26.22 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67991|0.68600|0.00128|0.19%|0.68127|0.00%|0.68090|0.00%|1.986|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b74e0f749d)|0.66826|0.66995|0.00044|0.07%|0.66882|-1.83%|0.66868|-1.79%|1.397|8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/bbf82d7a84)|0.67461|0.67798|0.00061|0.09%|0.67552|-0.84%|0.67543|-0.80%|2.518|8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bbf82d7a84)|0.64417|0.66780|0.00326|0.50%|0.64569|-5.22%|0.64513|-5.25%|6.640|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59249|0.59686|0.00104|0.17%|0.59437|0.00%|0.59434|0.00%|0.519|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b74e0f749d)|0.58953|0.59741|0.00137|0.23%|0.59112|-0.55%|0.59075|-0.60%|2.585|7.869|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/bbf82d7a84)|0.58881|0.59240|0.00068|0.12%|0.58986|-0.76%|0.58970|-0.78%|1.733|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bbf82d7a84)|0.51933|0.52255|0.00071|0.14%|0.52030|-12.46%|0.52011|-12.49%|1.443|8.614|0.000|26.27 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44342|0.45234|0.00126|0.28%|0.44494|0.00%|0.44478|0.00%|4.625|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b74e0f749d)|0.44930|0.45035|0.00023|0.05%|0.44985|1.10%|0.44988|1.15%|-0.267|-8.269|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/bbf82d7a84)|0.44833|0.45189|0.00053|0.12%|0.44916|0.95%|0.44910|0.97%|2.887|-8.269|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bbf82d7a84)|0.14410|0.14524|0.00021|0.15%|0.14464|-67.49%|0.14464|-67.48%|0.055|8.614|0.000|26.27 MB|
