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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-10-16 00:49:28 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43710|0.44587|0.00148|0.43817|0.00%|0.43789|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edf351ce6d)|0.43506|0.43719|0.00043|0.43583|-0.53%|0.43580|-0.48%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/097edc86c8)|0.43447|0.43674|0.00049|0.43554|-0.60%|0.43544|-0.56%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/097edc86c8)|0.42586|0.42988|0.00070|0.42650|-2.66%|0.42638|-2.63%|50.83 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71856|0.72195|0.00080|0.71988|0.00%|0.71984|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edf351ce6d)|0.71330|0.71743|0.00086|0.71447|-0.75%|0.71415|-0.79%|37.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/097edc86c8)|0.71325|0.72945|0.00284|0.71465|-0.73%|0.71406|-0.80%|37.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/097edc86c8)|0.68884|0.69102|0.00062|0.68973|-4.19%|0.68968|-4.19%|44.53 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58073|0.58251|0.00052|0.58155|0.00%|0.58147|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edf351ce6d)|0.57594|0.57768|0.00048|0.57700|-0.78%|0.57702|-0.77%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/097edc86c8)|0.57615|0.57826|0.00052|0.57692|-0.80%|0.57683|-0.80%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/097edc86c8)|0.52064|0.52258|0.00043|0.52155|-10.32%|0.52156|-10.30%|61.95 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21533|0.22109|0.00113|0.21655|0.00%|0.21634|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edf351ce6d)|0.21522|0.21725|0.00047|0.21617|-0.17%|0.21613|-0.10%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/097edc86c8)|0.21521|0.21915|0.00095|0.21654|-0.00%|0.21638|0.02%|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/097edc86c8)|0.07456|0.07634|0.00052|0.07547|-65.15%|0.07544|-65.13%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34405|1.36840|0.00635|1.35468|0.00%|1.35534|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edf351ce6d)|1.30209|1.31885|0.00384|1.30723|-3.50%|1.30657|-3.60%|20.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/097edc86c8)|1.29851|1.31201|0.00353|1.30612|-3.58%|1.30553|-3.67%|20.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/097edc86c8)|0.53408|0.54474|0.00271|0.53830|-60.26%|0.53799|-60.31%|21.78 MB|
