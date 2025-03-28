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
| Kernel        |6.1.130-139.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250317|
| GCC           |11.5.0|
| Time          |2025-03-28 00:49:33 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43861|0.44834|0.00167|0.43988|0.00%|0.43959|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0006522211)|0.43896|0.44048|0.00035|0.43951|-0.09%|0.43947|-0.03%|41.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/0943b8b7eb)|0.43640|0.43801|0.00040|0.43713|-0.62%|0.43707|-0.57%|41.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0943b8b7eb)|0.42673|0.42878|0.00048|0.42754|-2.80%|0.42747|-2.76%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71286|0.71556|0.00064|0.71447|0.00%|0.71447|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0006522211)|0.70899|0.71244|0.00078|0.71047|-0.56%|0.71034|-0.58%|37.60 MB|
|[PHP - master](https://github.com/php/php-src/commit/0943b8b7eb)|0.70638|0.71034|0.00083|0.70766|-0.95%|0.70751|-0.97%|37.60 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0943b8b7eb)|0.67968|0.68254|0.00068|0.68102|-4.68%|0.68098|-4.69%|44.57 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58111|0.58248|0.00036|0.58174|0.00%|0.58170|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0006522211)|0.57942|0.64576|0.02469|0.62958|8.22%|0.64144|10.27%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/0943b8b7eb)|0.63636|0.64530|0.00252|0.64044|10.09%|0.64011|10.04%|43.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0943b8b7eb)|0.52055|0.58920|0.03090|0.55442|-4.70%|0.57592|-0.99%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21500|0.21900|0.00101|0.21642|0.00%|0.21600|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0006522211)|0.21585|0.22019|0.00104|0.21805|0.76%|0.21854|1.18%|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/0943b8b7eb)|0.21665|0.22454|0.00170|0.21906|1.22%|0.21874|1.27%|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0943b8b7eb)|0.07525|0.07766|0.00061|0.07634|-64.73%|0.07628|-64.68%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34102|1.36748|0.00631|1.35241|0.00%|1.35203|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0006522211)|1.26015|1.27366|0.00393|1.26640|-6.36%|1.26586|-6.37%|20.59 MB|
|[PHP - master](https://github.com/php/php-src/commit/0943b8b7eb)|1.28247|1.30034|0.00401|1.29315|-4.38%|1.29289|-4.37%|20.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0943b8b7eb)|0.53248|0.55686|0.00480|0.54379|-59.79%|0.54417|-59.75%|21.80 MB|
