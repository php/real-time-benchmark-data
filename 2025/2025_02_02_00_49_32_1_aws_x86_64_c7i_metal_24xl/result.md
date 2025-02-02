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
| Kernel        |6.1.124-134.200.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250128|
| GCC           |11.4.1|
| Time          |2025-02-02 00:49:32 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43904|0.44101|0.00049|0.43989|0.00%|0.43996|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8deca2838c)|0.43939|0.44550|0.00089|0.44032|0.10%|0.44014|0.04%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/e306a2e0e8)|0.43788|0.44203|0.00060|0.43888|-0.23%|0.43889|-0.24%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e306a2e0e8)|0.42580|0.42776|0.00039|0.42659|-3.02%|0.42651|-3.06%|50.79 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71198|0.72821|0.00218|0.71351|0.00%|0.71330|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8deca2838c)|0.70917|0.71364|0.00098|0.71050|-0.42%|0.71042|-0.40%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/e306a2e0e8)|0.70900|0.71330|0.00096|0.71062|-0.41%|0.71044|-0.40%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e306a2e0e8)|0.68204|0.68527|0.00070|0.68327|-4.24%|0.68321|-4.22%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58114|0.64467|0.02570|0.59741|0.00%|0.58231|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8deca2838c)|0.58220|0.58465|0.00060|0.58299|-2.41%|0.58287|0.10%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/e306a2e0e8)|0.57963|0.58212|0.00054|0.58072|-2.79%|0.58066|-0.28%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e306a2e0e8)|0.51755|0.58535|0.01126|0.52385|-12.31%|0.52161|-10.42%|61.92 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21470|0.21816|0.00075|0.21571|0.00%|0.21555|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8deca2838c)|0.21243|0.21685|0.00096|0.21402|-0.78%|0.21406|-0.69%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/e306a2e0e8)|0.21543|0.21968|0.00103|0.21738|0.78%|0.21724|0.78%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e306a2e0e8)|0.07405|0.07748|0.00078|0.07554|-64.98%|0.07543|-65.01%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33363|1.36504|0.00571|1.35071|0.00%|1.35011|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8deca2838c)|1.27953|1.30642|0.00670|1.29113|-4.41%|1.29247|-4.27%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/e306a2e0e8)|1.29084|1.30994|0.00521|1.30102|-3.68%|1.30120|-3.62%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e306a2e0e8)|0.53773|0.56794|0.00693|0.55227|-59.11%|0.55258|-59.07%|21.71 MB|
