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
| Kernel        |6.1.132-147.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250414|
| GCC           |11.5.0|
| Time          |2025-04-26 00:49:32 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43811|0.44713|0.00156|0.43911|0.00%|0.43876|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6c09c167ef)|0.43845|0.44040|0.00042|0.43937|0.06%|0.43933|0.13%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/61d15870aa)|0.43840|0.44332|0.00090|0.43947|0.08%|0.43921|0.10%|41.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61d15870aa)|0.42229|0.42395|0.00041|0.42315|-3.63%|0.42310|-3.57%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71458|0.73100|0.00280|0.71649|0.00%|0.71591|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6c09c167ef)|0.70883|0.72140|0.00221|0.71056|-0.83%|0.71001|-0.82%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/61d15870aa)|0.70888|0.71455|0.00120|0.71020|-0.88%|0.70992|-0.84%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61d15870aa)|0.67872|0.68129|0.00068|0.67992|-5.10%|0.68001|-5.01%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58073|0.58289|0.00057|0.58166|0.00%|0.58161|0.00%|43.06 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6c09c167ef)|0.57642|0.57927|0.00072|0.57747|-0.72%|0.57744|-0.72%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/61d15870aa)|0.57580|0.57911|0.00081|0.57727|-0.75%|0.57720|-0.76%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61d15870aa)|0.52146|0.52322|0.00042|0.52232|-10.20%|0.52241|-10.18%|60.79 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21544|0.21926|0.00092|0.21731|0.00%|0.21722|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6c09c167ef)|0.21534|0.21819|0.00069|0.21628|-0.47%|0.21617|-0.49%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/61d15870aa)|0.21505|0.21775|0.00066|0.21601|-0.60%|0.21584|-0.64%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61d15870aa)|0.07525|0.07771|0.00060|0.07651|-64.80%|0.07646|-64.80%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34594|1.36158|0.00429|1.35276|0.00%|1.35273|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6c09c167ef)|1.27163|1.29281|0.00522|1.28268|-5.18%|1.28281|-5.17%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/61d15870aa)|1.27019|1.28491|0.00391|1.27658|-5.63%|1.27741|-5.57%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61d15870aa)|0.55170|0.56696|0.00315|0.55869|-58.70%|0.55846|-58.72%|21.82 MB|
