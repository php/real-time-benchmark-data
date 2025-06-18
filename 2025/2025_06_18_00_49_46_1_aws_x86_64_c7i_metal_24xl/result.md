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
| Time          |2025-06-18 00:49:46 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44172|0.44525|0.00067|0.44275|0.00%|0.44270|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.44151|0.44444|0.00071|0.44260|-0.03%|0.44264|-0.01%|42.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.44065|0.44305|0.00051|0.44147|-0.29%|0.44147|-0.28%|42.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.42515|0.42663|0.00041|0.42585|-3.82%|0.42587|-3.80%|51.33 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70750|0.73064|0.00315|0.71636|0.00%|0.71612|0.00%|37.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.71237|0.71563|0.00075|0.71368|-0.37%|0.71368|-0.34%|38.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.71252|0.71592|0.00097|0.71385|-0.35%|0.71355|-0.36%|38.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.68060|0.68335|0.00066|0.68177|-4.83%|0.68156|-4.83%|45.01 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58018|0.58381|0.00084|0.58211|0.00%|0.58223|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.57937|0.58335|0.00090|0.58128|-0.14%|0.58130|-0.16%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.57971|0.58361|0.00069|0.58136|-0.13%|0.58120|-0.18%|43.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.52628|0.52850|0.00044|0.52727|-9.42%|0.52728|-9.44%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21556|0.22009|0.00104|0.21735|0.00%|0.21746|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|0.21574|0.21976|0.00096|0.21791|0.26%|0.21787|0.19%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.21600|0.21923|0.00078|0.21777|0.19%|0.21778|0.15%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.07575|0.07878|0.00088|0.07691|-64.62%|0.07666|-64.75%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34717|1.36628|0.00549|1.35480|0.00%|1.35362|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e2494fbef)|1.31246|1.33172|0.00489|1.32098|-2.50%|1.31954|-2.52%|20.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee1bbcf0bb)|1.31281|1.33392|0.00444|1.32096|-2.50%|1.32082|-2.42%|20.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.54731|0.57965|0.00686|0.56902|-58.00%|0.57008|-57.88%|22.23 MB|
