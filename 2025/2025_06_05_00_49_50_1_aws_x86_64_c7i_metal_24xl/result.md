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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250527|
| GCC           |11.5.0|
| Time          |2025-06-05 00:49:50 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43964|0.44230|0.00058|0.44075|0.00%|0.44076|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359bb6303d)|0.44004|0.44227|0.00056|0.44121|0.11%|0.44129|0.12%|42.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f91462019)|0.43933|0.44241|0.00067|0.44038|-0.08%|0.44024|-0.12%|42.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f91462019)|0.42327|0.42709|0.00064|0.42444|-3.70%|0.42437|-3.72%|51.18 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71334|0.71764|0.00087|0.71450|0.00%|0.71430|0.00%|37.53 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359bb6303d)|0.71006|0.71264|0.00065|0.71132|-0.45%|0.71135|-0.41%|37.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f91462019)|0.70885|0.72188|0.00227|0.71095|-0.50%|0.71046|-0.54%|37.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f91462019)|0.67685|0.68069|0.00081|0.67844|-5.05%|0.67832|-5.04%|44.94 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58053|0.58360|0.00066|0.58168|0.00%|0.58158|0.00%|43.09 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359bb6303d)|0.58071|0.58282|0.00052|0.58153|-0.03%|0.58142|-0.03%|43.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f91462019)|0.57874|0.58969|0.00185|0.58043|-0.22%|0.57997|-0.28%|43.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f91462019)|0.52794|0.53000|0.00057|0.52887|-9.08%|0.52878|-9.08%|61.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21563|0.21837|0.00078|0.21680|0.00%|0.21688|0.00%|26.25 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359bb6303d)|0.21256|0.21557|0.00088|0.21375|-1.41%|0.21357|-1.53%|26.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f91462019)|0.21212|0.21700|0.00123|0.21360|-1.48%|0.21317|-1.71%|26.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f91462019)|0.07610|0.07959|0.00090|0.07730|-64.35%|0.07705|-64.47%|27.69 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34288|1.36225|0.00471|1.35062|0.00%|1.35051|0.00%|20.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/359bb6303d)|1.29441|1.31217|0.00460|1.30330|-3.50%|1.30277|-3.54%|20.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f91462019)|1.29445|1.31612|0.00595|1.30254|-3.56%|1.30130|-3.64%|20.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f91462019)|0.54893|0.57411|0.00553|0.56403|-58.24%|0.56406|-58.23%|22.11 MB|
