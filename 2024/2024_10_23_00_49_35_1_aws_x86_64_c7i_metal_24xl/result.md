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
| Time          |2024-10-23 00:49:35 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43883|0.44081|0.00052|0.43967|0.00%|0.43960|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6dd67bbb76)|0.43720|0.44016|0.00053|0.43784|-0.42%|0.43777|-0.42%|41.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/55e8ebe29b)|0.43529|0.44285|0.00114|0.43628|-0.77%|0.43604|-0.81%|41.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55e8ebe29b)|0.42668|0.42860|0.00041|0.42745|-2.78%|0.42744|-2.77%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71087|0.72299|0.00164|0.72074|0.00%|0.72083|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6dd67bbb76)|0.71618|0.71937|0.00069|0.71737|-0.47%|0.71721|-0.50%|37.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/55e8ebe29b)|0.70954|0.71656|0.00114|0.71353|-1.00%|0.71330|-1.04%|37.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55e8ebe29b)|0.68944|0.69321|0.00065|0.69083|-4.15%|0.69086|-4.16%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58278|0.58587|0.00058|0.58382|0.00%|0.58377|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6dd67bbb76)|0.57945|0.58282|0.00065|0.58057|-0.56%|0.58046|-0.57%|42.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/55e8ebe29b)|0.57823|0.58051|0.00054|0.57919|-0.79%|0.57915|-0.79%|42.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55e8ebe29b)|0.52486|0.52673|0.00044|0.52561|-9.97%|0.52552|-9.98%|61.88 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21489|0.21949|0.00088|0.21615|0.00%|0.21594|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6dd67bbb76)|0.21716|0.22156|0.00089|0.21846|1.06%|0.21828|1.09%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/55e8ebe29b)|0.21596|0.21938|0.00067|0.21756|0.65%|0.21760|0.77%|26.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55e8ebe29b)|0.07384|0.07724|0.00071|0.07515|-65.23%|0.07504|-65.25%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34121|1.36421|0.00541|1.35216|0.00%|1.35122|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6dd67bbb76)|1.27163|1.29290|0.00501|1.28255|-5.15%|1.28284|-5.06%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/55e8ebe29b)|1.27909|1.29417|0.00329|1.28527|-4.95%|1.28505|-4.90%|20.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55e8ebe29b)|0.53070|0.54678|0.00366|0.53791|-60.22%|0.53745|-60.23%|21.64 MB|
