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
| Kernel        |6.1.132-147.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250414|
| GCC           |11.5.0|
| Time          |2025-04-19 00:49:42 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43825|0.45274|0.00248|0.43956|0.00%|0.43904|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|0.43751|0.43891|0.00030|0.43799|-0.36%|0.43806|-0.22%|41.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|0.43727|0.43938|0.00049|0.43807|-0.34%|0.43794|-0.25%|41.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.41709|0.42583|0.00128|0.42348|-3.66%|0.42361|-3.51%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71444|0.71856|0.00114|0.71593|0.00%|0.71563|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|0.70886|0.72101|0.00283|0.71065|-0.74%|0.70983|-0.81%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|0.70794|0.71130|0.00075|0.70925|-0.93%|0.70905|-0.92%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.67919|0.68242|0.00075|0.68059|-4.94%|0.68048|-4.91%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57972|0.58286|0.00076|0.58123|0.00%|0.58135|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|0.57806|0.58079|0.00064|0.57913|-0.36%|0.57907|-0.39%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|0.57786|0.58019|0.00058|0.57896|-0.39%|0.57889|-0.42%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.52008|0.52160|0.00047|0.52088|-10.38%|0.52097|-10.39%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21551|0.21920|0.00089|0.21689|0.00%|0.21674|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|0.21703|0.22080|0.00082|0.21888|0.92%|0.21879|0.94%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|0.21712|0.22247|0.00109|0.21848|0.73%|0.21830|0.72%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.07553|0.07755|0.00056|0.07638|-64.79%|0.07642|-64.74%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34585|1.36732|0.00518|1.35887|0.00%|1.35877|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8376904aeb)|1.32403|1.34935|0.00550|1.33711|-1.60%|1.33670|-1.62%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/8376904aeb)|1.32190|1.34864|0.00642|1.33743|-1.58%|1.33797|-1.53%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8376904aeb)|0.55772|0.58196|0.00541|0.56685|-58.29%|0.56723|-58.25%|21.82 MB|
