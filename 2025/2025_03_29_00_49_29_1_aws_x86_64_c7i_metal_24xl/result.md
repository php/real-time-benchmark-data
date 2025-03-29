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
| Kernel        |6.1.130-139.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250317|
| GCC           |11.5.0|
| Time          |2025-03-29 00:49:29 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43827|0.43993|0.00040|0.43909|0.00%|0.43901|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0943b8b7eb)|0.43604|0.43809|0.00046|0.43673|-0.54%|0.43664|-0.54%|41.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/314219387e)|0.43560|0.43797|0.00055|0.43626|-0.64%|0.43610|-0.66%|41.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/314219387e)|0.42537|0.42807|0.00053|0.42618|-2.94%|0.42605|-2.95%|50.82 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71254|0.71581|0.00084|0.71384|0.00%|0.71355|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0943b8b7eb)|0.70585|0.70836|0.00067|0.70685|-0.98%|0.70675|-0.95%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/314219387e)|0.70490|0.70851|0.00083|0.70604|-1.09%|0.70577|-1.09%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/314219387e)|0.67819|0.68038|0.00051|0.67935|-4.83%|0.67927|-4.80%|44.59 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58043|0.58253|0.00047|0.58145|0.00%|0.58144|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0943b8b7eb)|0.57950|0.58200|0.00049|0.58031|-0.20%|0.58029|-0.20%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/314219387e)|0.57723|0.57973|0.00059|0.57847|-0.51%|0.57856|-0.50%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/314219387e)|0.52029|0.52170|0.00037|0.52087|-10.42%|0.52079|-10.43%|61.96 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21498|0.21864|0.00098|0.21636|0.00%|0.21609|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0943b8b7eb)|0.21765|0.22210|0.00132|0.22032|1.83%|0.22042|2.01%|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/314219387e)|0.21668|0.22123|0.00129|0.21901|1.23%|0.21881|1.26%|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/314219387e)|0.07436|0.07645|0.00055|0.07558|-65.07%|0.07548|-65.07%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34781|1.36983|0.00489|1.35641|0.00%|1.35497|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0943b8b7eb)|1.28356|1.30005|0.00455|1.29156|-4.78%|1.29246|-4.61%|20.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/314219387e)|1.26486|1.28100|0.00396|1.27237|-6.20%|1.27245|-6.09%|20.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/314219387e)|0.52909|0.54120|0.00318|0.53303|-60.70%|0.53200|-60.74%|21.82 MB|
