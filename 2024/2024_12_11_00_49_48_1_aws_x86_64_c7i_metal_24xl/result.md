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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241209|
| GCC           |11.4.1|
| Time          |2024-12-11 00:49:48 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43956|0.45440|0.00196|0.44113|0.00%|0.44084|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ef9302c31)|0.43726|0.44498|0.00107|0.43857|-0.58%|0.43845|-0.54%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e759e079f)|0.43815|0.44528|0.00099|0.43925|-0.43%|0.43913|-0.39%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e759e079f)|0.42592|0.42752|0.00033|0.42693|-3.22%|0.42696|-3.15%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71572|0.71960|0.00083|0.71728|0.00%|0.71732|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ef9302c31)|0.71111|0.71442|0.00080|0.71280|-0.63%|0.71279|-0.63%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e759e079f)|0.70557|0.71482|0.00125|0.71178|-0.77%|0.71180|-0.77%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e759e079f)|0.68278|0.68700|0.00076|0.68507|-4.49%|0.68511|-4.49%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58139|0.58374|0.00053|0.58252|0.00%|0.58255|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ef9302c31)|0.57741|0.58059|0.00062|0.57916|-0.58%|0.57919|-0.58%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e759e079f)|0.57745|0.58078|0.00065|0.57895|-0.61%|0.57898|-0.61%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e759e079f)|0.51873|0.52349|0.00102|0.52206|-10.38%|0.52231|-10.34%|60.84 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21456|0.21963|0.00122|0.21641|0.00%|0.21603|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ef9302c31)|0.21504|0.22042|0.00093|0.21686|0.21%|0.21686|0.38%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e759e079f)|0.21552|0.21828|0.00071|0.21676|0.16%|0.21667|0.30%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e759e079f)|0.07381|0.07760|0.00090|0.07535|-65.18%|0.07519|-65.19%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34236|1.36731|0.00524|1.35379|0.00%|1.35295|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ef9302c31)|1.32773|1.34561|0.00457|1.33767|-1.19%|1.33823|-1.09%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/6e759e079f)|1.32580|1.34555|0.00472|1.33602|-1.31%|1.33562|-1.28%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6e759e079f)|0.52554|0.54652|0.00473|0.53934|-60.16%|0.53923|-60.14%|21.64 MB|
