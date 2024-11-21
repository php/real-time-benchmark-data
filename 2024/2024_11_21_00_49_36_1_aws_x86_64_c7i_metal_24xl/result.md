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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241111|
| GCC           |11.4.1|
| Time          |2024-11-21 00:49:36 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43999|0.44239|0.00051|0.44106|0.00%|0.44104|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba0ecaa107)|0.43788|0.44522|0.00105|0.43914|-0.44%|0.43899|-0.46%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/91f0b3bc04)|0.43748|0.44037|0.00057|0.43866|-0.54%|0.43870|-0.53%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/91f0b3bc04)|0.42709|0.42921|0.00052|0.42801|-2.96%|0.42796|-2.97%|50.74 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71420|0.71868|0.00093|0.71599|0.00%|0.71574|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba0ecaa107)|0.71212|0.71680|0.00126|0.71372|-0.32%|0.71341|-0.33%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/91f0b3bc04)|0.70309|0.71509|0.00153|0.71278|-0.45%|0.71297|-0.39%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/91f0b3bc04)|0.68244|0.68677|0.00073|0.68500|-4.33%|0.68502|-4.29%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58084|0.58421|0.00071|0.58242|0.00%|0.58238|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba0ecaa107)|0.57726|0.64515|0.02923|0.59868|2.79%|0.57887|-0.60%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/91f0b3bc04)|0.58056|0.58298|0.00055|0.58160|-0.14%|0.58149|-0.15%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/91f0b3bc04)|0.52185|0.52379|0.00045|0.52291|-10.22%|0.52300|-10.20%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21442|0.21885|0.00095|0.21632|0.00%|0.21617|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba0ecaa107)|0.21548|0.21965|0.00116|0.21729|0.44%|0.21707|0.41%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/91f0b3bc04)|0.21184|0.21575|0.00101|0.21335|-1.37%|0.21318|-1.39%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/91f0b3bc04)|0.07420|0.07746|0.00073|0.07553|-65.09%|0.07543|-65.11%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33947|1.36274|0.00498|1.35265|0.00%|1.35271|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba0ecaa107)|1.27789|1.30843|0.00602|1.28904|-4.70%|1.28873|-4.73%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/91f0b3bc04)|1.27675|1.30009|0.00575|1.28819|-4.77%|1.28764|-4.81%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/91f0b3bc04)|0.53855|0.56594|0.00612|0.55024|-59.32%|0.54943|-59.38%|21.69 MB|
