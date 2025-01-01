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
| Time          |2025-01-01 00:50:09 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43866|0.44920|0.00141|0.43977|0.00%|0.43951|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/47e440019c)|0.43569|0.43809|0.00051|0.43640|-0.77%|0.43633|-0.72%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/90121f4056)|0.43578|0.43790|0.00052|0.43665|-0.71%|0.43660|-0.66%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/90121f4056)|0.42535|0.42706|0.00039|0.42621|-3.08%|0.42628|-3.01%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71306|0.71754|0.00093|0.71461|0.00%|0.71453|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/47e440019c)|0.70989|0.71320|0.00077|0.71120|-0.48%|0.71115|-0.47%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/90121f4056)|0.70835|0.71206|0.00066|0.71009|-0.63%|0.71001|-0.63%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/90121f4056)|0.68009|0.68335|0.00068|0.68162|-4.62%|0.68166|-4.60%|44.48 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58172|0.58703|0.00091|0.58304|0.00%|0.58287|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/47e440019c)|0.57355|0.58075|0.00106|0.57842|-0.79%|0.57854|-0.74%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/90121f4056)|0.57704|0.58056|0.00073|0.57821|-0.83%|0.57812|-0.81%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/90121f4056)|0.51915|0.52154|0.00053|0.52026|-10.77%|0.52022|-10.75%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21486|0.21885|0.00083|0.21625|0.00%|0.21621|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/47e440019c)|0.21545|0.21860|0.00069|0.21704|0.37%|0.21692|0.33%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/90121f4056)|0.21555|0.21847|0.00062|0.21676|0.24%|0.21668|0.22%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/90121f4056)|0.07406|0.07679|0.00077|0.07522|-65.22%|0.07495|-65.34%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34248|1.37030|0.00625|1.35364|0.00%|1.35308|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/47e440019c)|1.26091|1.28360|0.00488|1.27075|-6.12%|1.27123|-6.05%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/90121f4056)|1.26128|1.28119|0.00457|1.27032|-6.16%|1.27009|-6.13%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/90121f4056)|0.53103|0.55030|0.00408|0.54002|-60.11%|0.53945|-60.13%|21.66 MB|
