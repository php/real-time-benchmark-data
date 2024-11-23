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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241121|
| GCC           |11.4.1|
| Time          |2024-11-23 00:50:28 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43873|0.44122|0.00050|0.43950|0.00%|0.43941|0.00%|41.83 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ccda20b8d1)|0.43639|0.43844|0.00044|0.43738|-0.48%|0.43732|-0.48%|41.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.43644|0.43817|0.00039|0.43718|-0.53%|0.43714|-0.52%|41.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.42357|0.42501|0.00035|0.42426|-3.47%|0.42427|-3.45%|50.76 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71188|0.71593|0.00081|0.71346|0.00%|0.71347|0.00%|37.35 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ccda20b8d1)|0.70538|0.71010|0.00106|0.70708|-0.89%|0.70678|-0.94%|37.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.70581|0.71031|0.00098|0.70742|-0.85%|0.70718|-0.88%|37.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.68016|0.68365|0.00070|0.68140|-4.49%|0.68127|-4.51%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58044|0.58342|0.00062|0.58191|0.00%|0.58194|0.00%|42.97 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ccda20b8d1)|0.57595|0.58005|0.00096|0.57797|-0.68%|0.57801|-0.67%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.57640|0.57887|0.00052|0.57745|-0.77%|0.57736|-0.79%|42.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.51716|0.52376|0.00161|0.52134|-10.41%|0.52181|-10.33%|60.61 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21463|0.21920|0.00098|0.21636|0.00%|0.21628|0.00%|26.14 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ccda20b8d1)|0.21452|0.21858|0.00086|0.21610|-0.12%|0.21611|-0.08%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.21486|0.21861|0.00077|0.21628|-0.04%|0.21610|-0.09%|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.07269|0.07738|0.00094|0.07522|-65.24%|0.07517|-65.25%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34016|1.36967|0.00639|1.35173|0.00%|1.35155|0.00%|20.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ccda20b8d1)|1.27198|1.30448|0.00777|1.28864|-4.67%|1.28893|-4.63%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|1.27461|1.30405|0.00730|1.28939|-4.61%|1.28891|-4.63%|20.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.51751|0.54307|0.00494|0.53054|-60.75%|0.53102|-60.71%|21.71 MB|
