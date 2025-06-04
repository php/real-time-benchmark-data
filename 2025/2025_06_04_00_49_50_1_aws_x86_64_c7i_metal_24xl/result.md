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
| OS            |Amazon Linux 2023.7.20250527|
| GCC           |11.5.0|
| Time          |2025-06-04 00:49:50 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43966|0.45383|0.00248|0.44075|0.00%|0.44032|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/36891a6775)|0.43955|0.44167|0.00043|0.44068|-0.01%|0.44064|0.07%|42.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/359bb6303d)|0.43996|0.44170|0.00043|0.44079|0.01%|0.44074|0.09%|42.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/359bb6303d)|0.42297|0.42443|0.00041|0.42351|-3.91%|0.42342|-3.84%|51.25 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71361|0.71625|0.00071|0.71476|0.00%|0.71468|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/36891a6775)|0.71057|0.71308|0.00062|0.71171|-0.43%|0.71179|-0.40%|37.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/359bb6303d)|0.70688|0.71416|0.00115|0.71156|-0.45%|0.71151|-0.44%|37.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/359bb6303d)|0.67974|0.68287|0.00078|0.68086|-4.74%|0.68067|-4.76%|45.01 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58113|0.58392|0.00058|0.58189|0.00%|0.58183|0.00%|43.09 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/36891a6775)|0.58116|0.58337|0.00057|0.58211|0.04%|0.58197|0.02%|43.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/359bb6303d)|0.58083|0.58506|0.00072|0.58223|0.06%|0.58214|0.05%|43.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/359bb6303d)|0.52511|0.52784|0.00061|0.52640|-9.54%|0.52642|-9.52%|61.03 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21556|0.21941|0.00100|0.21692|0.00%|0.21672|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/36891a6775)|0.21223|0.21686|0.00100|0.21361|-1.53%|0.21339|-1.54%|26.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/359bb6303d)|0.21270|0.21582|0.00084|0.21402|-1.34%|0.21400|-1.26%|26.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/359bb6303d)|0.07662|0.07819|0.00047|0.07750|-64.28%|0.07758|-64.20%|27.76 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33876|1.36596|0.00550|1.34977|0.00%|1.34921|0.00%|20.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/36891a6775)|1.29733|1.31305|0.00425|1.30453|-3.35%|1.30462|-3.30%|20.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/359bb6303d)|1.29888|1.31104|0.00362|1.30602|-3.24%|1.30723|-3.11%|20.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/359bb6303d)|0.55678|0.57094|0.00371|0.56439|-58.19%|0.56429|-58.18%|22.17 MB|
