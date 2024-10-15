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
| Time          |2024-10-15 00:49:24 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43730|0.43895|0.00040|0.43797|0.00%|0.43796|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/41c55d18f5)|0.43634|0.43890|0.00055|0.43729|-0.16%|0.43721|-0.17%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/edf351ce6d)|0.43454|0.43851|0.00074|0.43552|-0.56%|0.43535|-0.60%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edf351ce6d)|0.42445|0.42681|0.00046|0.42528|-2.90%|0.42522|-2.91%|50.82 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71758|0.72204|0.00086|0.71975|0.00%|0.71963|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/41c55d18f5)|0.71538|0.71775|0.00065|0.71639|-0.47%|0.71641|-0.45%|37.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/edf351ce6d)|0.71288|0.73014|0.00293|0.71476|-0.69%|0.71409|-0.77%|37.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edf351ce6d)|0.68880|0.69073|0.00052|0.68988|-4.15%|0.68998|-4.12%|44.53 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58072|0.58343|0.00059|0.58185|0.00%|0.58184|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/41c55d18f5)|0.57685|0.57985|0.00071|0.57796|-0.67%|0.57791|-0.68%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/edf351ce6d)|0.57593|0.57813|0.00054|0.57680|-0.87%|0.57665|-0.89%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edf351ce6d)|0.52065|0.52294|0.00050|0.52163|-10.35%|0.52162|-10.35%|61.95 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21545|0.22016|0.00124|0.21672|0.00%|0.21629|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/41c55d18f5)|0.21514|0.21894|0.00085|0.21679|0.03%|0.21697|0.32%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/edf351ce6d)|0.21682|0.22236|0.00113|0.21804|0.61%|0.21762|0.62%|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edf351ce6d)|0.07384|0.07656|0.00064|0.07510|-65.35%|0.07510|-65.28%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34330|1.36354|0.00554|1.35300|0.00%|1.35224|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/41c55d18f5)|1.35813|1.38363|0.00623|1.37111|1.34%|1.37094|1.38%|20.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/edf351ce6d)|1.29861|1.31180|0.00322|1.30544|-3.52%|1.30505|-3.49%|20.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/edf351ce6d)|0.53223|0.55519|0.00452|0.53901|-60.16%|0.53815|-60.20%|21.78 MB|
