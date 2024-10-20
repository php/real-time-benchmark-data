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
| Time          |2024-10-20 00:49:36 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43994|0.44195|0.00046|0.44083|0.00%|0.44089|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a00c73458f)|0.43818|0.44054|0.00049|0.43925|-0.36%|0.43925|-0.37%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/d19fdaa4b7)|0.43839|0.44093|0.00058|0.43951|-0.30%|0.43952|-0.31%|41.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d19fdaa4b7)|0.42806|0.43031|0.00047|0.42928|-2.62%|0.42931|-2.62%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.72154|0.72640|0.00098|0.72334|0.00%|0.72322|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a00c73458f)|0.71880|0.73624|0.00244|0.72060|-0.38%|0.72013|-0.43%|37.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/d19fdaa4b7)|0.71794|0.72143|0.00078|0.71959|-0.52%|0.71946|-0.52%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d19fdaa4b7)|0.69349|0.69728|0.00077|0.69526|-3.88%|0.69526|-3.87%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58298|0.58497|0.00049|0.58384|0.00%|0.58383|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a00c73458f)|0.58011|0.58246|0.00064|0.58113|-0.46%|0.58098|-0.49%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/d19fdaa4b7)|0.58019|0.58167|0.00034|0.58096|-0.49%|0.58091|-0.50%|42.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d19fdaa4b7)|0.52501|0.52741|0.00046|0.52602|-9.90%|0.52603|-9.90%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21468|0.22002|0.00117|0.21664|0.00%|0.21638|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a00c73458f)|0.21615|0.21993|0.00083|0.21739|0.35%|0.21720|0.38%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/d19fdaa4b7)|0.21570|0.21926|0.00096|0.21748|0.39%|0.21749|0.52%|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d19fdaa4b7)|0.07397|0.07791|0.00075|0.07569|-65.06%|0.07563|-65.05%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33530|1.35664|0.00500|1.34615|0.00%|1.34587|0.00%|20.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a00c73458f)|1.26942|1.28913|0.00557|1.27907|-4.98%|1.27846|-5.01%|20.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/d19fdaa4b7)|1.27188|1.29430|0.00474|1.28321|-4.68%|1.28379|-4.61%|20.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d19fdaa4b7)|0.51596|0.53027|0.00332|0.52356|-61.11%|0.52310|-61.13%|21.71 MB|
