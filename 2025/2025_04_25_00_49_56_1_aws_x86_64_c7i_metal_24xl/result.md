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
| Time          |2025-04-25 00:49:56 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43823|0.44247|0.00073|0.43901|0.00%|0.43883|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3244351d)|0.43815|0.44097|0.00058|0.43901|0.00%|0.43887|0.01%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/6c09c167ef)|0.43881|0.44088|0.00055|0.43966|0.15%|0.43954|0.16%|41.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6c09c167ef)|0.42301|0.42490|0.00045|0.42359|-3.51%|0.42351|-3.49%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71523|0.73058|0.00263|0.71703|0.00%|0.71650|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3244351d)|0.71128|0.71487|0.00092|0.71251|-0.63%|0.71236|-0.58%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/6c09c167ef)|0.70916|0.71262|0.00083|0.71042|-0.92%|0.71029|-0.87%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6c09c167ef)|0.67980|0.68245|0.00072|0.68082|-5.05%|0.68071|-4.99%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57995|0.58354|0.00085|0.58171|0.00%|0.58172|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3244351d)|0.57975|0.58237|0.00056|0.58104|-0.12%|0.58097|-0.13%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/6c09c167ef)|0.57781|0.58041|0.00059|0.57914|-0.44%|0.57904|-0.46%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6c09c167ef)|0.52051|0.52254|0.00059|0.52180|-10.30%|0.52212|-10.25%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21543|0.22120|0.00124|0.21735|0.00%|0.21703|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3244351d)|0.21743|0.22079|0.00081|0.21864|0.59%|0.21863|0.74%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/6c09c167ef)|0.21518|0.21784|0.00059|0.21604|-0.60%|0.21604|-0.46%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6c09c167ef)|0.07542|0.07749|0.00060|0.07638|-64.86%|0.07637|-64.81%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33945|1.35672|0.00410|1.34840|0.00%|1.34829|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3244351d)|1.31245|1.33246|0.00546|1.32336|-1.86%|1.32231|-1.93%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/6c09c167ef)|1.26705|1.28242|0.00430|1.27538|-5.42%|1.27490|-5.44%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6c09c167ef)|0.55434|0.56410|0.00276|0.55944|-58.51%|0.55982|-58.48%|21.82 MB|
