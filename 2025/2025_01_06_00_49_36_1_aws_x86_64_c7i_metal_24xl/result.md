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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2025-01-06 00:49:36 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43861|0.44036|0.00041|0.43938|0.00%|0.43930|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/025cc6f603)|0.43611|0.43827|0.00046|0.43687|-0.57%|0.43677|-0.58%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4ad271073)|0.43532|0.43733|0.00044|0.43604|-0.76%|0.43604|-0.74%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4ad271073)|0.42482|0.42648|0.00034|0.42550|-3.16%|0.42545|-3.15%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71298|0.71614|0.00072|0.71421|0.00%|0.71409|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/025cc6f603)|0.71027|0.71354|0.00078|0.71124|-0.42%|0.71101|-0.43%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4ad271073)|0.71077|0.71518|0.00086|0.71246|-0.24%|0.71233|-0.25%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4ad271073)|0.68330|0.68626|0.00068|0.68439|-4.18%|0.68442|-4.15%|44.48 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58153|0.58466|0.00061|0.58258|0.00%|0.58247|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/025cc6f603)|0.57986|0.58381|0.00072|0.58216|-0.07%|0.58214|-0.06%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4ad271073)|0.57204|0.57892|0.00168|0.57577|-1.17%|0.57622|-1.07%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4ad271073)|0.51868|0.52107|0.00048|0.51972|-10.79%|0.51971|-10.78%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21488|0.21883|0.00099|0.21664|0.00%|0.21647|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/025cc6f603)|0.21128|0.21444|0.00072|0.21242|-1.95%|0.21226|-1.95%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4ad271073)|0.21474|0.21887|0.00086|0.21646|-0.09%|0.21627|-0.09%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4ad271073)|0.07364|0.07693|0.00089|0.07517|-65.30%|0.07521|-65.25%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33916|1.37062|0.00657|1.35276|0.00%|1.35200|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/025cc6f603)|1.25632|1.27368|0.00376|1.26420|-6.55%|1.26438|-6.48%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/e4ad271073)|1.25795|1.28059|0.00538|1.26865|-6.22%|1.26862|-6.17%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e4ad271073)|0.53467|0.55876|0.00477|0.54571|-59.66%|0.54566|-59.64%|21.66 MB|
