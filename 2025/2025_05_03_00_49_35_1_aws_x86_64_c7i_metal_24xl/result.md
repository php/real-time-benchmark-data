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
| Kernel        |6.1.134-150.224.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250428|
| GCC           |11.5.0|
| Time          |2025-05-03 00:49:35 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43448|0.43624|0.00049|0.43528|0.00%|0.43515|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd5733202d)|0.43596|0.43727|0.00033|0.43647|0.27%|0.43645|0.30%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/07959fc007)|0.43224|0.43468|0.00057|0.43305|-0.51%|0.43298|-0.50%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/07959fc007)|0.41950|0.42119|0.00039|0.42032|-3.44%|0.42026|-3.42%|50.84 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70979|0.71234|0.00062|0.71049|0.00%|0.71024|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd5733202d)|0.70554|0.70914|0.00089|0.70691|-0.50%|0.70697|-0.46%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/07959fc007)|0.70252|0.70636|0.00082|0.70398|-0.92%|0.70390|-0.89%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/07959fc007)|0.67183|0.67931|0.00121|0.67780|-4.60%|0.67796|-4.55%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57818|0.58068|0.00064|0.57940|0.00%|0.57937|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd5733202d)|0.58135|0.58448|0.00073|0.58236|0.51%|0.58218|0.48%|43.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/07959fc007)|0.57963|0.58146|0.00046|0.58035|0.16%|0.58039|0.18%|43.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/07959fc007)|0.51786|0.52078|0.00057|0.51883|-10.45%|0.51874|-10.46%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21529|0.21964|0.00093|0.21664|0.00%|0.21664|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd5733202d)|0.21643|0.22261|0.00162|0.21854|0.88%|0.21837|0.80%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/07959fc007)|0.21670|0.22529|0.00175|0.21826|0.74%|0.21783|0.55%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/07959fc007)|0.07485|0.07803|0.00074|0.07648|-64.70%|0.07637|-64.75%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34584|1.36540|0.00532|1.35394|0.00%|1.35505|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd5733202d)|1.27859|1.29670|0.00498|1.28665|-4.97%|1.28688|-5.03%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/07959fc007)|1.29397|1.31253|0.00468|1.30162|-3.86%|1.30083|-4.00%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/07959fc007)|0.56321|0.57898|0.00402|0.57167|-57.78%|0.57268|-57.74%|21.82 MB|
