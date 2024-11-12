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
| Kernel        |6.1.112-124.190.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241031|
| GCC           |11.4.1|
| Time          |2024-11-12 00:49:37 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43891|0.44182|0.00046|0.43955|0.00%|0.43948|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53df3ae1e5)|0.43578|0.43752|0.00038|0.43651|-0.69%|0.43649|-0.68%|41.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f5a888bdb)|0.43634|0.43910|0.00054|0.43739|-0.49%|0.43731|-0.49%|41.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f5a888bdb)|0.42621|0.42841|0.00043|0.42734|-2.78%|0.42734|-2.76%|50.85 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71964|0.72415|0.00096|0.72113|0.00%|0.72097|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53df3ae1e5)|0.71615|0.72107|0.00096|0.71742|-0.51%|0.71739|-0.50%|37.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f5a888bdb)|0.71492|0.71914|0.00074|0.71671|-0.61%|0.71668|-0.59%|37.49 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f5a888bdb)|0.69285|0.69534|0.00061|0.69416|-3.74%|0.69410|-3.73%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58214|0.58487|0.00066|0.58328|0.00%|0.58329|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53df3ae1e5)|0.57873|0.58214|0.00070|0.58002|-0.56%|0.57985|-0.59%|43.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f5a888bdb)|0.57768|0.58154|0.00087|0.57899|-0.73%|0.57887|-0.76%|43.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f5a888bdb)|0.52074|0.52377|0.00074|0.52216|-10.48%|0.52208|-10.49%|62.00 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21566|0.21932|0.00092|0.21722|0.00%|0.21698|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53df3ae1e5)|0.21156|0.21691|0.00100|0.21300|-1.94%|0.21277|-1.94%|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f5a888bdb)|0.21510|0.21928|0.00089|0.21635|-0.40%|0.21617|-0.38%|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f5a888bdb)|0.07317|0.07637|0.00072|0.07473|-65.60%|0.07468|-65.58%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33925|1.36724|0.00520|1.34846|0.00%|1.34827|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/53df3ae1e5)|1.27738|1.30351|0.00429|1.28861|-4.44%|1.28876|-4.41%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/7f5a888bdb)|1.28667|1.32273|0.00729|1.30500|-3.22%|1.30531|-3.19%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7f5a888bdb)|0.51989|0.53715|0.00406|0.52722|-60.90%|0.52690|-60.92%|21.80 MB|
