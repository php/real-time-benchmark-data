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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20241001|
| GCC           |11.4.1|
| Time          |2024-10-08 00:49:20 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43752|0.44024|0.00061|0.43860|0.00%|0.43849|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2d3990c50a)|0.43448|0.43649|0.00042|0.43542|-0.73%|0.43537|-0.71%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/edc94a8d21)|0.43655|0.44365|0.00121|0.43758|-0.23%|0.43752|-0.22%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edc94a8d21)|0.42768|0.42957|0.00040|0.42858|-2.29%|0.42858|-2.26%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71460|0.71615|0.00045|0.71530|0.00%|0.71522|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2d3990c50a)|0.70881|0.71303|0.00098|0.71010|-0.73%|0.70985|-0.75%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/edc94a8d21)|0.70980|0.71560|0.00104|0.71093|-0.61%|0.71067|-0.64%|37.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edc94a8d21)|0.68751|0.68997|0.00053|0.68855|-3.74%|0.68847|-3.74%|44.52 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58008|0.58259|0.00058|0.58122|0.00%|0.58122|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2d3990c50a)|0.57634|0.57845|0.00057|0.57747|-0.65%|0.57753|-0.64%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/edc94a8d21)|0.57787|0.58013|0.00056|0.57879|-0.42%|0.57878|-0.42%|42.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edc94a8d21)|0.51988|0.52201|0.00049|0.52092|-10.38%|0.52093|-10.37%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21508|0.21830|0.00075|0.21651|0.00%|0.21642|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2d3990c50a)|0.21546|0.21947|0.00091|0.21666|0.07%|0.21647|0.02%|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/edc94a8d21)|0.21617|0.21853|0.00059|0.21726|0.34%|0.21720|0.36%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edc94a8d21)|0.07433|0.07651|0.00067|0.07516|-65.29%|0.07494|-65.37%|27.30 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34246|1.36111|0.00547|1.35060|0.00%|1.35109|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2d3990c50a)|1.39824|1.42330|0.00721|1.40864|4.30%|1.40744|4.17%|20.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/edc94a8d21)|1.41801|1.43828|0.00511|1.42725|5.68%|1.42705|5.62%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edc94a8d21)|0.63725|0.66193|0.00610|0.64684|-52.11%|0.64492|-52.27%|21.71 MB|
