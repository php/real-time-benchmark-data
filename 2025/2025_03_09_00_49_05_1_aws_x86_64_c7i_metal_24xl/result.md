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
| Kernel        |6.1.129-138.220.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250303|
| GCC           |11.4.1|
| Time          |2025-03-09 00:49:05 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44071|0.44278|0.00048|0.44170|0.00%|0.44164|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3772b502f6)|0.43642|0.44417|0.00133|0.43804|-0.83%|0.43785|-0.86%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/30ce9acd33)|0.43991|0.44266|0.00056|0.44067|-0.23%|0.44054|-0.25%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30ce9acd33)|0.42827|0.43089|0.00057|0.42912|-2.85%|0.42900|-2.86%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71335|0.71964|0.00115|0.71776|0.00%|0.71783|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3772b502f6)|0.70792|0.72115|0.00225|0.71009|-1.07%|0.70952|-1.16%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/30ce9acd33)|0.70890|0.72145|0.00219|0.71047|-1.02%|0.71004|-1.09%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30ce9acd33)|0.68152|0.68408|0.00075|0.68256|-4.90%|0.68231|-4.95%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58077|0.58366|0.00069|0.58221|0.00%|0.58213|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3772b502f6)|0.57866|0.58170|0.00066|0.57984|-0.41%|0.57989|-0.39%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/30ce9acd33)|0.57510|0.57806|0.00064|0.57639|-1.00%|0.57638|-0.99%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30ce9acd33)|0.51985|0.52205|0.00053|0.52068|-10.57%|0.52057|-10.58%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21447|0.22032|0.00135|0.21630|0.00%|0.21594|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3772b502f6)|0.21720|0.22045|0.00097|0.21870|1.11%|0.21851|1.19%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/30ce9acd33)|0.21564|0.22045|0.00094|0.21672|0.19%|0.21651|0.26%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30ce9acd33)|0.07464|0.07700|0.00065|0.07599|-64.87%|0.07612|-64.75%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34133|1.35692|0.00477|1.34912|0.00%|1.34791|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3772b502f6)|1.29287|1.31317|0.00449|1.30307|-3.41%|1.30369|-3.28%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/30ce9acd33)|1.27796|1.29627|0.00424|1.28912|-4.45%|1.28883|-4.38%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/30ce9acd33)|0.52502|0.54019|0.00372|0.53307|-60.49%|0.53372|-60.40%|21.79 MB|
