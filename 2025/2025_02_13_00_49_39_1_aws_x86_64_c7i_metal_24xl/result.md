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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250203|
| GCC           |11.4.1|
| Time          |2025-02-13 00:49:39 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43927|0.44174|0.00054|0.44024|0.00%|0.44014|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5acff0e61d)|0.43760|0.44580|0.00113|0.43863|-0.36%|0.43849|-0.37%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/65d433161a)|0.43587|0.44490|0.00119|0.43720|-0.69%|0.43701|-0.71%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65d433161a)|0.42725|0.43331|0.00084|0.42803|-2.77%|0.42792|-2.78%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71358|0.71724|0.00083|0.71529|0.00%|0.71524|0.00%|37.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5acff0e61d)|0.71081|0.72704|0.00221|0.71240|-0.40%|0.71204|-0.45%|37.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/65d433161a)|0.71209|0.71523|0.00071|0.71315|-0.30%|0.71299|-0.32%|37.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65d433161a)|0.68406|0.68761|0.00079|0.68568|-4.14%|0.68560|-4.14%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58177|0.58530|0.00058|0.58264|0.00%|0.58253|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5acff0e61d)|0.57683|0.58326|0.00179|0.58133|-0.22%|0.58183|-0.12%|42.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/65d433161a)|0.58025|0.58188|0.00041|0.58126|-0.24%|0.58125|-0.22%|42.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65d433161a)|0.52234|0.52475|0.00051|0.52342|-10.17%|0.52336|-10.16%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21487|0.21929|0.00089|0.21618|0.00%|0.21608|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5acff0e61d)|0.21230|0.21716|0.00108|0.21417|-0.93%|0.21398|-0.97%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/65d433161a)|0.21727|0.22304|0.00105|0.22005|1.79%|0.22009|1.85%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65d433161a)|0.07375|0.07717|0.00078|0.07518|-65.22%|0.07510|-65.25%|27.33 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33706|1.36584|0.00627|1.34866|0.00%|1.34849|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5acff0e61d)|1.25136|1.28605|0.00620|1.26998|-5.83%|1.27040|-5.79%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/65d433161a)|1.28287|1.29668|0.00301|1.28993|-4.35%|1.28993|-4.34%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/65d433161a)|0.54643|0.56580|0.00530|0.55662|-58.73%|0.55730|-58.67%|21.75 MB|
