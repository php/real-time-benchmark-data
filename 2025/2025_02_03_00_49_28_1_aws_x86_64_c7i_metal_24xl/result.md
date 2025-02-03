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
| Kernel        |6.1.124-134.200.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250128|
| GCC           |11.4.1|
| Time          |2025-02-03 00:49:28 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44053|0.44354|0.00063|0.44165|0.00%|0.44160|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e306a2e0e8)|0.43896|0.44743|0.00124|0.44025|-0.32%|0.44000|-0.36%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/caf5e8a167)|0.43973|0.44566|0.00095|0.44113|-0.12%|0.44104|-0.13%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/caf5e8a167)|0.42584|0.42873|0.00067|0.42702|-3.31%|0.42697|-3.31%|50.79 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71464|0.71823|0.00087|0.71635|0.00%|0.71631|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e306a2e0e8)|0.70962|0.71357|0.00085|0.71138|-0.69%|0.71121|-0.71%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/caf5e8a167)|0.71268|0.71720|0.00112|0.71461|-0.24%|0.71450|-0.25%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/caf5e8a167)|0.68604|0.69129|0.00112|0.68805|-3.95%|0.68803|-3.95%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58156|0.58440|0.00057|0.58272|0.00%|0.58270|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e306a2e0e8)|0.58035|0.58313|0.00070|0.58146|-0.22%|0.58142|-0.22%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/caf5e8a167)|0.57652|0.57930|0.00053|0.57766|-0.87%|0.57758|-0.88%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/caf5e8a167)|0.52052|0.52692|0.00112|0.52196|-10.43%|0.52177|-10.46%|61.92 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21417|0.21937|0.00096|0.21598|0.00%|0.21568|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e306a2e0e8)|0.21755|0.22090|0.00076|0.21897|1.38%|0.21888|1.48%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/caf5e8a167)|0.21388|0.21931|0.00105|0.21576|-0.10%|0.21554|-0.07%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/caf5e8a167)|0.07300|0.07712|0.00078|0.07474|-65.39%|0.07464|-65.39%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34015|1.36574|0.00634|1.35146|0.00%|1.35205|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e306a2e0e8)|1.28899|1.31219|0.00421|1.29761|-3.98%|1.29657|-4.10%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/caf5e8a167)|1.23891|1.26085|0.00517|1.24913|-7.57%|1.25024|-7.53%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/caf5e8a167)|0.52346|0.55149|0.00552|0.53953|-60.08%|0.53898|-60.14%|21.71 MB|
