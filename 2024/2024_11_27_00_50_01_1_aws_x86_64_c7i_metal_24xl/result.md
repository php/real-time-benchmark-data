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
| Time          |2024-11-27 00:50:01 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43949|0.44148|0.00043|0.44022|0.00%|0.44021|0.00%|41.83 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba6c00505d)|0.43642|0.43845|0.00046|0.43752|-0.61%|0.43747|-0.62%|41.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/17187c4646)|0.43739|0.43917|0.00043|0.43809|-0.48%|0.43801|-0.50%|41.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17187c4646)|0.42556|0.42751|0.00042|0.42620|-3.19%|0.42614|-3.20%|50.76 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71316|0.71749|0.00077|0.71429|0.00%|0.71412|0.00%|37.35 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba6c00505d)|0.70745|0.71162|0.00113|0.70894|-0.75%|0.70865|-0.77%|37.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/17187c4646)|0.70763|0.71037|0.00065|0.70890|-0.75%|0.70888|-0.73%|37.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17187c4646)|0.68014|0.68396|0.00080|0.68168|-4.56%|0.68148|-4.57%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58147|0.59037|0.00122|0.58258|0.00%|0.58244|0.00%|42.97 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba6c00505d)|0.57745|0.58015|0.00052|0.57849|-0.70%|0.57843|-0.69%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/17187c4646)|0.57985|0.58328|0.00066|0.58143|-0.20%|0.58134|-0.19%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17187c4646)|0.52099|0.52324|0.00045|0.52184|-10.43%|0.52179|-10.41%|61.64 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21457|0.21831|0.00086|0.21603|0.00%|0.21586|0.00%|26.14 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba6c00505d)|0.21547|0.22023|0.00097|0.21709|0.49%|0.21691|0.49%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/17187c4646)|0.21152|0.21529|0.00085|0.21291|-1.45%|0.21276|-1.44%|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17187c4646)|0.07404|0.07727|0.00082|0.07521|-65.18%|0.07515|-65.19%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34053|1.36945|0.00658|1.35250|0.00%|1.35217|0.00%|20.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ba6c00505d)|1.34759|1.36826|0.00460|1.35769|0.38%|1.35738|0.39%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/17187c4646)|1.27366|1.29432|0.00424|1.28209|-5.21%|1.28235|-5.16%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17187c4646)|0.54245|0.56480|0.00413|0.55399|-59.04%|0.55443|-59.00%|21.71 MB|
