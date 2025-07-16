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
| OS            |Amazon Linux 2023.8.20250707|
| GCC           |11.5.0|
| Time          |2025-07-16 00:49:50 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44030|0.44220|0.00047|0.44102|0.00%|0.44101|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/142e378618)|0.43647|0.44008|0.00080|0.43725|-0.85%|0.43702|-0.91%|42.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/02b94556cf)|0.43712|0.44071|0.00081|0.43834|-0.61%|0.43809|-0.66%|42.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02b94556cf)|0.42389|0.42567|0.00047|0.42479|-3.68%|0.42480|-3.68%|51.58 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71211|0.71469|0.00062|0.71331|0.00%|0.71324|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/142e378618)|0.70977|0.72202|0.00212|0.71194|-0.19%|0.71149|-0.24%|38.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/02b94556cf)|0.70988|0.71237|0.00065|0.71091|-0.34%|0.71089|-0.33%|38.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02b94556cf)|0.67351|0.68284|0.00150|0.68103|-4.53%|0.68124|-4.49%|45.19 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58257|0.58532|0.00060|0.58378|0.00%|0.58368|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/142e378618)|0.58274|0.58500|0.00057|0.58372|-0.01%|0.58370|0.00%|43.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/02b94556cf)|0.58266|0.58475|0.00054|0.58361|-0.03%|0.58371|0.01%|43.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02b94556cf)|0.52409|0.52626|0.00044|0.52519|-10.04%|0.52515|-10.03%|62.24 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21459|0.21848|0.00098|0.21617|0.00%|0.21626|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/142e378618)|0.21766|0.22092|0.00065|0.21894|1.28%|0.21890|1.22%|26.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/02b94556cf)|0.21660|0.21945|0.00071|0.21783|0.77%|0.21792|0.77%|26.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02b94556cf)|0.07555|0.07868|0.00074|0.07697|-64.39%|0.07687|-64.46%|27.97 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41850|1.43319|0.00408|1.42656|0.00%|1.42747|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/142e378618)|1.29512|1.30702|0.00320|1.30140|-8.77%|1.30111|-8.85%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/02b94556cf)|1.27959|1.29094|0.00335|1.28492|-9.93%|1.28507|-9.98%|21.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02b94556cf)|0.55313|0.56791|0.00356|0.56113|-60.67%|0.56103|-60.70%|22.41 MB|
