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
| OS            |Amazon Linux 2023.6.20250123|
| GCC           |11.4.1|
| Time          |2025-01-27 00:49:37 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44027|0.44813|0.00133|0.44176|0.00%|0.44151|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75d7684e9f)|0.44105|0.44389|0.00058|0.44220|0.10%|0.44211|0.14%|41.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/60ee42eb3e)|0.44119|0.44458|0.00060|0.44232|0.13%|0.44240|0.20%|41.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60ee42eb3e)|0.43019|0.43275|0.00052|0.43126|-2.38%|0.43117|-2.34%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71580|0.71986|0.00084|0.71753|0.00%|0.71753|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75d7684e9f)|0.71757|0.72182|0.00089|0.71912|0.22%|0.71886|0.19%|37.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/60ee42eb3e)|0.72024|0.73606|0.00214|0.72215|0.64%|0.72178|0.59%|37.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60ee42eb3e)|0.69001|0.69316|0.00077|0.69146|-3.63%|0.69131|-3.65%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57806|0.58389|0.00143|0.57963|0.00%|0.57930|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75d7684e9f)|0.58165|0.58464|0.00062|0.58268|0.53%|0.58257|0.56%|42.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/60ee42eb3e)|0.57929|0.58137|0.00055|0.58013|0.09%|0.58012|0.14%|42.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60ee42eb3e)|0.52104|0.52368|0.00048|0.52226|-9.90%|0.52232|-9.84%|62.50 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21468|0.21865|0.00101|0.21606|0.00%|0.21580|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75d7684e9f)|0.21188|0.21612|0.00086|0.21369|-1.10%|0.21359|-1.02%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/60ee42eb3e)|0.21473|0.21843|0.00073|0.21610|0.02%|0.21613|0.15%|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60ee42eb3e)|0.07447|0.07668|0.00055|0.07565|-64.99%|0.07567|-64.94%|27.31 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33885|1.36179|0.00548|1.34815|0.00%|1.34748|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75d7684e9f)|1.25436|1.27713|0.00495|1.26525|-6.15%|1.26535|-6.09%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/60ee42eb3e)|1.26889|1.28751|0.00465|1.27802|-5.20%|1.27794|-5.16%|20.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60ee42eb3e)|0.54817|0.56913|0.00445|0.55773|-58.63%|0.55746|-58.63%|21.73 MB|
