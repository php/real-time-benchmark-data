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
| Time          |2024-11-13 00:49:29 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43759|0.43930|0.00039|0.43820|0.00%|0.43812|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f5a888bdb)|0.43545|0.43728|0.00042|0.43623|-0.45%|0.43626|-0.42%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/33ba1a4ab9)|0.43501|0.43719|0.00041|0.43605|-0.49%|0.43600|-0.48%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33ba1a4ab9)|0.42527|0.42675|0.00033|0.42602|-2.78%|0.42602|-2.76%|50.85 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71783|0.72131|0.00074|0.71934|0.00%|0.71936|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f5a888bdb)|0.71355|0.71812|0.00088|0.71500|-0.60%|0.71484|-0.63%|37.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/33ba1a4ab9)|0.71343|0.71625|0.00059|0.71464|-0.65%|0.71449|-0.68%|37.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33ba1a4ab9)|0.69054|0.69328|0.00059|0.69158|-3.86%|0.69150|-3.87%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58099|0.58404|0.00058|0.58236|0.00%|0.58226|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f5a888bdb)|0.57781|0.58034|0.00054|0.57904|-0.57%|0.57901|-0.56%|43.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/33ba1a4ab9)|0.57621|0.58551|0.00137|0.57723|-0.88%|0.57691|-0.92%|43.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33ba1a4ab9)|0.51970|0.52276|0.00051|0.52102|-10.53%|0.52105|-10.51%|62.00 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21448|0.21918|0.00097|0.21628|0.00%|0.21619|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f5a888bdb)|0.21556|0.22173|0.00103|0.21716|0.41%|0.21709|0.42%|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/33ba1a4ab9)|0.21533|0.22045|0.00113|0.21685|0.26%|0.21661|0.19%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33ba1a4ab9)|0.07293|0.07727|0.00081|0.07439|-65.60%|0.07420|-65.68%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33837|1.36554|0.00591|1.34975|0.00%|1.34921|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f5a888bdb)|1.29092|1.32177|0.00675|1.30462|-3.34%|1.30445|-3.32%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/33ba1a4ab9)|1.29321|1.32383|0.00664|1.30668|-3.19%|1.30697|-3.13%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33ba1a4ab9)|0.51973|0.54215|0.00503|0.52810|-60.87%|0.52728|-60.92%|21.80 MB|
