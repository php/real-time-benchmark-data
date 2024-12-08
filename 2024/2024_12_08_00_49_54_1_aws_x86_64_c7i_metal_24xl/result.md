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
| Time          |2024-12-08 00:49:54 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43972|0.44448|0.00107|0.44206|0.00%|0.44232|0.00%|41.83 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7aba3571f)|0.44084|0.44329|0.00058|0.44186|-0.05%|0.44180|-0.12%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5d9c7da9e)|0.44094|0.44319|0.00044|0.44218|0.03%|0.44213|-0.04%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5d9c7da9e)|0.42795|0.43054|0.00049|0.42881|-3.00%|0.42880|-3.06%|50.76 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71686|0.72070|0.00085|0.71851|0.00%|0.71851|0.00%|37.35 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7aba3571f)|0.71507|0.71888|0.00086|0.71667|-0.26%|0.71655|-0.27%|37.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5d9c7da9e)|0.71524|0.71953|0.00103|0.71686|-0.23%|0.71674|-0.25%|37.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5d9c7da9e)|0.68749|0.69059|0.00066|0.68862|-4.16%|0.68857|-4.17%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58255|0.58549|0.00062|0.58382|0.00%|0.58380|0.00%|42.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7aba3571f)|0.57888|0.58247|0.00082|0.58057|-0.56%|0.58067|-0.54%|42.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5d9c7da9e)|0.57907|0.58361|0.00080|0.58014|-0.63%|0.57999|-0.65%|42.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5d9c7da9e)|0.52022|0.52235|0.00053|0.52129|-10.71%|0.52122|-10.72%|61.64 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21539|0.22230|0.00116|0.21717|0.00%|0.21689|0.00%|26.13 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7aba3571f)|0.21518|0.21911|0.00083|0.21621|-0.44%|0.21600|-0.41%|26.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5d9c7da9e)|0.21491|0.21760|0.00064|0.21620|-0.45%|0.21626|-0.29%|26.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5d9c7da9e)|0.07405|0.07752|0.00084|0.07531|-65.32%|0.07518|-65.34%|27.24 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34711|1.36954|0.00617|1.35793|0.00%|1.35724|0.00%|20.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7aba3571f)|1.25338|1.27544|0.00417|1.26419|-6.90%|1.26418|-6.86%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5d9c7da9e)|1.25607|1.27897|0.00494|1.26488|-6.85%|1.26475|-6.81%|20.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5d9c7da9e)|0.53465|0.55395|0.00408|0.54585|-59.80%|0.54646|-59.74%|21.65 MB|
