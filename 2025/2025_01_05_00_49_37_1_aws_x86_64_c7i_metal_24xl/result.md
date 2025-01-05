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
| Time          |2025-01-05 00:49:37 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43901|0.45363|0.00198|0.44014|0.00%|0.43982|0.00%|41.83 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/209e0d6ad2)|0.43554|0.44310|0.00103|0.43647|-0.83%|0.43633|-0.79%|41.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/025cc6f603)|0.43670|0.44403|0.00105|0.43756|-0.59%|0.43736|-0.56%|41.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/025cc6f603)|0.42598|0.42729|0.00035|0.42666|-3.06%|0.42663|-3.00%|50.76 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71314|0.71623|0.00075|0.71441|0.00%|0.71438|0.00%|37.35 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/209e0d6ad2)|0.70955|0.71294|0.00074|0.71110|-0.46%|0.71109|-0.46%|37.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/025cc6f603)|0.70946|0.72567|0.00220|0.71120|-0.45%|0.71089|-0.49%|37.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/025cc6f603)|0.68307|0.68539|0.00054|0.68397|-4.26%|0.68400|-4.25%|44.49 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58092|0.59098|0.00138|0.58247|0.00%|0.58223|0.00%|42.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/209e0d6ad2)|0.57845|0.58060|0.00053|0.57938|-0.53%|0.57933|-0.50%|42.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/025cc6f603)|0.57778|0.58385|0.00119|0.58153|-0.16%|0.58176|-0.08%|42.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/025cc6f603)|0.52006|0.52232|0.00048|0.52120|-10.52%|0.52113|-10.49%|61.92 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21532|0.22027|0.00093|0.21663|0.00%|0.21646|0.00%|26.13 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/209e0d6ad2)|0.21517|0.21827|0.00068|0.21629|-0.16%|0.21618|-0.13%|26.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/025cc6f603)|0.21135|0.21708|0.00133|0.21298|-1.68%|0.21251|-1.83%|26.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/025cc6f603)|0.07392|0.07696|0.00072|0.07515|-65.31%|0.07499|-65.36%|27.25 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34206|1.36483|0.00509|1.35303|0.00%|1.35392|0.00%|20.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/209e0d6ad2)|1.26900|1.29010|0.00427|1.27997|-5.40%|1.28002|-5.46%|20.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/025cc6f603)|1.24842|1.27467|0.00550|1.26228|-6.71%|1.26219|-6.77%|20.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/025cc6f603)|0.53867|0.56380|0.00596|0.55270|-59.15%|0.55356|-59.11%|21.67 MB|
