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
| Time          |2024-12-31 00:49:24 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43875|0.44647|0.00135|0.43974|0.00%|0.43948|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ab38b52d3)|0.43559|0.43752|0.00046|0.43649|-0.74%|0.43640|-0.70%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/47e440019c)|0.43571|0.43776|0.00046|0.43671|-0.69%|0.43664|-0.65%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/47e440019c)|0.42570|0.42726|0.00037|0.42631|-3.05%|0.42626|-3.01%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71423|0.72965|0.00212|0.71563|0.00%|0.71517|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ab38b52d3)|0.70879|0.72447|0.00215|0.70997|-0.79%|0.70958|-0.78%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/47e440019c)|0.70954|0.71312|0.00064|0.71150|-0.58%|0.71147|-0.52%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/47e440019c)|0.68229|0.68469|0.00058|0.68322|-4.53%|0.68315|-4.48%|44.48 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58096|0.58346|0.00054|0.58219|0.00%|0.58217|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ab38b52d3)|0.57806|0.58083|0.00062|0.57932|-0.49%|0.57921|-0.51%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/47e440019c)|0.57323|0.57958|0.00155|0.57730|-0.84%|0.57774|-0.76%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/47e440019c)|0.51918|0.52133|0.00053|0.52006|-10.67%|0.52000|-10.68%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21552|0.21851|0.00072|0.21688|0.00%|0.21678|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ab38b52d3)|0.21600|0.22016|0.00101|0.21756|0.31%|0.21750|0.33%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/47e440019c)|0.21538|0.21929|0.00069|0.21681|-0.03%|0.21681|0.01%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/47e440019c)|0.07338|0.07678|0.00086|0.07494|-65.45%|0.07473|-65.53%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33731|1.36839|0.00665|1.35466|0.00%|1.35392|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ab38b52d3)|1.33267|1.35681|0.00513|1.34601|-0.64%|1.34587|-0.59%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/47e440019c)|1.25816|1.27939|0.00440|1.26992|-6.26%|1.26985|-6.21%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/47e440019c)|0.52722|0.54741|0.00329|0.53911|-60.20%|0.53909|-60.18%|21.66 MB|
