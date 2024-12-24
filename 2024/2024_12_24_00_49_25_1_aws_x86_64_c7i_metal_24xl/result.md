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
| Time          |2024-12-24 00:49:25 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43865|0.45018|0.00154|0.44006|0.00%|0.43983|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.43598|0.44310|0.00095|0.43710|-0.67%|0.43692|-0.66%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e9cde758e)|0.43667|0.43880|0.00045|0.43760|-0.56%|0.43759|-0.51%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e9cde758e)|0.42430|0.42665|0.00047|0.42515|-3.39%|0.42514|-3.34%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71351|0.71759|0.00088|0.71491|0.00%|0.71474|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.71059|0.71374|0.00074|0.71228|-0.37%|0.71228|-0.34%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e9cde758e)|0.71040|0.71424|0.00082|0.71175|-0.44%|0.71159|-0.44%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e9cde758e)|0.68338|0.68538|0.00048|0.68441|-4.27%|0.68437|-4.25%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58134|0.58412|0.00057|0.58239|0.00%|0.58223|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.57836|0.58025|0.00048|0.57900|-0.58%|0.57885|-0.58%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e9cde758e)|0.57377|0.57977|0.00154|0.57810|-0.74%|0.57853|-0.64%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e9cde758e)|0.51969|0.52230|0.00054|0.52128|-10.49%|0.52134|-10.46%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21511|0.21906|0.00094|0.21654|0.00%|0.21635|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.21599|0.22119|0.00114|0.21795|0.65%|0.21776|0.65%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e9cde758e)|0.21605|0.22039|0.00096|0.21739|0.39%|0.21721|0.39%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e9cde758e)|0.07364|0.07752|0.00088|0.07555|-65.11%|0.07565|-65.03%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34141|1.36619|0.00565|1.35241|0.00%|1.35195|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf5e6c5f2d)|1.34007|1.37026|0.00701|1.35489|0.18%|1.35464|0.20%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e9cde758e)|1.34475|1.36741|0.00565|1.35598|0.26%|1.35616|0.31%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e9cde758e)|0.52728|0.54455|0.00421|0.53678|-60.31%|0.53723|-60.26%|21.65 MB|
