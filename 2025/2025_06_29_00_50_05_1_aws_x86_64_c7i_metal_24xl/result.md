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
| Time          |2025-06-29 00:50:05 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43788|0.45501|0.00262|0.44148|0.00%|0.44106|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/22e444c5c7)|0.44049|0.44209|0.00049|0.44108|-0.09%|0.44100|-0.01%|42.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/761478a032)|0.43895|0.44117|0.00051|0.43974|-0.40%|0.43965|-0.32%|42.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/761478a032)|0.42518|0.42750|0.00055|0.42602|-3.50%|0.42595|-3.43%|51.60 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71281|0.71575|0.00078|0.71409|0.00%|0.71405|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/22e444c5c7)|0.70681|0.71166|0.00092|0.70817|-0.83%|0.70805|-0.84%|38.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/761478a032)|0.70586|0.70810|0.00057|0.70671|-1.03%|0.70664|-1.04%|38.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/761478a032)|0.67710|0.68049|0.00088|0.67854|-4.98%|0.67852|-4.98%|45.21 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58254|0.58434|0.00041|0.58339|0.00%|0.58347|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/22e444c5c7)|0.58293|0.59283|0.00172|0.58404|0.11%|0.58367|0.03%|43.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/761478a032)|0.58140|0.58318|0.00048|0.58236|-0.18%|0.58239|-0.18%|43.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/761478a032)|0.52459|0.52744|0.00051|0.52591|-9.85%|0.52588|-9.87%|61.64 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21363|0.22013|0.00167|0.21621|0.00%|0.21570|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/22e444c5c7)|0.21780|0.22164|0.00088|0.21922|1.39%|0.21928|1.66%|26.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/761478a032)|0.25806|0.27915|0.00525|0.27182|25.72%|0.27372|26.90%|26.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/761478a032)|0.07533|0.07905|0.00108|0.07708|-64.35%|0.07672|-64.43%|28.01 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42261|1.43492|0.00341|1.42850|0.00%|1.42871|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/22e444c5c7)|1.30983|1.32666|0.00394|1.31969|-7.62%|1.31982|-7.62%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/761478a032)|1.30921|1.32540|0.00444|1.31598|-7.88%|1.31508|-7.95%|21.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/761478a032)|0.54920|0.57725|0.00750|0.56502|-60.45%|0.56689|-60.32%|22.44 MB|
