### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-03-20 00:54:45 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23324266399 ([Artifacts](https://github.com/php/php-src/actions/runs/23324266399/artifacts/6018541670))|
| Changeset  |https://github.com/php/php-src/compare/e6db18b74c..38cbbee4aa|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39459|0.39647|0.00035|0.09%|0.39497|0.00%|0.39489|0.00%|2.413|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6db18b74c)|0.38818|0.39032|0.00037|0.10%|0.38862|-1.61%|0.38853|-1.61%|2.349|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/38cbbee4aa)|0.38809|0.38933|0.00028|0.07%|0.38853|-1.63%|0.38848|-1.62%|1.089|8.614|0.000|25.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/38cbbee4aa)|0.36063|0.36221|0.00031|0.08%|0.36109|-8.58%|0.36108|-8.56%|1.056|8.614|0.000|25.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66837|0.67058|0.00052|0.08%|0.66904|0.00%|0.66889|0.00%|1.416|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6db18b74c)|0.66499|0.66634|0.00034|0.05%|0.66558|-0.52%|0.66551|-0.50%|0.448|8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/38cbbee4aa)|0.66358|0.66555|0.00033|0.05%|0.66430|-0.71%|0.66426|-0.69%|1.118|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/38cbbee4aa)|0.63286|0.63920|0.00107|0.17%|0.63360|-5.30%|0.63328|-5.32%|3.852|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58761|0.59356|0.00130|0.22%|0.58975|0.00%|0.58954|0.00%|1.068|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6db18b74c)|0.58495|0.58888|0.00068|0.12%|0.58568|-0.69%|0.58557|-0.67%|3.658|8.469|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/38cbbee4aa)|0.58522|0.58824|0.00063|0.11%|0.58582|-0.67%|0.58565|-0.66%|2.614|8.579|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/38cbbee4aa)|0.51461|0.52490|0.00147|0.28%|0.51526|-12.63%|0.51499|-12.65%|6.097|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44163|0.44624|0.00078|0.18%|0.44295|0.00%|0.44287|0.00%|1.423|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6db18b74c)|0.44422|0.44825|0.00062|0.14%|0.44567|0.62%|0.44563|0.62%|1.212|-8.317|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/38cbbee4aa)|0.44437|0.44699|0.00052|0.12%|0.44572|0.63%|0.44577|0.65%|-0.175|-8.304|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/38cbbee4aa)|0.14348|0.14438|0.00021|0.15%|0.14385|-67.52%|0.14389|-67.51%|0.473|8.614|0.000|25.35 MB|
