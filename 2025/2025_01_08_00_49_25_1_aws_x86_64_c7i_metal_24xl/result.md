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
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2025-01-08 00:49:25 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43860|0.44111|0.00052|0.43972|0.00%|0.43976|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c49f52b0d)|0.43806|0.44008|0.00043|0.43903|-0.16%|0.43903|-0.16%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/a091e52316)|0.43545|0.44291|0.00132|0.43645|-0.74%|0.43625|-0.80%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a091e52316)|0.42433|0.42647|0.00044|0.42510|-3.32%|0.42506|-3.34%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71350|0.71632|0.00075|0.71462|0.00%|0.71460|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c49f52b0d)|0.70998|0.71286|0.00065|0.71141|-0.45%|0.71138|-0.45%|37.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/a091e52316)|0.70592|0.70963|0.00075|0.70711|-1.05%|0.70696|-1.07%|37.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a091e52316)|0.68039|0.68286|0.00060|0.68168|-4.61%|0.68170|-4.60%|44.48 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58194|0.58475|0.00057|0.58289|0.00%|0.58276|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c49f52b0d)|0.57940|0.58276|0.00082|0.58055|-0.40%|0.58037|-0.41%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/a091e52316)|0.57427|0.58049|0.00139|0.57792|-0.85%|0.57835|-0.76%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a091e52316)|0.52032|0.52565|0.00184|0.52259|-10.34%|0.52151|-10.51%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21462|0.21845|0.00080|0.21596|0.00%|0.21599|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c49f52b0d)|0.21205|0.21639|0.00107|0.21373|-1.03%|0.21342|-1.19%|26.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/a091e52316)|0.21470|0.21910|0.00091|0.21603|0.04%|0.21580|-0.09%|26.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a091e52316)|0.07473|0.07769|0.00071|0.07614|-64.74%|0.07610|-64.77%|27.24 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34171|1.36444|0.00534|1.35266|0.00%|1.35303|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c49f52b0d)|1.25417|1.27383|0.00536|1.26209|-6.70%|1.26267|-6.68%|20.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/a091e52316)|1.30682|1.33295|0.00649|1.31928|-2.47%|1.31932|-2.49%|20.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a091e52316)|0.52937|0.55902|0.00634|0.54769|-59.51%|0.54876|-59.44%|21.66 MB|
