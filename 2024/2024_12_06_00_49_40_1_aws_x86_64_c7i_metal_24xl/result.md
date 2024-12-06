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
| Time          |2024-12-06 00:49:40 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43906|0.44921|0.00132|0.44045|0.00%|0.44024|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bef96f35fd)|0.43817|0.44481|0.00091|0.43918|-0.29%|0.43902|-0.28%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b80b2e5ec)|0.43841|0.44574|0.00098|0.43950|-0.22%|0.43939|-0.19%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b80b2e5ec)|0.42621|0.42809|0.00033|0.42685|-3.09%|0.42675|-3.06%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71267|0.72874|0.00218|0.71430|0.00%|0.71407|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bef96f35fd)|0.71242|0.71620|0.00086|0.71374|-0.08%|0.71347|-0.08%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b80b2e5ec)|0.71168|0.71495|0.00069|0.71322|-0.15%|0.71320|-0.12%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b80b2e5ec)|0.68260|0.68518|0.00066|0.68384|-4.27%|0.68383|-4.24%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57689|0.58361|0.00208|0.58022|0.00%|0.58139|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bef96f35fd)|0.57641|0.58281|0.00157|0.58100|0.13%|0.58131|-0.01%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b80b2e5ec)|0.58039|0.59088|0.00141|0.58181|0.27%|0.58161|0.04%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b80b2e5ec)|0.51985|0.52175|0.00047|0.52065|-10.27%|0.52061|-10.45%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21502|0.21982|0.00105|0.21648|0.00%|0.21613|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bef96f35fd)|0.21188|0.21529|0.00085|0.21327|-1.49%|0.21303|-1.44%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b80b2e5ec)|0.21199|0.21636|0.00085|0.21340|-1.43%|0.21332|-1.30%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b80b2e5ec)|0.07403|0.07702|0.00075|0.07525|-65.24%|0.07519|-65.21%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34012|1.36864|0.00592|1.35256|0.00%|1.35258|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bef96f35fd)|1.27207|1.28917|0.00423|1.27989|-5.37%|1.27972|-5.39%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b80b2e5ec)|1.27001|1.29592|0.00409|1.28093|-5.30%|1.28019|-5.35%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b80b2e5ec)|0.54896|0.57050|0.00536|0.56007|-58.59%|0.56009|-58.59%|21.70 MB|
