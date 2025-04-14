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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-14 00:49:45 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43853|0.44846|0.00171|0.43947|0.00%|0.43920|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1684c52a88)|0.43966|0.44169|0.00047|0.44048|0.23%|0.44052|0.30%|41.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8b3328996)|0.43969|0.44386|0.00074|0.44063|0.27%|0.44050|0.30%|41.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8b3328996)|0.42739|0.42933|0.00042|0.42792|-2.63%|0.42782|-2.59%|50.87 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71188|0.71562|0.00091|0.71331|0.00%|0.71310|0.00%|37.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1684c52a88)|0.70520|0.71038|0.00087|0.70886|-0.62%|0.70887|-0.59%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8b3328996)|0.70760|0.71083|0.00078|0.70871|-0.65%|0.70861|-0.63%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8b3328996)|0.67235|0.68161|0.00152|0.68009|-4.66%|0.68024|-4.61%|44.61 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58102|0.58348|0.00063|0.58212|0.00%|0.58207|0.00%|43.07 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1684c52a88)|0.57946|0.58253|0.00077|0.58105|-0.18%|0.58114|-0.16%|43.04 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8b3328996)|0.57964|0.58247|0.00066|0.58082|-0.22%|0.58073|-0.23%|43.04 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8b3328996)|0.52204|0.52391|0.00042|0.52272|-10.20%|0.52270|-10.20%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21609|0.21943|0.00080|0.21795|0.00%|0.21785|0.00%|26.23 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1684c52a88)|0.21659|0.22370|0.00132|0.21905|0.50%|0.21890|0.48%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8b3328996)|0.21625|0.21998|0.00097|0.21785|-0.05%|0.21766|-0.09%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8b3328996)|0.07497|0.07887|0.00086|0.07647|-64.91%|0.07636|-64.95%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33595|1.36366|0.00647|1.34679|0.00%|1.34586|0.00%|20.49 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1684c52a88)|1.31304|1.33614|0.00544|1.32427|-1.67%|1.32399|-1.62%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8b3328996)|1.31003|1.32842|0.00485|1.32033|-1.96%|1.31960|-1.95%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8b3328996)|0.53964|0.55650|0.00421|0.54730|-59.36%|0.54726|-59.34%|21.83 MB|
