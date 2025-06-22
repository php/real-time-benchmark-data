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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-22 00:50:08 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44038|0.44359|0.00068|0.44127|0.00%|0.44125|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89be689f77)|0.44101|0.44396|0.00061|0.44186|0.14%|0.44182|0.13%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/37549e4563)|0.43992|0.44303|0.00087|0.44089|-0.08%|0.44068|-0.13%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/37549e4563)|0.42443|0.42616|0.00035|0.42521|-3.64%|0.42513|-3.65%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71583|0.71910|0.00069|0.71685|0.00%|0.71674|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89be689f77)|0.71167|0.71596|0.00101|0.71343|-0.48%|0.71340|-0.47%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/37549e4563)|0.71111|0.72469|0.00334|0.71377|-0.43%|0.71284|-0.54%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/37549e4563)|0.67841|0.68203|0.00084|0.67999|-5.14%|0.67992|-5.14%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58118|0.58351|0.00054|0.58229|0.00%|0.58219|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89be689f77)|0.57934|0.58245|0.00069|0.58060|-0.29%|0.58050|-0.29%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/37549e4563)|0.57847|0.58099|0.00059|0.57942|-0.49%|0.57935|-0.49%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/37549e4563)|0.52334|0.52519|0.00051|0.52412|-9.99%|0.52415|-9.97%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21539|0.21920|0.00095|0.21712|0.00%|0.21695|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89be689f77)|0.21328|0.21681|0.00088|0.21452|-1.20%|0.21424|-1.25%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/37549e4563)|0.21282|0.21617|0.00097|0.21410|-1.39%|0.21394|-1.39%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/37549e4563)|0.07571|0.07803|0.00064|0.07657|-64.73%|0.07646|-64.76%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34515|1.36691|0.00584|1.35572|0.00%|1.35543|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89be689f77)|1.29407|1.31295|0.00485|1.30508|-3.74%|1.30522|-3.70%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/37549e4563)|1.28857|1.30638|0.00437|1.29693|-4.34%|1.29604|-4.38%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/37549e4563)|0.55209|0.56520|0.00384|0.55800|-58.84%|0.55787|-58.84%|22.23 MB|
