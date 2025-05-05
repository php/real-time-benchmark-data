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
| Time          |2025-05-05 00:49:53 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43783|0.44001|0.00050|0.43889|0.00%|0.43890|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0371d3965)|0.43566|0.43762|0.00045|0.43631|-0.59%|0.43621|-0.61%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ee1a641)|0.43634|0.43917|0.00069|0.43744|-0.33%|0.43722|-0.38%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ee1a641)|0.42417|0.42619|0.00041|0.42521|-3.12%|0.42531|-3.10%|50.84 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71312|0.72888|0.00275|0.71512|0.00%|0.71444|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0371d3965)|0.70625|0.70862|0.00057|0.70735|-1.09%|0.70739|-0.99%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ee1a641)|0.71019|0.72129|0.00258|0.71182|-0.46%|0.71091|-0.49%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ee1a641)|0.68281|0.68465|0.00048|0.68369|-4.40%|0.68357|-4.32%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58034|0.59052|0.00177|0.58159|0.00%|0.58115|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0371d3965)|0.58086|0.58323|0.00054|0.58210|0.09%|0.58209|0.16%|43.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ee1a641)|0.58120|0.58349|0.00058|0.58204|0.08%|0.58197|0.14%|43.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ee1a641)|0.52109|0.52402|0.00061|0.52219|-10.21%|0.52204|-10.17%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21541|0.21921|0.00083|0.21664|0.00%|0.21653|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0371d3965)|0.21782|0.22157|0.00095|0.21952|1.33%|0.21942|1.33%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ee1a641)|0.21438|0.21773|0.00065|0.21584|-0.37%|0.21573|-0.37%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ee1a641)|0.07568|0.07890|0.00086|0.07684|-64.53%|0.07658|-64.64%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34956|1.36799|0.00445|1.35737|0.00%|1.35712|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0371d3965)|1.29673|1.30868|0.00341|1.30141|-4.12%|1.30056|-4.17%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ee1a641)|1.28259|1.29616|0.00280|1.29032|-4.94%|1.29062|-4.90%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ee1a641)|0.52199|0.53810|0.00355|0.53048|-60.92%|0.53060|-60.90%|21.82 MB|
