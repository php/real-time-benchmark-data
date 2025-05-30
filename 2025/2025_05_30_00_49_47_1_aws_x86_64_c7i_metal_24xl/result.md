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
| Time          |2025-05-30 00:49:47 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43823|0.44017|0.00048|0.43906|0.00%|0.43901|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a63d0a49b0)|0.43750|0.44014|0.00058|0.43823|-0.19%|0.43809|-0.21%|42.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/56abb316eb)|0.43713|0.44006|0.00062|0.43815|-0.21%|0.43802|-0.23%|42.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56abb316eb)|0.42200|0.42380|0.00047|0.42264|-3.74%|0.42249|-3.76%|51.28 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71380|0.72968|0.00272|0.71553|0.00%|0.71509|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a63d0a49b0)|0.71340|0.71673|0.00067|0.71472|-0.11%|0.71468|-0.06%|38.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/56abb316eb)|0.71198|0.71533|0.00090|0.71340|-0.30%|0.71324|-0.26%|38.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56abb316eb)|0.68018|0.68357|0.00072|0.68176|-4.72%|0.68165|-4.68%|45.03 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57936|0.58178|0.00063|0.58040|0.00%|0.58029|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a63d0a49b0)|0.57877|0.58123|0.00062|0.57993|-0.08%|0.57985|-0.08%|43.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/56abb316eb)|0.57959|0.58135|0.00046|0.58033|-0.01%|0.58033|0.01%|43.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56abb316eb)|0.52378|0.52593|0.00050|0.52470|-9.60%|0.52471|-9.58%|61.05 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21566|0.21968|0.00081|0.21687|0.00%|0.21677|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a63d0a49b0)|0.21693|0.22219|0.00135|0.21864|0.81%|0.21827|0.69%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/56abb316eb)|0.21791|0.22070|0.00079|0.21924|1.09%|0.21939|1.21%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56abb316eb)|0.07674|0.07891|0.00052|0.07745|-64.29%|0.07731|-64.34%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34476|1.36644|0.00569|1.35192|0.00%|1.35022|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a63d0a49b0)|1.29000|1.30136|0.00336|1.29530|-4.19%|1.29492|-4.10%|20.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/56abb316eb)|1.29490|1.31450|0.00520|1.30398|-3.55%|1.30337|-3.47%|20.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56abb316eb)|0.54080|0.55861|0.00427|0.54776|-59.48%|0.54767|-59.44%|22.20 MB|
