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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-11-03 00:49:43 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43822|0.44730|0.00158|0.43950|0.00%|0.43920|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b10cd1beb)|0.43681|0.43851|0.00038|0.43745|-0.47%|0.43744|-0.40%|41.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/64f2d11e38)|0.43695|0.43895|0.00051|0.43770|-0.41%|0.43760|-0.36%|41.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64f2d11e38)|0.42710|0.42892|0.00039|0.42775|-2.67%|0.42769|-2.62%|50.85 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71942|0.72379|0.00083|0.72080|0.00%|0.72067|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b10cd1beb)|0.71551|0.71938|0.00087|0.71705|-0.52%|0.71702|-0.51%|37.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/64f2d11e38)|0.71189|0.72037|0.00122|0.71799|-0.39%|0.71789|-0.38%|37.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64f2d11e38)|0.69520|0.69834|0.00057|0.69623|-3.41%|0.69620|-3.39%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58207|0.58503|0.00064|0.58343|0.00%|0.58346|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b10cd1beb)|0.58286|0.58528|0.00058|0.58387|0.08%|0.58377|0.05%|43.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/64f2d11e38)|0.58378|0.58649|0.00054|0.58495|0.26%|0.58481|0.23%|43.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64f2d11e38)|0.52352|0.52930|0.00189|0.52581|-9.88%|0.52476|-10.06%|61.99 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21497|0.21946|0.00097|0.21618|0.00%|0.21604|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b10cd1beb)|0.21266|0.21712|0.00086|0.21380|-1.10%|0.21362|-1.12%|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/64f2d11e38)|0.21236|0.21501|0.00055|0.21345|-1.26%|0.21344|-1.20%|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64f2d11e38)|0.07328|0.07666|0.00079|0.07461|-65.48%|0.07466|-65.44%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33935|1.35877|0.00398|1.34991|0.00%|1.35016|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b10cd1beb)|1.42024|1.43760|0.00380|1.42930|5.88%|1.42968|5.89%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/64f2d11e38)|1.26570|1.28158|0.00384|1.27364|-5.65%|1.27432|-5.62%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64f2d11e38)|0.55844|0.57321|0.00371|0.56699|-58.00%|0.56623|-58.06%|21.80 MB|
