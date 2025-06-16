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
| Time          |2025-06-16 00:49:57 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43961|0.44970|0.00172|0.44079|0.00%|0.44044|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.43987|0.44244|0.00075|0.44072|-0.02%|0.44048|0.01%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.43933|0.44166|0.00056|0.44031|-0.11%|0.44017|-0.06%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.42386|0.42526|0.00035|0.42444|-3.71%|0.42442|-3.64%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71333|0.71735|0.00100|0.71490|0.00%|0.71488|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.71118|0.72225|0.00195|0.71252|-0.33%|0.71205|-0.40%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.71062|0.72289|0.00279|0.71263|-0.32%|0.71188|-0.42%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.67899|0.68223|0.00074|0.68016|-4.86%|0.68010|-4.87%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58118|0.58301|0.00049|0.58184|0.00%|0.58175|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.57974|0.58157|0.00049|0.58046|-0.24%|0.58041|-0.23%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.57958|0.64780|0.01212|0.58263|0.13%|0.58030|-0.25%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.52594|0.52737|0.00029|0.52651|-9.51%|0.52651|-9.50%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21583|0.22061|0.00138|0.21805|0.00%|0.21805|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.21587|0.21944|0.00094|0.21741|-0.29%|0.21748|-0.26%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.21627|0.21938|0.00070|0.21747|-0.27%|0.21740|-0.30%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.07553|0.07912|0.00089|0.07687|-64.75%|0.07682|-64.77%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34387|1.37335|0.00721|1.35382|0.00%|1.35308|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|1.31324|1.32785|0.00343|1.32293|-2.28%|1.32356|-2.18%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|1.32064|1.33516|0.00365|1.32808|-1.90%|1.32878|-1.80%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.55383|0.57179|0.00438|0.56241|-58.46%|0.56306|-58.39%|22.23 MB|
