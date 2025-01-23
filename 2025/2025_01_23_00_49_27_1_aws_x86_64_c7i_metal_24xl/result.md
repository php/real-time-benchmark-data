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
| OS            |Amazon Linux 2023.6.20250115|
| GCC           |11.4.1|
| Time          |2025-01-23 00:49:27 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43792|0.43964|0.00041|0.43878|0.00%|0.43877|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3337f22eb1)|0.43619|0.43861|0.00060|0.43721|-0.36%|0.43700|-0.40%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.43647|0.44333|0.00098|0.43749|-0.29%|0.43727|-0.34%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.42025|0.42746|0.00096|0.42646|-2.81%|0.42652|-2.79%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71219|0.71630|0.00078|0.71379|0.00%|0.71374|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3337f22eb1)|0.71202|0.71635|0.00086|0.71338|-0.06%|0.71330|-0.06%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.71171|0.71412|0.00065|0.71281|-0.14%|0.71288|-0.12%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.67821|0.68759|0.00130|0.68598|-3.90%|0.68610|-3.87%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57891|0.58331|0.00109|0.58101|0.00%|0.58131|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3337f22eb1)|0.57588|0.58091|0.00096|0.57716|-0.66%|0.57696|-0.75%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.57594|0.58052|0.00076|0.57709|-0.67%|0.57695|-0.75%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.51823|0.52431|0.00084|0.51948|-10.59%|0.51942|-10.65%|62.49 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21489|0.21904|0.00084|0.21642|0.00%|0.21633|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3337f22eb1)|0.21638|0.22236|0.00121|0.21916|1.27%|0.21913|1.30%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.21511|0.21795|0.00067|0.21628|-0.07%|0.21615|-0.08%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.07356|0.07820|0.00075|0.07585|-64.95%|0.07578|-64.97%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34615|1.37101|0.00605|1.35736|0.00%|1.35675|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3337f22eb1)|1.32183|1.34454|0.00509|1.33027|-2.00%|1.33035|-1.95%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cbf4e7f)|1.33396|1.36043|0.00598|1.34354|-1.02%|1.34355|-0.97%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.53769|0.56035|0.00486|0.55027|-59.46%|0.55065|-59.41%|21.72 MB|
