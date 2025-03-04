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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-03-04 00:49:30 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43902|0.44166|0.00055|0.43979|0.00%|0.43974|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ae2c871d0)|0.43604|0.43871|0.00055|0.43694|-0.65%|0.43675|-0.68%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/0df99742c4)|0.43621|0.43931|0.00062|0.43741|-0.54%|0.43738|-0.54%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0df99742c4)|0.42676|0.42816|0.00038|0.42738|-2.82%|0.42748|-2.79%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71297|0.71579|0.00069|0.71381|0.00%|0.71374|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ae2c871d0)|0.70239|0.70658|0.00106|0.70397|-1.38%|0.70363|-1.42%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/0df99742c4)|0.70215|0.70514|0.00069|0.70346|-1.45%|0.70341|-1.45%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0df99742c4)|0.67891|0.68246|0.00078|0.68056|-4.66%|0.68065|-4.64%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58130|0.58343|0.00058|0.58235|0.00%|0.58230|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ae2c871d0)|0.57838|0.58133|0.00066|0.57933|-0.52%|0.57931|-0.51%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/0df99742c4)|0.57850|0.58088|0.00056|0.57944|-0.50%|0.57942|-0.50%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0df99742c4)|0.51903|0.52393|0.00085|0.52249|-10.28%|0.52249|-10.27%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21508|0.21915|0.00094|0.21641|0.00%|0.21619|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ae2c871d0)|0.21859|0.22124|0.00070|0.21972|1.53%|0.21971|1.63%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/0df99742c4)|0.21508|0.21967|0.00119|0.21720|0.36%|0.21720|0.47%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0df99742c4)|0.07553|0.07726|0.00047|0.07640|-64.70%|0.07640|-64.66%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34030|1.35895|0.00579|1.34985|0.00%|1.35098|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ae2c871d0)|1.27758|1.29999|0.00540|1.28812|-4.57%|1.28818|-4.65%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/0df99742c4)|1.37367|1.39384|0.00448|1.38128|2.33%|1.38132|2.25%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0df99742c4)|0.53790|0.56097|0.00559|0.54871|-59.35%|0.54763|-59.46%|21.79 MB|
