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
| Kernel        |6.1.134-150.224.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250428|
| GCC           |11.5.0|
| Time          |2025-05-13 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43791|0.44585|0.00132|0.43910|0.00%|0.43892|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/331ac35f58)|0.43765|0.44088|0.00070|0.43895|-0.03%|0.43888|-0.01%|42.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|0.43866|0.44094|0.00047|0.43939|0.07%|0.43935|0.10%|42.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.42505|0.42662|0.00041|0.42582|-3.02%|0.42582|-2.99%|50.87 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71438|0.71771|0.00077|0.71564|0.00%|0.71543|0.00%|37.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/331ac35f58)|0.71003|0.72164|0.00208|0.71163|-0.56%|0.71098|-0.62%|37.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|0.70883|0.72210|0.00302|0.71055|-0.71%|0.70963|-0.81%|37.66 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.68444|0.68684|0.00063|0.68549|-4.21%|0.68540|-4.20%|44.62 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58042|0.58231|0.00046|0.58165|0.00%|0.58177|0.00%|43.07 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/331ac35f58)|0.58472|0.58651|0.00049|0.58566|0.69%|0.58558|0.65%|43.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|0.57989|0.58418|0.00084|0.58192|0.05%|0.58189|0.02%|43.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.52030|0.52362|0.00064|0.52237|-10.19%|0.52235|-10.21%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21502|0.21933|0.00105|0.21697|0.00%|0.21664|0.00%|26.23 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/331ac35f58)|0.21359|0.21749|0.00114|0.21504|-0.89%|0.21456|-0.96%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|0.21678|0.22284|0.00132|0.21868|0.79%|0.21859|0.90%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.07550|0.07828|0.00077|0.07682|-64.59%|0.07673|-64.58%|27.42 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34313|1.36020|0.00492|1.35286|0.00%|1.35289|0.00%|20.49 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/331ac35f58)|1.26635|1.28891|0.00598|1.27908|-5.45%|1.27978|-5.40%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|1.29008|1.30821|0.00417|1.30008|-3.90%|1.30015|-3.90%|20.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.54860|0.56532|0.00451|0.55849|-58.72%|0.55932|-58.66%|21.84 MB|
