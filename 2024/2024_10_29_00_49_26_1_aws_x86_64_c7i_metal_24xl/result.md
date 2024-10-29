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
| Time          |2024-10-29 00:49:26 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43813|0.44091|0.00054|0.43923|0.00%|0.43916|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e8a1781c52)|0.43622|0.43852|0.00054|0.43703|-0.50%|0.43697|-0.50%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb6212b073)|0.43587|0.43800|0.00046|0.43656|-0.61%|0.43653|-0.60%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb6212b073)|0.42585|0.42772|0.00041|0.42656|-2.88%|0.42654|-2.87%|50.83 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71920|0.72380|0.00095|0.72089|0.00%|0.72062|0.00%|37.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e8a1781c52)|0.71256|0.71590|0.00064|0.71375|-0.99%|0.71375|-0.95%|37.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb6212b073)|0.71252|0.71638|0.00071|0.71362|-1.01%|0.71356|-0.98%|37.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb6212b073)|0.69262|0.69582|0.00069|0.69376|-3.76%|0.69376|-3.73%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58180|0.58480|0.00072|0.58303|0.00%|0.58301|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e8a1781c52)|0.57435|0.58142|0.00222|0.57717|-1.00%|0.57589|-1.22%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb6212b073)|0.57977|0.58315|0.00064|0.58115|-0.32%|0.58112|-0.32%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb6212b073)|0.52309|0.52550|0.00057|0.52434|-10.07%|0.52441|-10.05%|61.95 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21452|0.21938|0.00110|0.21629|0.00%|0.21602|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e8a1781c52)|0.21546|0.21934|0.00099|0.21716|0.40%|0.21709|0.50%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb6212b073)|0.21531|0.21931|0.00080|0.21641|0.05%|0.21628|0.12%|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb6212b073)|0.07221|0.07615|0.00077|0.07471|-65.46%|0.07475|-65.39%|27.38 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34023|1.36013|0.00480|1.34865|0.00%|1.34874|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e8a1781c52)|1.34388|1.36531|0.00458|1.35423|0.41%|1.35447|0.42%|20.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb6212b073)|1.28183|1.30792|0.00486|1.29203|-4.20%|1.29148|-4.25%|20.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb6212b073)|0.52514|0.54676|0.00435|0.53547|-60.30%|0.53447|-60.37%|21.78 MB|
