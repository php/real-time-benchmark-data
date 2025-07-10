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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-07-10 00:49:52 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44029|0.45410|0.00237|0.44143|0.00%|0.44103|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64e2832bc8)|0.43801|0.44071|0.00059|0.43877|-0.60%|0.43858|-0.55%|42.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/964a404451)|0.43732|0.44068|0.00076|0.43821|-0.73%|0.43806|-0.67%|42.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/964a404451)|0.42366|0.42484|0.00030|0.42409|-3.93%|0.42404|-3.85%|51.60 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71287|0.71630|0.00088|0.71400|0.00%|0.71368|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64e2832bc8)|0.70835|0.71263|0.00090|0.71008|-0.55%|0.70998|-0.52%|38.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/964a404451)|0.70778|0.72242|0.00319|0.71000|-0.56%|0.70907|-0.65%|38.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/964a404451)|0.67992|0.68233|0.00062|0.68118|-4.60%|0.68127|-4.54%|45.21 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58186|0.59281|0.00185|0.58346|0.00%|0.58305|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64e2832bc8)|0.57996|0.58300|0.00063|0.58122|-0.38%|0.58119|-0.32%|43.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/964a404451)|0.57625|0.58308|0.00124|0.57767|-0.99%|0.57746|-0.96%|43.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/964a404451)|0.52451|0.52721|0.00068|0.52547|-9.94%|0.52539|-9.89%|61.64 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21389|0.21919|0.00140|0.21627|0.00%|0.21611|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64e2832bc8)|0.21733|0.22117|0.00111|0.21879|1.16%|0.21844|1.08%|26.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/964a404451)|0.21630|0.22006|0.00103|0.21784|0.73%|0.21763|0.70%|26.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/964a404451)|0.07528|0.07760|0.00061|0.07652|-64.62%|0.07652|-64.59%|28.01 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.43437|1.45556|0.00568|1.44185|0.00%|1.44186|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64e2832bc8)|1.27549|1.29523|0.00441|1.28516|-10.87%|1.28525|-10.86%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/964a404451)|1.27783|1.29610|0.00359|1.28559|-10.84%|1.28530|-10.86%|21.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/964a404451)|0.54872|0.56044|0.00321|0.55462|-61.53%|0.55453|-61.54%|22.46 MB|
