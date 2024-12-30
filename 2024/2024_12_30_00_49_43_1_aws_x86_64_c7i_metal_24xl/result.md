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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2024-12-30 00:49:43 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43874|0.44307|0.00069|0.43985|0.00%|0.43980|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8e40bb689e)|0.43640|0.44240|0.00084|0.43732|-0.58%|0.43723|-0.59%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ab38b52d3)|0.43619|0.43894|0.00057|0.43710|-0.63%|0.43696|-0.65%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ab38b52d3)|0.42637|0.42815|0.00041|0.42717|-2.88%|0.42718|-2.87%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71326|0.71593|0.00065|0.71451|0.00%|0.71440|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8e40bb689e)|0.71046|0.71370|0.00069|0.71154|-0.42%|0.71131|-0.43%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ab38b52d3)|0.70684|0.70918|0.00058|0.70791|-0.92%|0.70788|-0.91%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ab38b52d3)|0.68127|0.68440|0.00073|0.68263|-4.46%|0.68251|-4.46%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58061|0.58360|0.00062|0.58230|0.00%|0.58239|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8e40bb689e)|0.57950|0.58273|0.00060|0.58070|-0.27%|0.58062|-0.30%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ab38b52d3)|0.57437|0.58062|0.00197|0.57748|-0.83%|0.57840|-0.68%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ab38b52d3)|0.51938|0.52222|0.00049|0.52080|-10.56%|0.52073|-10.59%|61.90 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21504|0.21969|0.00098|0.21636|0.00%|0.21601|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8e40bb689e)|0.21123|0.21667|0.00097|0.21244|-1.81%|0.21222|-1.76%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ab38b52d3)|0.21512|0.22159|0.00127|0.21692|0.26%|0.21654|0.24%|26.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ab38b52d3)|0.07379|0.07676|0.00074|0.07517|-65.26%|0.07505|-65.26%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34088|1.36794|0.00575|1.35522|0.00%|1.35465|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8e40bb689e)|1.25322|1.27465|0.00493|1.26327|-6.78%|1.26321|-6.75%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ab38b52d3)|1.33494|1.35593|0.00446|1.34570|-0.70%|1.34602|-0.64%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ab38b52d3)|0.52500|0.54356|0.00422|0.53440|-60.57%|0.53423|-60.56%|21.66 MB|
