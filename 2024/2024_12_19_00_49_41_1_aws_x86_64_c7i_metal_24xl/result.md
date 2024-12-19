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
| Time          |2024-12-19 00:49:41 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43846|0.45344|0.00199|0.44004|0.00%|0.43973|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d140f79e6)|0.43679|0.43929|0.00049|0.43765|-0.54%|0.43767|-0.47%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/8aac6987c2)|0.43619|0.44392|0.00106|0.43726|-0.63%|0.43707|-0.60%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8aac6987c2)|0.42599|0.42832|0.00044|0.42679|-3.01%|0.42670|-2.96%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71317|0.71615|0.00069|0.71444|0.00%|0.71439|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d140f79e6)|0.70842|0.71124|0.00064|0.70981|-0.65%|0.70984|-0.64%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/8aac6987c2)|0.70819|0.71132|0.00058|0.70944|-0.70%|0.70932|-0.71%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8aac6987c2)|0.68308|0.68609|0.00055|0.68437|-4.21%|0.68441|-4.20%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58144|0.58472|0.00066|0.58275|0.00%|0.58258|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d140f79e6)|0.58037|0.58334|0.00058|0.58161|-0.20%|0.58150|-0.19%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/8aac6987c2)|0.57338|0.57993|0.00240|0.57636|-1.10%|0.57500|-1.30%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8aac6987c2)|0.51983|0.52258|0.00064|0.52095|-10.61%|0.52081|-10.60%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21488|0.21902|0.00096|0.21638|0.00%|0.21615|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d140f79e6)|0.21508|0.22068|0.00112|0.21657|0.09%|0.21634|0.09%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/8aac6987c2)|0.21553|0.21756|0.00056|0.21641|0.01%|0.21640|0.11%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8aac6987c2)|0.07426|0.07756|0.00090|0.07567|-65.03%|0.07532|-65.16%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33943|1.36663|0.00629|1.35203|0.00%|1.35297|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d140f79e6)|1.29754|1.31460|0.00404|1.30544|-3.45%|1.30485|-3.56%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/8aac6987c2)|1.33662|1.36296|0.00601|1.34820|-0.28%|1.34832|-0.34%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8aac6987c2)|0.53246|0.55763|0.00494|0.54421|-59.75%|0.54394|-59.80%|21.64 MB|
