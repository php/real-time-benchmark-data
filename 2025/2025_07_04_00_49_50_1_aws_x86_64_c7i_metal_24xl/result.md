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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-07-04 00:49:50 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43977|0.44210|0.00049|0.44101|0.00%|0.44104|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51149b65ad)|0.44063|0.44230|0.00047|0.44128|0.06%|0.44112|0.02%|42.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/50ddf6a68f)|0.43905|0.44091|0.00041|0.43974|-0.29%|0.43964|-0.32%|42.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/50ddf6a68f)|0.42385|0.42533|0.00037|0.42459|-3.72%|0.42452|-3.75%|51.58 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71282|0.71670|0.00084|0.71418|0.00%|0.71396|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51149b65ad)|0.71280|0.71609|0.00075|0.71398|-0.03%|0.71374|-0.03%|38.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/50ddf6a68f)|0.70906|0.71206|0.00090|0.71042|-0.53%|0.71033|-0.51%|38.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/50ddf6a68f)|0.67915|0.68208|0.00075|0.68054|-4.71%|0.68042|-4.70%|45.20 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58240|0.58450|0.00045|0.58320|0.00%|0.58312|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51149b65ad)|0.57911|0.58562|0.00108|0.58407|0.15%|0.58429|0.20%|43.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/50ddf6a68f)|0.58101|0.58756|0.00239|0.58463|0.25%|0.58594|0.48%|43.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/50ddf6a68f)|0.52952|0.53148|0.00046|0.53037|-9.06%|0.53030|-9.06%|61.63 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21428|0.21884|0.00124|0.21611|0.00%|0.21603|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51149b65ad)|0.21414|0.21908|0.00113|0.21653|0.19%|0.21618|0.07%|26.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/50ddf6a68f)|0.21213|0.21712|0.00114|0.21325|-1.32%|0.21298|-1.41%|26.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/50ddf6a68f)|0.07532|0.07735|0.00063|0.07617|-64.75%|0.07604|-64.80%|28.00 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42010|1.44045|0.00416|1.42922|0.00%|1.42966|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51149b65ad)|1.30910|1.33398|0.00490|1.32152|-7.54%|1.32155|-7.56%|21.04 MB|
|[PHP - master](https://github.com/php/php-src/commit/50ddf6a68f)|1.29466|1.31078|0.00464|1.30151|-8.94%|1.30051|-9.03%|20.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/50ddf6a68f)|0.57699|0.59375|0.00373|0.58504|-59.07%|0.58513|-59.07%|22.43 MB|
