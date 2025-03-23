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
| Kernel        |6.1.129-138.220.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250303|
| GCC           |11.4.1|
| Time          |2025-03-23 00:49:44 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43844|0.44032|0.00044|0.43926|0.00%|0.43929|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8622362394)|0.43585|0.43717|0.00034|0.43635|-0.66%|0.43630|-0.68%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/a28fb52719)|0.43612|0.43845|0.00057|0.43701|-0.51%|0.43691|-0.54%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a28fb52719)|0.42600|0.42977|0.00061|0.42688|-2.82%|0.42680|-2.85%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71315|0.71569|0.00067|0.71430|0.00%|0.71430|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8622362394)|0.70839|0.71199|0.00095|0.70967|-0.65%|0.70941|-0.68%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/a28fb52719)|0.70869|0.71145|0.00066|0.70959|-0.66%|0.70946|-0.68%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a28fb52719)|0.67745|0.68121|0.00087|0.67882|-4.97%|0.67859|-5.00%|44.56 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58141|0.58364|0.00063|0.58243|0.00%|0.58235|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8622362394)|0.58148|0.58327|0.00047|0.58242|-0.00%|0.58250|0.02%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/a28fb52719)|0.58151|0.58300|0.00042|0.58225|-0.03%|0.58230|-0.01%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a28fb52719)|0.52107|0.52317|0.00045|0.52193|-10.39%|0.52179|-10.40%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21455|0.21856|0.00090|0.21592|0.00%|0.21576|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8622362394)|0.26302|0.28305|0.00521|0.27008|25.08%|0.27001|25.15%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/a28fb52719)|0.21280|0.21754|0.00114|0.21439|-0.71%|0.21440|-0.63%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a28fb52719)|0.07512|0.07743|0.00051|0.07620|-64.71%|0.07619|-64.69%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34110|1.36119|0.00409|1.34824|0.00%|1.34864|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8622362394)|1.25416|1.26399|0.00295|1.25848|-6.66%|1.25803|-6.72%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/a28fb52719)|1.25256|1.26822|0.00413|1.25904|-6.62%|1.25862|-6.68%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a28fb52719)|0.52958|0.56051|0.00716|0.54450|-59.61%|0.54297|-59.74%|21.80 MB|
