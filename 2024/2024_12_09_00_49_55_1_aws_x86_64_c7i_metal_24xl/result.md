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
| Time          |2024-12-09 00:49:55 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43907|0.44773|0.00117|0.44020|0.00%|0.43999|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5d9c7da9e)|0.43811|0.44009|0.00044|0.43886|-0.31%|0.43879|-0.27%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0385e978a)|0.43734|0.43948|0.00045|0.43823|-0.45%|0.43824|-0.40%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0385e978a)|0.42551|0.42752|0.00034|0.42636|-3.14%|0.42636|-3.10%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71253|0.71766|0.00088|0.71404|0.00%|0.71398|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5d9c7da9e)|0.70188|0.71446|0.00169|0.71159|-0.34%|0.71159|-0.33%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0385e978a)|0.70828|0.71224|0.00090|0.70965|-0.61%|0.70947|-0.63%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0385e978a)|0.68194|0.68455|0.00058|0.68314|-4.33%|0.68314|-4.32%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58028|0.58370|0.00075|0.58146|0.00%|0.58141|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5d9c7da9e)|0.57714|0.58136|0.00073|0.57832|-0.54%|0.57822|-0.55%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0385e978a)|0.57728|0.58783|0.00147|0.57859|-0.49%|0.57830|-0.53%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0385e978a)|0.52063|0.52341|0.00062|0.52157|-10.30%|0.52149|-10.31%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21521|0.22034|0.00116|0.21698|0.00%|0.21685|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5d9c7da9e)|0.21501|0.21791|0.00066|0.21631|-0.31%|0.21616|-0.32%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0385e978a)|0.21579|0.21983|0.00086|0.21704|0.03%|0.21688|0.01%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0385e978a)|0.07410|0.07676|0.00065|0.07535|-65.27%|0.07534|-65.26%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33942|1.36271|0.00510|1.35049|0.00%|1.35011|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5d9c7da9e)|1.25074|1.27549|0.00543|1.26146|-6.59%|1.26080|-6.62%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/c0385e978a)|1.33827|1.36648|0.00600|1.35161|0.08%|1.35236|0.17%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c0385e978a)|0.53213|0.55386|0.00443|0.54183|-59.88%|0.54118|-59.92%|21.64 MB|
