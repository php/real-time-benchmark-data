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
| Time          |2024-11-24 00:49:42 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43929|0.44353|0.00066|0.44042|0.00%|0.44040|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.43725|0.43949|0.00048|0.43816|-0.51%|0.43816|-0.51%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.43724|0.43888|0.00039|0.43792|-0.57%|0.43786|-0.58%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.42446|0.42595|0.00035|0.42512|-3.47%|0.42509|-3.47%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71376|0.71816|0.00084|0.71524|0.00%|0.71514|0.00%|37.34 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.70747|0.71230|0.00089|0.70865|-0.92%|0.70844|-0.94%|37.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.70762|0.71256|0.00108|0.70902|-0.87%|0.70888|-0.88%|37.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.68135|0.68463|0.00072|0.68285|-4.53%|0.68277|-4.53%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57898|0.58320|0.00093|0.58110|0.00%|0.58090|0.00%|42.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.57815|0.58515|0.00192|0.58037|-0.13%|0.57964|-0.22%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.57768|0.58384|0.00145|0.57952|-0.27%|0.57910|-0.31%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.52155|0.52373|0.00053|0.52251|-10.08%|0.52250|-10.05%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21529|0.22005|0.00106|0.21681|0.00%|0.21664|0.00%|26.13 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.21452|0.21763|0.00066|0.21593|-0.41%|0.21590|-0.34%|26.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.21449|0.21797|0.00063|0.21598|-0.38%|0.21599|-0.30%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.07331|0.07777|0.00076|0.07484|-65.48%|0.07467|-65.53%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34224|1.35858|0.00453|1.35124|0.00%|1.35151|0.00%|20.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|1.27273|1.30369|0.00672|1.28692|-4.76%|1.28814|-4.69%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/c84b7ed0c5)|1.27465|1.30993|0.00821|1.29130|-4.44%|1.29122|-4.46%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c84b7ed0c5)|0.52035|0.54294|0.00468|0.53171|-60.65%|0.53162|-60.66%|21.70 MB|
