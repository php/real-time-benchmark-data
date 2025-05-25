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
| Time          |2025-05-25 00:50:01 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43762|0.45065|0.00224|0.43878|0.00%|0.43844|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|0.43716|0.44008|0.00072|0.43813|-0.15%|0.43797|-0.11%|42.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/ab80e092fb)|0.43940|0.44142|0.00049|0.44022|0.33%|0.44022|0.41%|42.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ab80e092fb)|0.42228|0.42430|0.00048|0.42315|-3.56%|0.42309|-3.50%|50.93 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71295|0.72899|0.00288|0.71459|0.00%|0.71392|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|0.71222|0.71585|0.00076|0.71354|-0.15%|0.71349|-0.06%|37.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/ab80e092fb)|0.71011|0.71363|0.00076|0.71159|-0.42%|0.71153|-0.34%|37.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ab80e092fb)|0.67546|0.67864|0.00079|0.67673|-5.30%|0.67670|-5.21%|44.68 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58112|0.58307|0.00048|0.58190|0.00%|0.58186|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|0.58049|0.58429|0.00084|0.58193|0.01%|0.58182|-0.01%|43.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/ab80e092fb)|0.58305|0.58558|0.00059|0.58401|0.36%|0.58392|0.36%|43.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ab80e092fb)|0.52559|0.52719|0.00041|0.52636|-9.54%|0.52637|-9.54%|60.77 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21515|0.21902|0.00085|0.21698|0.00%|0.21705|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|0.21835|0.22295|0.00123|0.22021|1.49%|0.22005|1.38%|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/ab80e092fb)|0.25898|0.27879|0.00639|0.27058|24.70%|0.27342|25.97%|26.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ab80e092fb)|0.07533|0.07783|0.00072|0.07665|-64.68%|0.07663|-64.70%|27.49 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34196|1.35943|0.00481|1.35089|0.00%|1.35180|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|1.28289|1.30600|0.00469|1.29106|-4.43%|1.29040|-4.54%|20.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/ab80e092fb)|1.31221|1.33675|0.00526|1.32448|-1.96%|1.32344|-2.10%|20.66 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ab80e092fb)|0.56254|0.57850|0.00443|0.57125|-57.71%|0.57179|-57.70%|21.91 MB|
