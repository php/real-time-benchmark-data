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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20240916|
| GCC           |11.4.1|
| Time          |2024-09-28 00:49:31 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43731|0.44838|0.00193|0.43853|0.00%|0.43815|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b32a941b8e)|0.43608|0.43810|0.00057|0.43703|-0.34%|0.43688|-0.29%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/332e9a47ae)|0.43820|0.44055|0.00051|0.43902|0.11%|0.43894|0.18%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/332e9a47ae)|0.43747|0.43981|0.00065|0.43845|-0.02%|0.43824|0.02%|41.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71306|0.71720|0.00096|0.71522|0.00%|0.71514|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b32a941b8e)|0.71430|0.72012|0.00118|0.71598|0.11%|0.71565|0.07%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/332e9a47ae)|0.71271|0.71698|0.00098|0.71453|-0.10%|0.71438|-0.11%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/332e9a47ae)|0.71427|0.71846|0.00110|0.71577|0.08%|0.71562|0.07%|37.38 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57936|0.58329|0.00071|0.58079|0.00%|0.58081|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b32a941b8e)|0.57807|0.58057|0.00070|0.57925|-0.27%|0.57919|-0.28%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/332e9a47ae)|0.57753|0.57976|0.00060|0.57857|-0.38%|0.57856|-0.39%|43.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/332e9a47ae)|0.57708|0.57944|0.00051|0.57832|-0.43%|0.57840|-0.41%|43.00 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21493|0.22052|0.00107|0.21646|0.00%|0.21635|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b32a941b8e)|0.21895|0.22396|0.00107|0.22102|2.11%|0.22081|2.06%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/332e9a47ae)|0.21180|0.21722|0.00144|0.21349|-1.37%|0.21315|-1.48%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/332e9a47ae)|0.21205|0.21757|0.00164|0.21452|-0.90%|0.21439|-0.91%|26.23 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34141|1.36323|0.00458|1.35181|0.00%|1.35218|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b32a941b8e)|1.36395|1.38234|0.00404|1.37210|1.50%|1.37133|1.42%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/332e9a47ae)|1.35017|1.36646|0.00386|1.35816|0.47%|1.35871|0.48%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/332e9a47ae)|1.35467|1.37495|0.00547|1.36342|0.86%|1.36356|0.84%|20.49 MB|
