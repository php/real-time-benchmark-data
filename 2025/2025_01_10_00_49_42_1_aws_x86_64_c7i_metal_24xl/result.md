### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250107|
| GCC           |11.4.1|
| Time          |2025-01-10 00:49:42 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43825|0.44900|0.00148|0.43976|0.00%|0.43948|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a091e52316)|0.43457|0.43700|0.00043|0.43551|-0.97%|0.43545|-0.92%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d79ed6b3e)|0.43956|0.44682|0.00101|0.44030|0.12%|0.44013|0.15%|41.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d79ed6b3e)|0.42657|0.42846|0.00042|0.42732|-2.83%|0.42735|-2.76%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71405|0.71763|0.00074|0.71508|0.00%|0.71494|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a091e52316)|0.70595|0.71144|0.00083|0.70721|-1.10%|0.70703|-1.11%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d79ed6b3e)|0.71217|0.71535|0.00058|0.71369|-0.19%|0.71363|-0.18%|37.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d79ed6b3e)|0.68379|0.68620|0.00060|0.68482|-4.23%|0.68483|-4.21%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58171|0.58408|0.00056|0.58278|0.00%|0.58270|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a091e52316)|0.57768|0.58047|0.00065|0.57884|-0.68%|0.57882|-0.67%|42.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d79ed6b3e)|0.57631|0.58257|0.00171|0.58037|-0.41%|0.58095|-0.30%|42.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d79ed6b3e)|0.52014|0.52601|0.00088|0.52131|-10.55%|0.52112|-10.57%|61.98 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21447|0.21911|0.00098|0.21605|0.00%|0.21592|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a091e52316)|0.21552|0.22015|0.00109|0.21710|0.49%|0.21679|0.40%|26.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d79ed6b3e)|0.21202|0.21601|0.00096|0.21398|-0.96%|0.21389|-0.94%|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d79ed6b3e)|0.07549|0.07800|0.00060|0.07634|-64.66%|0.07621|-64.71%|27.31 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33973|1.37226|0.00722|1.35167|0.00%|1.35114|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a091e52316)|1.30586|1.33167|0.00570|1.31640|-2.61%|1.31470|-2.70%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d79ed6b3e)|1.24737|1.26916|0.00448|1.25836|-6.90%|1.25825|-6.87%|20.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d79ed6b3e)|0.52688|0.54329|0.00378|0.53405|-60.49%|0.53345|-60.52%|21.73 MB|
