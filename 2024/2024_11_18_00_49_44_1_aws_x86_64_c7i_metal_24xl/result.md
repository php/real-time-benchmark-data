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
| OS            |Amazon Linux 2023.6.20241111|
| GCC           |11.4.1|
| Time          |2024-11-18 00:49:44 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43899|0.44879|0.00144|0.43984|0.00%|0.43956|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27a1d69504)|0.43627|0.43805|0.00042|0.43716|-0.61%|0.43716|-0.55%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/b112d27ff5)|0.43663|0.43868|0.00043|0.43734|-0.57%|0.43726|-0.53%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b112d27ff5)|0.42642|0.42810|0.00041|0.42719|-2.88%|0.42721|-2.81%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71319|0.71579|0.00055|0.71429|0.00%|0.71418|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27a1d69504)|0.71360|0.72992|0.00230|0.71530|0.14%|0.71484|0.09%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/b112d27ff5)|0.71369|0.71590|0.00053|0.71474|0.06%|0.71475|0.08%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b112d27ff5)|0.68189|0.68513|0.00064|0.68324|-4.35%|0.68327|-4.33%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58089|0.58421|0.00066|0.58182|0.00%|0.58170|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27a1d69504)|0.57776|0.58233|0.00086|0.58042|-0.24%|0.58036|-0.23%|43.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/b112d27ff5)|0.57871|0.58166|0.00061|0.58011|-0.29%|0.58002|-0.29%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b112d27ff5)|0.51989|0.52268|0.00052|0.52082|-10.48%|0.52068|-10.49%|61.62 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21568|0.22011|0.00105|0.21726|0.00%|0.21695|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27a1d69504)|0.21158|0.21540|0.00093|0.21296|-1.98%|0.21267|-1.97%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/b112d27ff5)|0.21043|0.21432|0.00089|0.21210|-2.38%|0.21189|-2.33%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b112d27ff5)|0.07364|0.07638|0.00082|0.07478|-65.58%|0.07449|-65.67%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34518|1.36814|0.00514|1.35586|0.00%|1.35615|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27a1d69504)|1.27487|1.29593|0.00459|1.28530|-5.20%|1.28520|-5.23%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/b112d27ff5)|1.26847|1.29670|0.00542|1.28520|-5.21%|1.28430|-5.30%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b112d27ff5)|0.53078|0.55912|0.00561|0.54298|-59.95%|0.54352|-59.92%|21.69 MB|
