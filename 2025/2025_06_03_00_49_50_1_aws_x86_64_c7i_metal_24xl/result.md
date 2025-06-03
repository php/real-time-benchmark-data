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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250527|
| GCC           |11.5.0|
| Time          |2025-06-03 00:49:50 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43865|0.44807|0.00159|0.43977|0.00%|0.43950|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/910411f2f5)|0.44136|0.44387|0.00050|0.44209|0.53%|0.44209|0.59%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/36891a6775)|0.43980|0.44175|0.00050|0.44061|0.19%|0.44056|0.24%|42.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/36891a6775)|0.42165|0.42329|0.00038|0.42237|-3.96%|0.42233|-3.90%|51.25 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71254|0.72847|0.00271|0.71472|0.00%|0.71420|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/910411f2f5)|0.71026|0.71256|0.00064|0.71154|-0.44%|0.71154|-0.37%|37.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/36891a6775)|0.70989|0.72115|0.00195|0.71137|-0.47%|0.71095|-0.46%|37.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/36891a6775)|0.67218|0.68049|0.00137|0.67865|-5.05%|0.67885|-4.95%|45.01 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58028|0.58276|0.00058|0.58128|0.00%|0.58129|0.00%|43.09 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/910411f2f5)|0.57901|0.58192|0.00073|0.58061|-0.12%|0.58070|-0.10%|43.56 MB|
|[PHP - master](https://github.com/php/php-src/commit/36891a6775)|0.58066|0.58216|0.00040|0.58128|0.00%|0.58126|-0.01%|43.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/36891a6775)|0.52448|0.52707|0.00073|0.52543|-9.61%|0.52519|-9.65%|61.03 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21655|0.22002|0.00098|0.21782|0.00%|0.21764|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/910411f2f5)|0.21294|0.21619|0.00067|0.21403|-1.74%|0.21385|-1.74%|26.60 MB|
|[PHP - master](https://github.com/php/php-src/commit/36891a6775)|0.21240|0.21672|0.00112|0.21394|-1.78%|0.21361|-1.85%|26.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/36891a6775)|0.07662|0.07871|0.00046|0.07763|-64.36%|0.07749|-64.39%|27.76 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34500|1.37235|0.00642|1.35658|0.00%|1.35518|0.00%|20.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/910411f2f5)|1.30049|1.31341|0.00412|1.30739|-3.63%|1.30731|-3.53%|20.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/36891a6775)|1.29571|1.30901|0.00314|1.30348|-3.91%|1.30341|-3.82%|20.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/36891a6775)|0.54896|0.57160|0.00521|0.56248|-58.54%|0.56320|-58.44%|22.17 MB|
