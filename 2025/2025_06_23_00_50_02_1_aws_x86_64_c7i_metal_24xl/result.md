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
| Time          |2025-06-23 00:50:02 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44062|0.44283|0.00046|0.44173|0.00%|0.44173|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/37549e4563)|0.44093|0.44323|0.00055|0.44192|0.04%|0.44180|0.02%|42.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/ddd33fd7e4)|0.44031|0.44325|0.00059|0.44135|-0.08%|0.44130|-0.10%|42.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ddd33fd7e4)|0.42480|0.42693|0.00049|0.42573|-3.62%|0.42562|-3.65%|51.33 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71500|0.71849|0.00087|0.71690|0.00%|0.71691|0.00%|37.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/37549e4563)|0.71050|0.71465|0.00085|0.71222|-0.65%|0.71211|-0.67%|38.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/ddd33fd7e4)|0.71200|0.71529|0.00077|0.71302|-0.54%|0.71287|-0.56%|38.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ddd33fd7e4)|0.68071|0.68327|0.00064|0.68188|-4.89%|0.68184|-4.89%|45.01 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58130|0.58413|0.00067|0.58250|0.00%|0.58235|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/37549e4563)|0.57923|0.58296|0.00071|0.58022|-0.39%|0.58003|-0.40%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/ddd33fd7e4)|0.57945|0.58207|0.00055|0.58050|-0.34%|0.58055|-0.31%|43.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ddd33fd7e4)|0.52390|0.52594|0.00053|0.52499|-9.87%|0.52489|-9.87%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21616|0.22037|0.00126|0.21790|0.00%|0.21741|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/37549e4563)|0.21240|0.21672|0.00105|0.21393|-1.82%|0.21374|-1.69%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/ddd33fd7e4)|0.27147|0.28360|0.00270|0.27778|27.48%|0.27797|27.85%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ddd33fd7e4)|0.07571|0.07871|0.00077|0.07671|-64.80%|0.07648|-64.82%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34407|1.35875|0.00385|1.35201|0.00%|1.35198|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/37549e4563)|1.28914|1.30718|0.00460|1.29772|-4.02%|1.29776|-4.01%|20.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/ddd33fd7e4)|1.28572|1.29648|0.00273|1.29163|-4.47%|1.29173|-4.46%|20.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ddd33fd7e4)|0.55010|0.56678|0.00429|0.55979|-58.60%|0.56054|-58.54%|22.23 MB|
