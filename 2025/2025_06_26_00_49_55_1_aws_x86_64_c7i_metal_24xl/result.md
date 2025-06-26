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
| Time          |2025-06-26 00:49:55 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43762|0.45435|0.00254|0.44115|0.00%|0.44081|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aab281546c)|0.43916|0.44137|0.00048|0.44000|-0.26%|0.43991|-0.20%|42.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b61c49987)|0.43884|0.44116|0.00044|0.43977|-0.31%|0.43969|-0.26%|42.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8b61c49987)|0.42369|0.42498|0.00026|0.42402|-3.88%|0.42398|-3.82%|51.49 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71299|0.71596|0.00076|0.71424|0.00%|0.71428|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aab281546c)|0.70735|0.71364|0.00131|0.70880|-0.76%|0.70851|-0.81%|38.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b61c49987)|0.70712|0.71031|0.00086|0.70850|-0.80%|0.70829|-0.84%|38.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8b61c49987)|0.67997|0.68315|0.00072|0.68138|-4.60%|0.68135|-4.61%|45.17 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58163|0.58439|0.00057|0.58273|0.00%|0.58274|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aab281546c)|0.58304|0.58560|0.00057|0.58379|0.18%|0.58363|0.15%|43.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b61c49987)|0.58173|0.58468|0.00068|0.58319|0.08%|0.58323|0.09%|43.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8b61c49987)|0.52501|0.52728|0.00052|0.52615|-9.71%|0.52615|-9.71%|61.48 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21395|0.21833|0.00090|0.21565|0.00%|0.21550|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aab281546c)|0.21380|0.21792|0.00129|0.21549|-0.07%|0.21499|-0.24%|26.74 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b61c49987)|0.21359|0.21664|0.00084|0.21456|-0.50%|0.21436|-0.53%|26.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8b61c49987)|0.07653|0.07854|0.00055|0.07741|-64.10%|0.07730|-64.13%|27.97 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41910|1.43845|0.00511|1.42800|0.00%|1.42767|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aab281546c)|1.29367|1.30572|0.00303|1.29906|-9.03%|1.29895|-9.02%|21.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b61c49987)|1.29140|1.30814|0.00362|1.29911|-9.03%|1.29907|-9.01%|21.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8b61c49987)|0.55260|0.56165|0.00283|0.55760|-60.95%|0.55791|-60.92%|22.40 MB|
