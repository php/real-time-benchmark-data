### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-04 01:14:45 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25296315192 ([Artifacts](https://github.com/php/php-src/actions/runs/25296315192/artifacts/6775622305))|
| Changeset  |https://github.com/php/php-src/compare/794a35c705..87258eb267|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39448|0.39679|0.00073|0.19%|0.39526|0.00%|0.39494|0.00%|1.135|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/794a35c705)|0.38523|0.38677|0.00040|0.10%|0.38568|-2.42%|0.38558|-2.37%|1.587|8.614|0.000|25.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/87258eb267)|0.38547|0.38690|0.00028|0.07%|0.38596|-2.35%|0.38591|-2.29%|1.744|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87258eb267)|0.35971|0.36362|0.00078|0.22%|0.36038|-8.82%|0.36021|-8.79%|2.785|8.614|0.000|25.51 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67385|0.67583|0.00049|0.07%|0.67455|0.00%|0.67442|0.00%|1.171|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/794a35c705)|0.66362|0.66940|0.00083|0.12%|0.66430|-1.52%|0.66412|-1.53%|5.000|8.614|0.000|25.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/87258eb267)|0.66297|0.66588|0.00053|0.08%|0.66358|-1.63%|0.66340|-1.63%|2.483|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87258eb267)|0.63122|0.63350|0.00037|0.06%|0.63168|-6.36%|0.63161|-6.35%|2.667|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58748|0.59207|0.00100|0.17%|0.59008|0.00%|0.59010|0.00%|-0.040|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/794a35c705)|0.58355|0.58702|0.00069|0.12%|0.58444|-0.96%|0.58425|-0.99%|2.239|8.614|0.000|25.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/87258eb267)|0.58361|0.58713|0.00078|0.13%|0.58460|-0.93%|0.58432|-0.98%|1.530|8.614|0.000|25.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87258eb267)|0.51468|0.51873|0.00070|0.14%|0.51550|-12.64%|0.51538|-12.66%|2.810|8.614|0.000|25.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44209|0.44433|0.00049|0.11%|0.44297|0.00%|0.44296|0.00%|0.563|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/794a35c705)|0.44573|0.44857|0.00061|0.14%|0.44675|0.85%|0.44666|0.83%|0.833|-8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/87258eb267)|0.44510|0.44968|0.00084|0.19%|0.44675|0.85%|0.44667|0.84%|1.039|-8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87258eb267)|0.14356|0.14838|0.00087|0.60%|0.14419|-67.45%|0.14397|-67.50%|3.407|8.614|0.000|25.35 MB|
