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
| Kernel        |6.1.141-165.249.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250715|
| GCC           |11.5.0|
| Time          |2025-07-23 00:50:17 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43986|0.44825|0.00144|0.44084|0.00%|0.44071|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113eb203b0)|0.43839|0.44064|0.00057|0.43944|-0.32%|0.43936|-0.31%|42.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/d292968f7c)|0.43693|0.44047|0.00066|0.43772|-0.71%|0.43761|-0.70%|42.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d292968f7c)|0.42228|0.42442|0.00040|0.42285|-4.08%|0.42284|-4.05%|51.47 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71262|0.71526|0.00062|0.71395|0.00%|0.71398|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113eb203b0)|0.71165|0.71752|0.00148|0.71353|-0.06%|0.71315|-0.12%|38.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/d292968f7c)|0.71005|0.71345|0.00078|0.71108|-0.40%|0.71090|-0.43%|38.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d292968f7c)|0.67321|0.68120|0.00131|0.67958|-4.81%|0.67972|-4.80%|45.08 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58314|0.58942|0.00203|0.58727|0.00%|0.58805|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113eb203b0)|0.58488|0.58966|0.00109|0.58689|-0.07%|0.58676|-0.22%|43.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/d292968f7c)|0.58480|0.58863|0.00095|0.58679|-0.08%|0.58692|-0.19%|43.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d292968f7c)|0.52910|0.53117|0.00049|0.53000|-9.75%|0.53003|-9.87%|62.19 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21406|0.21839|0.00121|0.21591|0.00%|0.21580|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113eb203b0)|0.21679|0.22094|0.00101|0.21838|1.14%|0.21822|1.12%|26.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/d292968f7c)|0.21489|0.22019|0.00132|0.21717|0.58%|0.21702|0.57%|26.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d292968f7c)|0.07555|0.07907|0.00091|0.07685|-64.41%|0.07653|-64.54%|27.92 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42052|1.44437|0.00545|1.42982|0.00%|1.43004|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/113eb203b0)|1.29836|1.31647|0.00486|1.30714|-8.58%|1.30706|-8.60%|21.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/d292968f7c)|1.28615|1.30163|0.00410|1.29542|-9.40%|1.29545|-9.41%|21.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d292968f7c)|0.55757|0.58027|0.00544|0.57017|-60.12%|0.57018|-60.13%|22.37 MB|
