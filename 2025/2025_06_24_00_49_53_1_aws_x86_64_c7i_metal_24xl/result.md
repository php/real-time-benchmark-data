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
| Time          |2025-06-24 00:49:53 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44011|0.44724|0.00121|0.44104|0.00%|0.44079|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ddd33fd7e4)|0.43961|0.44128|0.00043|0.44040|-0.14%|0.44036|-0.10%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecc602e3bb)|0.43902|0.44050|0.00041|0.43972|-0.30%|0.43972|-0.24%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecc602e3bb)|0.42416|0.42568|0.00038|0.42488|-3.66%|0.42480|-3.63%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71459|0.71706|0.00061|0.71563|0.00%|0.71558|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ddd33fd7e4)|0.71134|0.71463|0.00093|0.71274|-0.40%|0.71250|-0.43%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecc602e3bb)|0.71104|0.71560|0.00125|0.71254|-0.43%|0.71214|-0.48%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecc602e3bb)|0.67967|0.68318|0.00086|0.68077|-4.87%|0.68050|-4.90%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57718|0.58295|0.00176|0.58113|0.00%|0.58188|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ddd33fd7e4)|0.57913|0.58139|0.00053|0.57997|-0.20%|0.57994|-0.33%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecc602e3bb)|0.57964|0.58220|0.00068|0.58108|-0.01%|0.58115|-0.13%|43.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecc602e3bb)|0.52480|0.52637|0.00042|0.52564|-9.55%|0.52573|-9.65%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21555|0.21992|0.00129|0.21760|0.00%|0.21762|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ddd33fd7e4)|0.26251|0.28261|0.00546|0.27504|26.40%|0.27713|27.34%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecc602e3bb)|0.21646|0.22063|0.00108|0.21791|0.14%|0.21764|0.01%|26.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecc602e3bb)|0.07641|0.07879|0.00070|0.07756|-64.36%|0.07734|-64.46%|27.77 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34745|1.36482|0.00448|1.35518|0.00%|1.35422|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ddd33fd7e4)|1.28397|1.29670|0.00345|1.29036|-4.78%|1.29061|-4.70%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecc602e3bb)|1.30984|1.32610|0.00427|1.31850|-2.71%|1.31936|-2.57%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecc602e3bb)|0.55577|0.56799|0.00284|0.56253|-58.49%|0.56321|-58.41%|22.23 MB|
