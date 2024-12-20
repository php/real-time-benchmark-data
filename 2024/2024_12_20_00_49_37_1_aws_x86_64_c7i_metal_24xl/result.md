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
| Time          |2024-12-20 00:49:37 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43883|0.45285|0.00189|0.43996|0.00%|0.43968|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8aac6987c2)|0.43558|0.43786|0.00059|0.43651|-0.78%|0.43636|-0.75%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.43463|0.43618|0.00038|0.43542|-1.03%|0.43534|-0.99%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.42532|0.42671|0.00030|0.42605|-3.16%|0.42601|-3.11%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71324|0.71643|0.00070|0.71437|0.00%|0.71430|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8aac6987c2)|0.70824|0.71622|0.00125|0.71008|-0.60%|0.70989|-0.62%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.70942|0.71254|0.00068|0.71070|-0.51%|0.71066|-0.51%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.68123|0.68465|0.00057|0.68265|-4.44%|0.68262|-4.43%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58179|0.58437|0.00054|0.58307|0.00%|0.58298|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8aac6987c2)|0.57863|0.59053|0.00163|0.57986|-0.55%|0.57952|-0.59%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.57384|0.58066|0.00185|0.57698|-1.04%|0.57772|-0.90%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.52118|0.52333|0.00053|0.52213|-10.45%|0.52212|-10.44%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21493|0.21977|0.00100|0.21628|0.00%|0.21612|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8aac6987c2)|0.21536|0.21972|0.00088|0.21687|0.27%|0.21669|0.27%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.21583|0.21827|0.00054|0.21668|0.18%|0.21665|0.25%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.07417|0.07784|0.00087|0.07542|-65.13%|0.07519|-65.21%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34241|1.36613|0.00608|1.35271|0.00%|1.35201|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8aac6987c2)|1.46078|1.48621|0.00537|1.46966|8.65%|1.46944|8.69%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/4b1c3cf0b6)|1.33497|1.35976|0.00583|1.34581|-0.51%|1.34487|-0.53%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.53263|0.55081|0.00384|0.54149|-59.97%|0.54108|-59.98%|21.65 MB|
