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
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2024-12-15 00:49:48 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43899|0.45310|0.00193|0.44007|0.00%|0.43975|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bb6dbdcf94)|0.43702|0.43856|0.00038|0.43774|-0.53%|0.43766|-0.48%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/57e9429e73)|0.43687|0.43851|0.00036|0.43780|-0.52%|0.43782|-0.44%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/57e9429e73)|0.42479|0.42694|0.00042|0.42581|-3.24%|0.42573|-3.19%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71365|0.71753|0.00077|0.71480|0.00%|0.71467|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bb6dbdcf94)|0.70790|0.71147|0.00081|0.70921|-0.78%|0.70913|-0.78%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/57e9429e73)|0.70880|0.71131|0.00064|0.71029|-0.63%|0.71036|-0.60%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/57e9429e73)|0.68160|0.68538|0.00067|0.68297|-4.45%|0.68296|-4.44%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58149|0.58434|0.00073|0.58245|0.00%|0.58228|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bb6dbdcf94)|0.57669|0.58018|0.00066|0.57809|-0.75%|0.57812|-0.71%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/57e9429e73)|0.58047|0.58276|0.00043|0.58144|-0.17%|0.58148|-0.14%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/57e9429e73)|0.51995|0.52278|0.00052|0.52099|-10.55%|0.52095|-10.53%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21484|0.22101|0.00104|0.21640|0.00%|0.21625|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bb6dbdcf94)|0.21502|0.21837|0.00075|0.21619|-0.10%|0.21613|-0.05%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/57e9429e73)|0.21302|0.21761|0.00089|0.21441|-0.92%|0.21421|-0.94%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/57e9429e73)|0.07433|0.07765|0.00080|0.07546|-65.13%|0.07527|-65.19%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34082|1.37431|0.00626|1.35611|0.00%|1.35566|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bb6dbdcf94)|1.27806|1.30221|0.00497|1.28961|-4.90%|1.29023|-4.83%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/57e9429e73)|1.25207|1.27544|0.00398|1.25942|-7.13%|1.25907|-7.12%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/57e9429e73)|0.52627|0.55134|0.00446|0.53564|-60.50%|0.53527|-60.52%|21.64 MB|
