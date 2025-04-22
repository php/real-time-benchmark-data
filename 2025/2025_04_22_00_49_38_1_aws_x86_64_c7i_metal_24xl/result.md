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
| Time          |2025-04-22 00:49:38 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43844|0.43981|0.00037|0.43902|0.00%|0.43894|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/158181ff37)|0.43613|0.43785|0.00042|0.43698|-0.46%|0.43710|-0.42%|41.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/32a45769d1)|0.43621|0.43881|0.00069|0.43752|-0.34%|0.43732|-0.37%|41.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32a45769d1)|0.42353|0.42510|0.00035|0.42414|-3.39%|0.42410|-3.38%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71512|0.71801|0.00070|0.71607|0.00%|0.71588|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/158181ff37)|0.70878|0.71196|0.00073|0.71020|-0.82%|0.71021|-0.79%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/32a45769d1)|0.70984|0.71287|0.00074|0.71095|-0.72%|0.71084|-0.70%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32a45769d1)|0.68046|0.68239|0.00052|0.68118|-4.87%|0.68107|-4.86%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58077|0.59083|0.00170|0.58227|0.00%|0.58197|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/158181ff37)|0.57574|0.58188|0.00196|0.57820|-0.70%|0.57735|-0.79%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/32a45769d1)|0.58009|0.58193|0.00054|0.58099|-0.22%|0.58091|-0.18%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32a45769d1)|0.52025|0.52256|0.00055|0.52139|-10.45%|0.52132|-10.42%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21596|0.21872|0.00074|0.21701|0.00%|0.21680|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/158181ff37)|0.21840|0.22080|0.00067|0.21977|1.27%|0.21990|1.43%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/32a45769d1)|0.21688|0.22001|0.00084|0.21840|0.64%|0.21832|0.70%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32a45769d1)|0.07598|0.07920|0.00100|0.07710|-64.47%|0.07678|-64.59%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34000|1.36808|0.00595|1.35132|0.00%|1.35054|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/158181ff37)|1.29782|1.32376|0.00675|1.31267|-2.86%|1.31497|-2.63%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/32a45769d1)|1.30286|1.32018|0.00439|1.31068|-3.01%|1.31005|-3.00%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32a45769d1)|0.54373|0.56361|0.00510|0.55356|-59.04%|0.55430|-58.96%|21.82 MB|
