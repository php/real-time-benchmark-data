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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250203|
| GCC           |11.4.1|
| Time          |2025-02-10 00:49:25 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43887|0.44404|0.00073|0.43999|0.00%|0.43999|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e55889dca)|0.43695|0.43886|0.00048|0.43767|-0.53%|0.43756|-0.55%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/bce1f4aeb1)|0.43808|0.44634|0.00149|0.43923|-0.17%|0.43890|-0.25%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bce1f4aeb1)|0.42678|0.42867|0.00038|0.42761|-2.81%|0.42761|-2.81%|50.80 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70718|0.71656|0.00130|0.71429|0.00%|0.71437|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e55889dca)|0.70846|0.72481|0.00225|0.71039|-0.55%|0.71000|-0.61%|37.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/bce1f4aeb1)|0.70884|0.71116|0.00057|0.70994|-0.61%|0.70991|-0.62%|37.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bce1f4aeb1)|0.68357|0.68720|0.00069|0.68518|-4.08%|0.68504|-4.11%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57958|0.58393|0.00097|0.58192|0.00%|0.58186|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e55889dca)|0.57612|0.58393|0.00108|0.57787|-0.70%|0.57774|-0.71%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/bce1f4aeb1)|0.57547|0.57904|0.00085|0.57659|-0.92%|0.57642|-0.94%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bce1f4aeb1)|0.51614|0.52088|0.00090|0.51954|-10.72%|0.51966|-10.69%|61.93 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21434|0.22061|0.00127|0.21635|0.00%|0.21614|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e55889dca)|0.21560|0.21965|0.00089|0.21699|0.30%|0.21667|0.25%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/bce1f4aeb1)|0.21498|0.22036|0.00097|0.21674|0.18%|0.21650|0.17%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bce1f4aeb1)|0.07429|0.07846|0.00081|0.07567|-65.02%|0.07556|-65.04%|27.35 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33735|1.36333|0.00612|1.35064|0.00%|1.35002|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e55889dca)|1.27204|1.29342|0.00412|1.28208|-5.08%|1.28186|-5.05%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/bce1f4aeb1)|1.27092|1.29608|0.00525|1.28351|-4.97%|1.28380|-4.90%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bce1f4aeb1)|0.52203|0.54263|0.00481|0.53139|-60.66%|0.53096|-60.67%|21.77 MB|
