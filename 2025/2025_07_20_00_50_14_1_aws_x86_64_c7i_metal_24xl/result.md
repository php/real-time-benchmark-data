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
| OS            |Amazon Linux 2023.8.20250715|
| GCC           |11.5.0|
| Time          |2025-07-20 00:50:14 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44015|0.44913|0.00135|0.44265|0.00%|0.44259|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/189b933dd4)|0.43988|0.44200|0.00052|0.44101|-0.37%|0.44100|-0.36%|42.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/03a9f03822)|0.43933|0.44204|0.00069|0.44033|-0.53%|0.44024|-0.53%|42.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03a9f03822)|0.42549|0.42745|0.00046|0.42646|-3.66%|0.42648|-3.64%|51.52 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71450|0.71808|0.00096|0.71618|0.00%|0.71602|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/189b933dd4)|0.71461|0.71953|0.00108|0.71569|-0.07%|0.71533|-0.10%|38.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/03a9f03822)|0.71344|0.71907|0.00120|0.71565|-0.07%|0.71522|-0.11%|38.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03a9f03822)|0.68014|0.68422|0.00105|0.68193|-4.78%|0.68200|-4.75%|45.13 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58241|0.58582|0.00080|0.58357|0.00%|0.58353|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/189b933dd4)|0.58426|0.58636|0.00052|0.58532|0.30%|0.58540|0.32%|43.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/03a9f03822)|0.58393|0.58776|0.00083|0.58587|0.39%|0.58581|0.39%|43.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03a9f03822)|0.52461|0.52705|0.00058|0.52606|-9.86%|0.52615|-9.83%|62.17 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21409|0.21917|0.00128|0.21591|0.00%|0.21560|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/189b933dd4)|0.21559|0.21800|0.00063|0.21670|0.37%|0.21655|0.44%|26.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/03a9f03822)|0.21273|0.21713|0.00097|0.21413|-0.82%|0.21388|-0.80%|26.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03a9f03822)|0.07607|0.07921|0.00067|0.07699|-64.34%|0.07687|-64.35%|27.91 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41921|1.44067|0.00576|1.42937|0.00%|1.42851|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/189b933dd4)|1.32104|1.33309|0.00347|1.32641|-7.20%|1.32551|-7.21%|20.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/03a9f03822)|1.29152|1.30746|0.00391|1.29963|-9.08%|1.30070|-8.95%|20.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03a9f03822)|0.55245|0.56895|0.00363|0.56100|-60.75%|0.56008|-60.79%|22.35 MB|
