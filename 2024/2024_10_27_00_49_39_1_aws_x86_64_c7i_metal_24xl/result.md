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
| Time          |2024-10-27 00:49:39 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43853|0.44094|0.00056|0.43952|0.00%|0.43945|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bfca4c7ba9)|0.43664|0.43956|0.00057|0.43775|-0.40%|0.43769|-0.40%|41.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8d388eb3a)|0.43604|0.44056|0.00077|0.43694|-0.59%|0.43667|-0.63%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8d388eb3a)|0.42757|0.42908|0.00034|0.42831|-2.55%|0.42831|-2.53%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71103|0.72233|0.00151|0.72047|0.00%|0.72061|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bfca4c7ba9)|0.71129|0.71561|0.00071|0.71301|-1.04%|0.71290|-1.07%|37.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8d388eb3a)|0.71410|0.73178|0.00237|0.71604|-0.62%|0.71562|-0.69%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8d388eb3a)|0.69225|0.69481|0.00050|0.69342|-3.76%|0.69333|-3.79%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58141|0.58439|0.00064|0.58309|0.00%|0.58314|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bfca4c7ba9)|0.58027|0.58346|0.00060|0.58120|-0.32%|0.58112|-0.35%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8d388eb3a)|0.58431|0.58604|0.00049|0.58524|0.37%|0.58524|0.36%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8d388eb3a)|0.52439|0.52671|0.00045|0.52558|-9.86%|0.52560|-9.87%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21452|0.21892|0.00096|0.21602|0.00%|0.21574|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bfca4c7ba9)|0.21577|0.21927|0.00081|0.21714|0.52%|0.21710|0.63%|26.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8d388eb3a)|0.21271|0.21653|0.00099|0.21403|-0.92%|0.21369|-0.95%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8d388eb3a)|0.07398|0.07772|0.00072|0.07546|-65.07%|0.07545|-65.03%|27.36 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33700|1.36104|0.00590|1.34791|0.00%|1.34799|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bfca4c7ba9)|1.24904|1.27359|0.00523|1.26138|-6.42%|1.26061|-6.48%|20.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8d388eb3a)|1.26978|1.29096|0.00520|1.27777|-5.20%|1.27679|-5.28%|20.49 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8d388eb3a)|0.53101|0.54815|0.00378|0.53870|-60.03%|0.53819|-60.07%|21.77 MB|
