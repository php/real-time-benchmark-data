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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-02-22 00:49:21 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43792|0.43959|0.00039|0.43865|0.00%|0.43865|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0ec6413562)|0.43471|0.43820|0.00076|0.43545|-0.73%|0.43523|-0.78%|41.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/49d798abcc)|0.43500|0.43708|0.00047|0.43580|-0.65%|0.43566|-0.68%|41.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49d798abcc)|0.42291|0.42482|0.00042|0.42356|-3.44%|0.42344|-3.47%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71117|0.71528|0.00081|0.71287|0.00%|0.71290|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0ec6413562)|0.70469|0.70764|0.00067|0.70553|-1.03%|0.70538|-1.05%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/49d798abcc)|0.70246|0.70480|0.00058|0.70352|-1.31%|0.70347|-1.32%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49d798abcc)|0.66971|0.68053|0.00165|0.67787|-4.91%|0.67793|-4.91%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58018|0.58252|0.00062|0.58123|0.00%|0.58120|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0ec6413562)|0.57886|0.58120|0.00050|0.58002|-0.21%|0.58000|-0.21%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/49d798abcc)|0.57858|0.58004|0.00038|0.57935|-0.32%|0.57936|-0.32%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49d798abcc)|0.51858|0.52167|0.00058|0.51943|-10.63%|0.51936|-10.64%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21520|0.21837|0.00083|0.21622|0.00%|0.21605|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0ec6413562)|0.21342|0.21925|0.00118|0.21490|-0.61%|0.21469|-0.63%|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/49d798abcc)|0.21139|0.21400|0.00062|0.21289|-1.54%|0.21285|-1.48%|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49d798abcc)|0.07501|0.07757|0.00062|0.07605|-64.83%|0.07595|-64.85%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34159|1.36041|0.00497|1.35012|0.00%|1.35018|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0ec6413562)|1.25533|1.27547|0.00462|1.26371|-6.40%|1.26254|-6.49%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/49d798abcc)|1.25644|1.27385|0.00481|1.26286|-6.46%|1.26171|-6.55%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/49d798abcc)|0.55981|0.58262|0.00604|0.57144|-57.67%|0.57156|-57.67%|21.80 MB|
