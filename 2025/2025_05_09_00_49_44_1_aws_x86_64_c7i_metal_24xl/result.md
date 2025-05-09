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
| Time          |2025-05-09 00:49:44 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43763|0.43977|0.00045|0.43873|0.00%|0.43878|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3715cddf0)|0.43820|0.44149|0.00060|0.43904|0.07%|0.43894|0.04%|41.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b0cb760d4)|0.43777|0.44068|0.00067|0.43893|0.05%|0.43880|0.01%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b0cb760d4)|0.42589|0.42952|0.00065|0.42687|-2.70%|0.42683|-2.72%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71422|0.71686|0.00067|0.71543|0.00%|0.71540|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3715cddf0)|0.70963|0.71344|0.00096|0.71072|-0.66%|0.71056|-0.68%|37.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b0cb760d4)|0.70921|0.71356|0.00085|0.71050|-0.69%|0.71047|-0.69%|37.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b0cb760d4)|0.68456|0.68690|0.00060|0.68570|-4.16%|0.68578|-4.14%|44.61 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58119|0.58378|0.00072|0.58230|0.00%|0.58220|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3715cddf0)|0.58502|0.58823|0.00058|0.58616|0.66%|0.58615|0.68%|43.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b0cb760d4)|0.58522|0.58786|0.00061|0.58621|0.67%|0.58615|0.68%|43.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b0cb760d4)|0.52338|0.52556|0.00050|0.52440|-9.94%|0.52432|-9.94%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21585|0.21985|0.00087|0.21703|0.00%|0.21678|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3715cddf0)|0.21127|0.21938|0.00206|0.21420|-1.30%|0.21409|-1.24%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b0cb760d4)|0.21225|0.22018|0.00212|0.21436|-1.23%|0.21371|-1.42%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b0cb760d4)|0.07533|0.07900|0.00088|0.07689|-64.57%|0.07666|-64.64%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34295|1.37206|0.00686|1.35262|0.00%|1.35150|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3715cddf0)|1.26875|1.29281|0.00665|1.28056|-5.33%|1.27934|-5.34%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b0cb760d4)|1.27017|1.29368|0.00562|1.28216|-5.21%|1.28179|-5.16%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b0cb760d4)|0.56447|0.57831|0.00335|0.57119|-57.77%|0.57111|-57.74%|21.83 MB|
