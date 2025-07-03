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
| Time          |2025-07-03 00:50:01 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43511|0.44537|0.00141|0.44117|0.00%|0.44123|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8a75b3c50c)|0.43975|0.44614|0.00118|0.44067|-0.11%|0.44047|-0.17%|42.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/51149b65ad)|0.43949|0.44177|0.00053|0.44047|-0.16%|0.44044|-0.18%|42.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51149b65ad)|0.42024|0.42600|0.00096|0.42506|-3.65%|0.42512|-3.65%|51.52 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71045|0.71636|0.00094|0.71320|0.00%|0.71327|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8a75b3c50c)|0.70847|0.71227|0.00092|0.70977|-0.48%|0.70952|-0.52%|38.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/51149b65ad)|0.71225|0.71557|0.00073|0.71365|0.06%|0.71354|0.04%|38.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51149b65ad)|0.67809|0.68073|0.00062|0.67896|-4.80%|0.67885|-4.83%|45.14 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58222|0.58522|0.00062|0.58316|0.00%|0.58314|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8a75b3c50c)|0.58335|0.58584|0.00062|0.58426|0.19%|0.58411|0.17%|43.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/51149b65ad)|0.58274|0.58563|0.00072|0.58401|0.15%|0.58401|0.15%|43.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51149b65ad)|0.52503|0.52790|0.00072|0.52603|-9.80%|0.52591|-9.81%|61.57 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21351|0.21919|0.00147|0.21619|0.00%|0.21595|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8a75b3c50c)|0.21817|0.22115|0.00072|0.21929|1.43%|0.21906|1.44%|26.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/51149b65ad)|0.21365|0.21637|0.00076|0.21496|-0.57%|0.21494|-0.46%|26.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51149b65ad)|0.07554|0.07850|0.00069|0.07683|-64.46%|0.07683|-64.42%|27.94 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41927|1.44069|0.00517|1.43198|0.00%|1.43249|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8a75b3c50c)|1.28363|1.29763|0.00370|1.29039|-9.89%|1.29138|-9.85%|21.04 MB|
|[PHP - master](https://github.com/php/php-src/commit/51149b65ad)|1.31552|1.33629|0.00449|1.32293|-7.62%|1.32232|-7.69%|20.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/51149b65ad)|0.55290|0.56805|0.00394|0.55887|-60.97%|0.55871|-61.00%|22.37 MB|
