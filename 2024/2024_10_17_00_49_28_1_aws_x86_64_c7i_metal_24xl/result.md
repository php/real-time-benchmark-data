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
| Time          |2024-10-17 00:49:28 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43979|0.45053|0.00144|0.44122|0.00%|0.44094|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/097edc86c8)|0.43811|0.44078|0.00060|0.43918|-0.46%|0.43908|-0.42%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/3351daee61)|0.43836|0.44195|0.00059|0.43955|-0.38%|0.43946|-0.33%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3351daee61)|0.42928|0.43225|0.00053|0.43011|-2.52%|0.43006|-2.47%|50.83 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.72294|0.72639|0.00085|0.72427|0.00%|0.72415|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/097edc86c8)|0.71741|0.72130|0.00080|0.71901|-0.73%|0.71880|-0.74%|37.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/3351daee61)|0.71741|0.72249|0.00094|0.71905|-0.72%|0.71893|-0.72%|37.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3351daee61)|0.69678|0.70041|0.00075|0.69805|-3.62%|0.69796|-3.62%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58155|0.58461|0.00067|0.58333|0.00%|0.58329|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/097edc86c8)|0.57743|0.58168|0.00063|0.57921|-0.71%|0.57917|-0.71%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/3351daee61)|0.57855|0.58148|0.00062|0.57973|-0.62%|0.57973|-0.61%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3351daee61)|0.52241|0.52485|0.00053|0.52350|-10.26%|0.52348|-10.25%|61.95 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21532|0.22025|0.00108|0.21674|0.00%|0.21646|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/097edc86c8)|0.21559|0.21875|0.00073|0.21708|0.16%|0.21703|0.26%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/3351daee61)|0.21512|0.22068|0.00104|0.21662|-0.05%|0.21639|-0.03%|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3351daee61)|0.07393|0.07718|0.00064|0.07526|-65.27%|0.07528|-65.22%|27.38 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33688|1.36358|0.00594|1.34919|0.00%|1.34953|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/097edc86c8)|1.30093|1.32095|0.00383|1.30876|-3.00%|1.30837|-3.05%|20.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/3351daee61)|1.29851|1.31677|0.00423|1.30714|-3.12%|1.30675|-3.17%|20.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3351daee61)|0.53514|0.55632|0.00409|0.54236|-59.80%|0.54254|-59.80%|21.78 MB|
