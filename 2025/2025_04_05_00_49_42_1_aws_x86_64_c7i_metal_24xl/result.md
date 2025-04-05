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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-05 00:49:42 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43982|0.44193|0.00059|0.44078|0.00%|0.44071|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/68665d3cb5)|0.43957|0.44345|0.00075|0.44077|-0.00%|0.44077|0.01%|41.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/d80682e753)|0.43879|0.44126|0.00069|0.44005|-0.17%|0.44007|-0.14%|41.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d80682e753)|0.42799|0.43030|0.00060|0.42898|-2.68%|0.42901|-2.65%|50.87 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71388|0.73193|0.00312|0.71558|0.00%|0.71501|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/68665d3cb5)|0.71346|0.71708|0.00083|0.71462|-0.13%|0.71438|-0.09%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/d80682e753)|0.71068|0.71412|0.00093|0.71201|-0.50%|0.71213|-0.40%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d80682e753)|0.68079|0.68330|0.00073|0.68208|-4.68%|0.68209|-4.60%|44.71 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58033|0.59063|0.00171|0.58196|0.00%|0.58160|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/68665d3cb5)|0.57832|0.58025|0.00048|0.57934|-0.45%|0.57937|-0.38%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/d80682e753)|0.57957|0.58226|0.00065|0.58050|-0.25%|0.58028|-0.23%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d80682e753)|0.52042|0.52236|0.00044|0.52128|-10.43%|0.52130|-10.37%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21450|0.21879|0.00104|0.21632|0.00%|0.21603|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/68665d3cb5)|0.21644|0.21886|0.00062|0.21759|0.59%|0.21754|0.70%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/d80682e753)|0.21661|0.22113|0.00120|0.21850|1.01%|0.21826|1.03%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d80682e753)|0.07570|0.07815|0.00064|0.07685|-64.48%|0.07674|-64.48%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34244|1.36661|0.00591|1.35157|0.00%|1.35196|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/68665d3cb5)|1.25361|1.27381|0.00558|1.26510|-6.40%|1.26533|-6.41%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/d80682e753)|1.29182|1.30970|0.00459|1.29893|-3.89%|1.29784|-4.00%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d80682e753)|0.54327|0.56331|0.00574|0.55263|-59.11%|0.55270|-59.12%|21.82 MB|
