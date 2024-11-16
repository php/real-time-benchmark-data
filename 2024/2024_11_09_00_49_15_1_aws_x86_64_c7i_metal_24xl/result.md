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
| Kernel        |6.1.112-124.190.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241031|
| GCC           |11.4.1|
| Time          |2024-11-09 00:49:15 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43830|0.44841|0.00141|0.43926|0.00%|0.43899|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1bf3acf44)|0.43623|0.43848|0.00044|0.43717|-0.48%|0.43712|-0.43%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/963511bffa)|0.43615|0.43818|0.00049|0.43698|-0.52%|0.43693|-0.47%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/963511bffa)|0.42641|0.42824|0.00037|0.42715|-2.76%|0.42712|-2.70%|50.87 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71919|0.72206|0.00071|0.72037|0.00%|0.72036|0.00%|37.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1bf3acf44)|0.71520|0.71855|0.00072|0.71642|-0.55%|0.71617|-0.58%|37.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/963511bffa)|0.71723|0.71984|0.00065|0.71837|-0.28%|0.71832|-0.28%|37.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/963511bffa)|0.69100|0.69377|0.00052|0.69236|-3.89%|0.69232|-3.89%|44.57 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58299|0.58952|0.00164|0.58738|0.00%|0.58791|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1bf3acf44)|0.57894|0.58623|0.00180|0.58348|-0.66%|0.58406|-0.65%|43.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/963511bffa)|0.58385|0.58659|0.00071|0.58498|-0.41%|0.58492|-0.51%|43.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/963511bffa)|0.52864|0.53095|0.00051|0.52957|-9.84%|0.52948|-9.94%|62.01 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21584|0.22178|0.00118|0.21736|0.00%|0.21710|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1bf3acf44)|0.21467|0.21925|0.00107|0.21693|-0.20%|0.21690|-0.09%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/963511bffa)|0.21626|0.21975|0.00086|0.21746|0.04%|0.21725|0.07%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/963511bffa)|0.07385|0.07749|0.00089|0.07530|-65.36%|0.07520|-65.36%|27.41 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33687|1.36088|0.00491|1.35088|0.00%|1.35106|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1bf3acf44)|1.25432|1.27451|0.00479|1.26387|-6.44%|1.26353|-6.48%|20.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/963511bffa)|1.33132|1.35590|0.00621|1.34229|-0.64%|1.34232|-0.65%|20.49 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/963511bffa)|0.50899|0.52685|0.00337|0.51885|-61.59%|0.51902|-61.58%|21.82 MB|