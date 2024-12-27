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
| Time          |2024-12-27 00:49:20 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43908|0.44223|0.00058|0.44007|0.00%|0.43998|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1c6520c4f)|0.43604|0.43788|0.00044|0.43708|-0.68%|0.43712|-0.65%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/f0554477ae)|0.43627|0.43859|0.00050|0.43700|-0.70%|0.43692|-0.70%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f0554477ae)|0.42623|0.42785|0.00037|0.42695|-2.98%|0.42698|-2.96%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71313|0.71597|0.00066|0.71443|0.00%|0.71443|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1c6520c4f)|0.71012|0.71495|0.00083|0.71209|-0.33%|0.71204|-0.33%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/f0554477ae)|0.70954|0.71256|0.00064|0.71076|-0.51%|0.71079|-0.51%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f0554477ae)|0.68500|0.68711|0.00056|0.68600|-3.98%|0.68607|-3.97%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58105|0.58375|0.00060|0.58243|0.00%|0.58231|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1c6520c4f)|0.57766|0.58069|0.00062|0.57920|-0.55%|0.57910|-0.55%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/f0554477ae)|0.57742|0.57940|0.00050|0.57839|-0.70%|0.57842|-0.67%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f0554477ae)|0.52068|0.52289|0.00053|0.52174|-10.42%|0.52177|-10.40%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21578|0.22000|0.00075|0.21694|0.00%|0.21685|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1c6520c4f)|0.21986|0.22814|0.00142|0.22203|2.34%|0.22191|2.33%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/f0554477ae)|0.21531|0.22138|0.00121|0.21719|0.11%|0.21681|-0.02%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f0554477ae)|0.07416|0.07765|0.00082|0.07581|-65.06%|0.07576|-65.06%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33578|1.37132|0.00687|1.35538|0.00%|1.35510|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1c6520c4f)|1.33891|1.36734|0.00591|1.35209|-0.24%|1.35205|-0.23%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/f0554477ae)|1.33545|1.36602|0.00669|1.35112|-0.31%|1.35089|-0.31%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f0554477ae)|0.52561|0.55715|0.00605|0.53817|-60.29%|0.53864|-60.25%|21.65 MB|
