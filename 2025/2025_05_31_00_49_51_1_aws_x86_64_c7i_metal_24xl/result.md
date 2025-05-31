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
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-05-31 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43759|0.43944|0.00044|0.43853|0.00%|0.43848|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56abb316eb)|0.43638|0.43934|0.00064|0.43739|-0.26%|0.43737|-0.25%|42.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/b64daf9b3f)|0.43801|0.44022|0.00053|0.43902|0.11%|0.43893|0.10%|42.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b64daf9b3f)|0.42135|0.42264|0.00037|0.42192|-3.79%|0.42189|-3.78%|51.28 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71296|0.71464|0.00048|0.71386|0.00%|0.71384|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56abb316eb)|0.71143|0.71489|0.00074|0.71284|-0.14%|0.71283|-0.14%|38.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/b64daf9b3f)|0.71122|0.71437|0.00074|0.71255|-0.18%|0.71258|-0.18%|38.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b64daf9b3f)|0.67703|0.68033|0.00081|0.67855|-4.95%|0.67859|-4.94%|45.03 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58000|0.58237|0.00055|0.58088|0.00%|0.58089|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56abb316eb)|0.57996|0.58456|0.00080|0.58124|0.06%|0.58120|0.05%|43.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/b64daf9b3f)|0.57966|0.58148|0.00047|0.58068|-0.03%|0.58077|-0.02%|43.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b64daf9b3f)|0.52258|0.52623|0.00072|0.52413|-9.77%|0.52410|-9.78%|61.05 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21564|0.21993|0.00107|0.21720|0.00%|0.21708|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56abb316eb)|0.21816|0.22191|0.00114|0.21970|1.15%|0.21927|1.01%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/b64daf9b3f)|0.26490|0.28496|0.00502|0.27496|26.59%|0.27523|26.79%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b64daf9b3f)|0.07616|0.07851|0.00059|0.07726|-64.43%|0.07719|-64.44%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34253|1.36197|0.00453|1.35003|0.00%|1.34981|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56abb316eb)|1.28811|1.31246|0.00599|1.30068|-3.66%|1.30049|-3.65%|20.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/b64daf9b3f)|1.29350|1.31322|0.00439|1.30057|-3.66%|1.29981|-3.70%|20.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b64daf9b3f)|0.54154|0.55917|0.00413|0.55199|-59.11%|0.55192|-59.11%|22.20 MB|
