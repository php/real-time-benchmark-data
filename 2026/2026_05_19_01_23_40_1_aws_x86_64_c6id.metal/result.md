### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-19 01:23:40 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26070377197 ([Artifacts](https://github.com/php/php-src/actions/runs/26070377197/artifacts/7073461925))|
| Changeset  |https://github.com/php/php-src/compare/7827754207..d6b7bd0f77|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39279|0.39467|0.00033|0.08%|0.39321|0.00%|0.39315|0.00%|3.316|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7827754207)|0.38506|0.38743|0.00041|0.11%|0.38554|-1.95%|0.38540|-1.97%|2.704|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6b7bd0f77)|0.38521|0.38675|0.00047|0.12%|0.38581|-1.88%|0.38564|-1.91%|0.686|8.614|0.000|25.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6b7bd0f77)|0.35885|0.36247|0.00054|0.15%|0.35998|-8.45%|0.35992|-8.45%|2.278|8.614|0.000|25.21 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67124|0.67485|0.00077|0.12%|0.67216|0.00%|0.67189|0.00%|1.489|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7827754207)|0.66566|0.66772|0.00037|0.05%|0.66630|-0.87%|0.66622|-0.84%|1.396|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6b7bd0f77)|0.66819|0.67199|0.00067|0.10%|0.66891|-0.48%|0.66869|-0.48%|2.522|8.421|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6b7bd0f77)|0.63346|0.64076|0.00099|0.16%|0.63426|-5.64%|0.63414|-5.62%|5.932|8.614|0.000|25.75 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58584|0.59163|0.00113|0.19%|0.58872|0.00%|0.58869|0.00%|0.213|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7827754207)|0.58326|0.58664|0.00056|0.10%|0.58391|-0.82%|0.58377|-0.84%|3.655|8.600|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6b7bd0f77)|0.58429|0.58698|0.00067|0.11%|0.58510|-0.62%|0.58495|-0.64%|1.388|8.559|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6b7bd0f77)|0.51228|0.52280|0.00145|0.28%|0.51358|-12.76%|0.51332|-12.80%|5.416|8.614|0.000|25.77 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44195|0.44725|0.00081|0.18%|0.44296|0.00%|0.44278|0.00%|3.088|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7827754207)|0.44650|0.44988|0.00055|0.12%|0.44725|0.97%|0.44711|0.98%|2.302|-8.414|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6b7bd0f77)|0.44926|0.45156|0.00050|0.11%|0.45027|1.65%|0.45021|1.68%|0.609|-8.614|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6b7bd0f77)|0.14338|0.14592|0.00058|0.40%|0.14393|-67.51%|0.14381|-67.52%|2.788|8.614|0.000|25.77 MB|
