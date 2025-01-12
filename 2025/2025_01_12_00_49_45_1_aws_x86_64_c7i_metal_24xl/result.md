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
| Time          |2025-01-12 00:49:45 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43865|0.45262|0.00188|0.43962|0.00%|0.43932|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11937b3df7)|0.43850|0.44046|0.00048|0.43937|-0.06%|0.43936|0.01%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6f42c1ed0)|0.43813|0.44055|0.00051|0.43912|-0.11%|0.43900|-0.07%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6f42c1ed0)|0.42489|0.43139|0.00089|0.42591|-3.12%|0.42579|-3.08%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71336|0.72928|0.00216|0.71550|0.00%|0.71503|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11937b3df7)|0.71450|0.71801|0.00074|0.71578|0.04%|0.71564|0.09%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6f42c1ed0)|0.71225|0.71502|0.00066|0.71370|-0.25%|0.71363|-0.19%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6f42c1ed0)|0.68360|0.68639|0.00067|0.68489|-4.28%|0.68496|-4.21%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57959|0.58423|0.00086|0.58223|0.00%|0.58223|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11937b3df7)|0.57939|0.58481|0.00096|0.58082|-0.24%|0.58063|-0.27%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6f42c1ed0)|0.57793|0.64425|0.02501|0.59192|1.66%|0.57940|-0.49%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6f42c1ed0)|0.51974|0.52296|0.00068|0.52090|-10.53%|0.52083|-10.55%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21467|0.21997|0.00111|0.21657|0.00%|0.21653|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11937b3df7)|0.21290|0.21780|0.00105|0.21490|-0.77%|0.21472|-0.84%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6f42c1ed0)|0.21536|0.22000|0.00100|0.21717|0.28%|0.21692|0.18%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6f42c1ed0)|0.07514|0.07807|0.00078|0.07624|-64.80%|0.07611|-64.85%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33867|1.36248|0.00527|1.35210|0.00%|1.35178|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/11937b3df7)|1.24726|1.26708|0.00464|1.25696|-7.04%|1.25641|-7.06%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6f42c1ed0)|1.29044|1.30982|0.00490|1.30169|-3.73%|1.30141|-3.73%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6f42c1ed0)|0.52978|0.55295|0.00561|0.54144|-59.96%|0.54170|-59.93%|21.72 MB|
