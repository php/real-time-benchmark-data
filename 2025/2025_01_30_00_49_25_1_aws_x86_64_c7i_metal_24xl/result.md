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
| Kernel        |6.1.124-134.200.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250128|
| GCC           |11.4.1|
| Time          |2025-01-30 00:49:25 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44042|0.44765|0.00129|0.44144|0.00%|0.44122|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f4579af85)|0.44034|0.44270|0.00054|0.44148|0.01%|0.44144|0.05%|41.84 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa7c67d622)|0.43887|0.44100|0.00049|0.43969|-0.40%|0.43961|-0.36%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa7c67d622)|0.42792|0.43030|0.00054|0.42873|-2.88%|0.42870|-2.84%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70742|0.71765|0.00138|0.71568|0.00%|0.71573|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f4579af85)|0.71430|0.71701|0.00078|0.71561|-0.01%|0.71555|-0.02%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa7c67d622)|0.70763|0.71252|0.00094|0.71006|-0.79%|0.71001|-0.80%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa7c67d622)|0.68213|0.68583|0.00073|0.68387|-4.44%|0.68393|-4.44%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58152|0.59241|0.00147|0.58293|0.00%|0.58269|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f4579af85)|0.58291|0.58486|0.00047|0.58373|0.14%|0.58372|0.18%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa7c67d622)|0.57853|0.58085|0.00046|0.57962|-0.57%|0.57961|-0.53%|42.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa7c67d622)|0.52065|0.52815|0.00108|0.52242|-10.38%|0.52223|-10.37%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21533|0.21766|0.00064|0.21640|0.00%|0.21636|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f4579af85)|0.21278|0.21768|0.00090|0.21408|-1.07%|0.21392|-1.13%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa7c67d622)|0.21545|0.21986|0.00105|0.21704|0.30%|0.21694|0.27%|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa7c67d622)|0.07411|0.07756|0.00081|0.07543|-65.14%|0.07546|-65.12%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33603|1.36809|0.00663|1.35195|0.00%|1.35205|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f4579af85)|1.27667|1.29927|0.00451|1.28884|-4.67%|1.28891|-4.67%|20.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/fa7c67d622)|1.33354|1.35658|0.00611|1.34418|-0.57%|1.34465|-0.55%|20.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fa7c67d622)|0.51927|0.54458|0.00551|0.53034|-60.77%|0.53028|-60.78%|21.72 MB|
