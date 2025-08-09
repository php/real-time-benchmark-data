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
| Kernel        |6.1.147-172.259.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250804|
| GCC           |11.5.0|
| Time          |2025-08-09 00:50:12 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47093|0.47289|0.00038|0.47180|0.00%|0.47180|0.00%|43.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe88711b14)|0.46741|0.46928|0.00049|0.46832|-0.74%|0.46825|-0.75%|43.56 MB|
|[PHP - master](https://github.com/php/php-src/commit/f64c6248b5)|0.46574|0.46759|0.00046|0.46656|-1.11%|0.46643|-1.14%|43.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f64c6248b5)|0.44955|0.45116|0.00037|0.45029|-4.56%|0.45026|-4.57%|53.75 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73889|0.74278|0.00102|0.74077|0.00%|0.74087|0.00%|39.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe88711b14)|0.72928|0.73969|0.00178|0.73076|-1.35%|0.73019|-1.44%|40.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/f64c6248b5)|0.72675|0.73389|0.00173|0.72876|-1.62%|0.72820|-1.71%|40.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f64c6248b5)|0.69391|0.70346|0.00197|0.69755|-5.83%|0.69708|-5.91%|47.78 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57970|0.58493|0.00097|0.58078|0.00%|0.58060|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe88711b14)|0.58079|0.58323|0.00060|0.58189|0.19%|0.58188|0.22%|43.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/f64c6248b5)|0.57945|0.58233|0.00077|0.58072|-0.01%|0.58058|-0.00%|43.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f64c6248b5)|0.51839|0.52062|0.00050|0.51936|-10.58%|0.51933|-10.55%|61.37 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21491|0.21909|0.00109|0.21676|0.00%|0.21685|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe88711b14)|0.21367|0.21583|0.00073|0.21455|-1.02%|0.21424|-1.20%|26.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/f64c6248b5)|0.25680|0.28223|0.00788|0.26918|24.18%|0.26892|24.01%|26.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f64c6248b5)|0.07372|0.07616|0.00066|0.07474|-65.52%|0.07461|-65.60%|27.73 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42232|1.43583|0.00389|1.42911|0.00%|1.42868|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe88711b14)|1.33660|1.36407|0.00551|1.34828|-5.66%|1.34795|-5.65%|20.84 MB|
|[PHP - master](https://github.com/php/php-src/commit/f64c6248b5)|1.29452|1.30728|0.00336|1.29988|-9.04%|1.29989|-9.01%|20.84 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f64c6248b5)|0.55482|0.57805|0.00616|0.56712|-60.32%|0.56803|-60.24%|22.17 MB|
