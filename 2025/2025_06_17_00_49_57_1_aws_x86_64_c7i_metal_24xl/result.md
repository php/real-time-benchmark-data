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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-17 00:49:57 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44024|0.44205|0.00037|0.44100|0.00%|0.44100|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.44062|0.44273|0.00050|0.44129|0.07%|0.44121|0.05%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.43999|0.44689|0.00122|0.44094|-0.01%|0.44060|-0.09%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.42437|0.42548|0.00029|0.42484|-3.67%|0.42483|-3.67%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71507|0.73030|0.00268|0.71676|0.00%|0.71612|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.71177|0.71496|0.00082|0.71334|-0.48%|0.71354|-0.36%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.71210|0.71445|0.00078|0.71339|-0.47%|0.71358|-0.35%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.67946|0.68219|0.00072|0.68096|-4.99%|0.68102|-4.90%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58163|0.59178|0.00245|0.58615|0.00%|0.58702|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.58557|0.58840|0.00071|0.58652|0.06%|0.58632|-0.12%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.58236|0.58737|0.00141|0.58469|-0.25%|0.58432|-0.46%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.52890|0.53236|0.00110|0.53106|-9.40%|0.53152|-9.45%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21527|0.22228|0.00137|0.21782|0.00%|0.21775|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.21655|0.22001|0.00089|0.21812|0.14%|0.21815|0.18%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.21667|0.21980|0.00093|0.21831|0.23%|0.21843|0.31%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.07621|0.07880|0.00073|0.07716|-64.57%|0.07693|-64.67%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34812|1.37069|0.00527|1.35778|0.00%|1.35904|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|1.31518|1.33121|0.00452|1.32146|-2.67%|1.32113|-2.79%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|1.31367|1.33242|0.00508|1.32215|-2.62%|1.32078|-2.82%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.55574|0.57779|0.00564|0.57002|-58.02%|0.57247|-57.88%|22.23 MB|
