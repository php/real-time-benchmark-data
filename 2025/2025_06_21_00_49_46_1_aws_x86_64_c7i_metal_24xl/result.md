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
| Time          |2025-06-21 00:49:46 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44061|0.45431|0.00233|0.44236|0.00%|0.44163|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be70f42de7)|0.43997|0.44206|0.00042|0.44073|-0.37%|0.44062|-0.23%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/89be689f77)|0.44146|0.44450|0.00067|0.44224|-0.03%|0.44205|0.09%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89be689f77)|0.42476|0.42707|0.00047|0.42587|-3.73%|0.42576|-3.60%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71626|0.72062|0.00110|0.71815|0.00%|0.71790|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be70f42de7)|0.71333|0.72385|0.00182|0.71463|-0.49%|0.71425|-0.51%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/89be689f77)|0.71339|0.72681|0.00299|0.71557|-0.36%|0.71489|-0.42%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89be689f77)|0.68065|0.68430|0.00084|0.68205|-5.03%|0.68195|-5.01%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58131|0.58329|0.00049|0.58207|0.00%|0.58206|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be70f42de7)|0.57854|0.58132|0.00052|0.57953|-0.44%|0.57955|-0.43%|43.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/89be689f77)|0.57929|0.58251|0.00075|0.58079|-0.22%|0.58053|-0.26%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89be689f77)|0.52370|0.52518|0.00040|0.52441|-9.91%|0.52434|-9.92%|61.30 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21544|0.22005|0.00094|0.21719|0.00%|0.21727|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be70f42de7)|0.21784|0.22129|0.00081|0.21897|0.82%|0.21890|0.75%|26.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/89be689f77)|0.21340|0.21602|0.00080|0.21433|-1.31%|0.21406|-1.48%|26.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89be689f77)|0.07549|0.07846|0.00066|0.07649|-64.78%|0.07637|-64.85%|27.77 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34594|1.37080|0.00471|1.35534|0.00%|1.35507|0.00%|20.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/be70f42de7)|1.27997|1.30272|0.00581|1.29327|-4.58%|1.29271|-4.60%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/89be689f77)|1.29880|1.32075|0.00600|1.30767|-3.52%|1.30707|-3.54%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89be689f77)|0.54267|0.55552|0.00332|0.54815|-59.56%|0.54783|-59.57%|22.23 MB|
