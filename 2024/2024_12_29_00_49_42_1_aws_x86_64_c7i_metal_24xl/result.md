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
| Time          |2024-12-29 00:49:42 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43927|0.44945|0.00138|0.44031|0.00%|0.44017|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f0554477ae)|0.43611|0.43795|0.00044|0.43696|-0.76%|0.43692|-0.74%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/8e40bb689e)|0.43703|0.44402|0.00096|0.43817|-0.49%|0.43791|-0.51%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8e40bb689e)|0.42625|0.42797|0.00039|0.42707|-3.01%|0.42704|-2.98%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71338|0.71638|0.00069|0.71503|0.00%|0.71489|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f0554477ae)|0.71070|0.71341|0.00057|0.71177|-0.46%|0.71170|-0.45%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/8e40bb689e)|0.71012|0.71294|0.00064|0.71157|-0.48%|0.71153|-0.47%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8e40bb689e)|0.68220|0.68497|0.00058|0.68345|-4.42%|0.68336|-4.41%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58175|0.58477|0.00062|0.58274|0.00%|0.58261|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f0554477ae)|0.57822|0.58078|0.00056|0.57907|-0.63%|0.57896|-0.62%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/8e40bb689e)|0.57583|0.58142|0.00201|0.57859|-0.71%|0.57875|-0.66%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8e40bb689e)|0.52054|0.52254|0.00043|0.52123|-10.56%|0.52117|-10.54%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21451|0.21849|0.00088|0.21603|0.00%|0.21594|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f0554477ae)|0.21594|0.22137|0.00123|0.21774|0.79%|0.21744|0.70%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/8e40bb689e)|0.21172|0.21443|0.00066|0.21280|-1.50%|0.21270|-1.50%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8e40bb689e)|0.07464|0.07834|0.00088|0.07605|-64.80%|0.07586|-64.87%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34041|1.36510|0.00571|1.35331|0.00%|1.35359|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f0554477ae)|1.33373|1.36014|0.00573|1.34889|-0.33%|1.34920|-0.32%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/8e40bb689e)|1.25160|1.27292|0.00473|1.26195|-6.75%|1.26197|-6.77%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8e40bb689e)|0.52614|0.54157|0.00320|0.53372|-60.56%|0.53351|-60.59%|21.65 MB|
