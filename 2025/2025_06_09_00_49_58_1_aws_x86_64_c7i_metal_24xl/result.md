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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250527|
| GCC           |11.5.0|
| Time          |2025-06-09 00:49:58 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43914|0.44189|0.00056|0.44025|0.00%|0.44029|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ceffa70b97)|0.44065|0.44325|0.00056|0.44156|0.30%|0.44141|0.25%|42.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3cfa4bcae)|0.44042|0.44795|0.00129|0.44137|0.26%|0.44109|0.18%|42.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3cfa4bcae)|0.42541|0.42703|0.00038|0.42605|-3.22%|0.42604|-3.24%|51.19 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71409|0.71677|0.00074|0.71521|0.00%|0.71522|0.00%|37.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ceffa70b97)|0.71058|0.71347|0.00070|0.71164|-0.50%|0.71142|-0.53%|37.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3cfa4bcae)|0.70894|0.71175|0.00068|0.71007|-0.72%|0.71007|-0.72%|37.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3cfa4bcae)|0.67742|0.68038|0.00073|0.67879|-5.09%|0.67871|-5.11%|44.96 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57998|0.58287|0.00058|0.58181|0.00%|0.58179|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ceffa70b97)|0.58235|0.58531|0.00055|0.58362|0.31%|0.58362|0.31%|43.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3cfa4bcae)|0.58186|0.58385|0.00050|0.58278|0.17%|0.58269|0.15%|43.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3cfa4bcae)|0.52668|0.52931|0.00057|0.52843|-9.17%|0.52854|-9.15%|61.16 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21534|0.21839|0.00063|0.21701|0.00%|0.21703|0.00%|26.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ceffa70b97)|0.21738|0.22137|0.00102|0.21864|0.75%|0.21830|0.58%|26.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3cfa4bcae)|0.25833|0.28168|0.00518|0.27370|26.12%|0.27359|26.06%|26.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3cfa4bcae)|0.07586|0.07907|0.00088|0.07699|-64.52%|0.07671|-64.65%|27.71 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34458|1.36000|0.00416|1.35172|0.00%|1.35251|0.00%|20.53 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ceffa70b97)|1.31049|1.32776|0.00461|1.32051|-2.31%|1.32094|-2.33%|20.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3cfa4bcae)|1.28988|1.31635|0.00496|1.29926|-3.88%|1.29911|-3.95%|20.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3cfa4bcae)|0.56114|0.58372|0.00516|0.57198|-57.69%|0.57154|-57.74%|22.12 MB|
