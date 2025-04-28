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
| Kernel        |6.1.132-147.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250414|
| GCC           |11.5.0|
| Time          |2025-04-28 00:49:45 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43851|0.44744|0.00154|0.43966|0.00%|0.43936|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61d15870aa)|0.43931|0.44154|0.00053|0.44008|0.09%|0.43994|0.13%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/6fa669a125)|0.43745|0.43978|0.00059|0.43844|-0.28%|0.43832|-0.24%|41.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6fa669a125)|0.42261|0.42447|0.00039|0.42316|-3.75%|0.42309|-3.70%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71638|0.72103|0.00100|0.71804|0.00%|0.71799|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61d15870aa)|0.71099|0.72370|0.00229|0.71239|-0.79%|0.71165|-0.88%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/6fa669a125)|0.71068|0.72312|0.00212|0.71244|-0.78%|0.71199|-0.84%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6fa669a125)|0.68028|0.68231|0.00054|0.68111|-5.14%|0.68105|-5.15%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58166|0.58398|0.00060|0.58247|0.00%|0.58231|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61d15870aa)|0.57805|0.58055|0.00053|0.57925|-0.55%|0.57927|-0.52%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/6fa669a125)|0.58071|0.58257|0.00045|0.58156|-0.16%|0.58159|-0.12%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6fa669a125)|0.52030|0.52190|0.00040|0.52101|-10.55%|0.52096|-10.54%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21555|0.21926|0.00099|0.21698|0.00%|0.21682|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61d15870aa)|0.21531|0.21854|0.00070|0.21643|-0.25%|0.21650|-0.15%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/6fa669a125)|0.21455|0.21771|0.00086|0.21591|-0.50%|0.21590|-0.42%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6fa669a125)|0.07575|0.07909|0.00075|0.07714|-64.45%|0.07710|-64.44%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33787|1.36184|0.00521|1.35129|0.00%|1.35170|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61d15870aa)|1.27015|1.28212|0.00313|1.27481|-5.66%|1.27369|-5.77%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/6fa669a125)|1.28742|1.30704|0.00468|1.29518|-4.15%|1.29410|-4.26%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6fa669a125)|0.54635|0.56657|0.00411|0.55745|-58.75%|0.55767|-58.74%|21.82 MB|
