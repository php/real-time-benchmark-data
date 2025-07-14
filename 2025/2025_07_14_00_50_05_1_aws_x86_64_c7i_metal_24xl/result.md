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
| Kernel        |6.1.141-165.249.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250707|
| GCC           |11.5.0|
| Time          |2025-07-14 00:50:05 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44059|0.45453|0.00243|0.44176|0.00%|0.44125|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a402edac1a)|0.43333|0.44229|0.00134|0.43945|-0.52%|0.43958|-0.38%|42.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d9fc506df)|0.43845|0.44039|0.00046|0.43914|-0.59%|0.43907|-0.50%|42.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d9fc506df)|0.42264|0.42531|0.00052|0.42346|-4.14%|0.42345|-4.04%|51.60 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71204|0.71480|0.00073|0.71368|0.00%|0.71371|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a402edac1a)|0.71120|0.71641|0.00109|0.71274|-0.13%|0.71252|-0.17%|38.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d9fc506df)|0.71122|0.71566|0.00105|0.71269|-0.14%|0.71256|-0.16%|38.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d9fc506df)|0.67606|0.68203|0.00103|0.67985|-4.74%|0.67985|-4.74%|45.22 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58379|0.58638|0.00056|0.58472|0.00%|0.58465|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a402edac1a)|0.58419|0.58892|0.00095|0.58581|0.19%|0.58570|0.18%|43.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d9fc506df)|0.58001|0.58648|0.00191|0.58434|-0.07%|0.58503|0.07%|43.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d9fc506df)|0.52648|0.52824|0.00049|0.52743|-9.80%|0.52735|-9.80%|61.65 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21390|0.21984|0.00115|0.21600|0.00%|0.21573|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a402edac1a)|0.21415|0.21903|0.00105|0.21619|0.09%|0.21611|0.18%|26.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d9fc506df)|0.21444|0.21815|0.00100|0.21602|0.01%|0.21601|0.13%|26.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d9fc506df)|0.07635|0.07936|0.00062|0.07764|-64.06%|0.07748|-64.08%|28.01 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42102|1.43660|0.00388|1.42774|0.00%|1.42842|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a402edac1a)|1.31809|1.33939|0.00464|1.32509|-7.19%|1.32507|-7.24%|21.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d9fc506df)|1.32303|1.33932|0.00399|1.33060|-6.80%|1.33099|-6.82%|21.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d9fc506df)|0.56387|0.57871|0.00317|0.56955|-60.11%|0.56950|-60.13%|22.46 MB|
