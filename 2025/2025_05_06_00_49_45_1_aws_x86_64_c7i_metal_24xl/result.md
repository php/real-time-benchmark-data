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
| Kernel        |6.1.134-150.224.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250428|
| GCC           |11.5.0|
| Time          |2025-05-06 00:49:45 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43879|0.44483|0.00107|0.43970|0.00%|0.43950|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ee1a641)|0.43727|0.43971|0.00049|0.43864|-0.24%|0.43870|-0.18%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0b73dc977)|0.44008|0.44224|0.00054|0.44106|0.31%|0.44097|0.33%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0b73dc977)|0.42514|0.42833|0.00068|0.42574|-3.17%|0.42551|-3.18%|50.84 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71400|0.71656|0.00066|0.71494|0.00%|0.71483|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ee1a641)|0.71079|0.71399|0.00064|0.71205|-0.40%|0.71200|-0.40%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0b73dc977)|0.70999|0.71345|0.00078|0.71152|-0.48%|0.71170|-0.44%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0b73dc977)|0.68334|0.68551|0.00051|0.68439|-4.27%|0.68428|-4.27%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58099|0.58267|0.00051|0.58175|0.00%|0.58170|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ee1a641)|0.58133|0.58349|0.00050|0.58236|0.10%|0.58241|0.12%|43.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0b73dc977)|0.58255|0.58767|0.00078|0.58526|0.60%|0.58529|0.62%|43.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0b73dc977)|0.52152|0.52472|0.00069|0.52266|-10.16%|0.52263|-10.15%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21589|0.21950|0.00075|0.21682|0.00%|0.21658|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ee1a641)|0.21479|0.22041|0.00116|0.21598|-0.39%|0.21565|-0.43%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0b73dc977)|0.21721|0.22133|0.00123|0.21858|0.81%|0.21823|0.76%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0b73dc977)|0.07538|0.07879|0.00089|0.07683|-64.56%|0.07689|-64.50%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34062|1.36026|0.00440|1.34979|0.00%|1.35016|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/940ee1a641)|1.28486|1.30089|0.00394|1.29058|-4.39%|1.29019|-4.44%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0b73dc977)|1.27434|1.29142|0.00389|1.28430|-4.85%|1.28359|-4.93%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0b73dc977)|0.54933|0.57086|0.00453|0.55671|-58.76%|0.55658|-58.78%|21.82 MB|
