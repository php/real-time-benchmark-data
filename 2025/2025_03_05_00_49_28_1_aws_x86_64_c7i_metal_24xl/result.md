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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-03-05 00:49:28 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43873|0.45193|0.00230|0.43981|0.00%|0.43930|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0df99742c4)|0.43631|0.43846|0.00049|0.43704|-0.63%|0.43691|-0.55%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe8d39afc4)|0.43608|0.43859|0.00052|0.43679|-0.69%|0.43667|-0.60%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe8d39afc4)|0.42597|0.42809|0.00045|0.42696|-2.92%|0.42688|-2.83%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71338|0.71513|0.00046|0.71413|0.00%|0.71415|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0df99742c4)|0.70282|0.70555|0.00068|0.70375|-1.45%|0.70353|-1.49%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe8d39afc4)|0.70407|0.70610|0.00062|0.70498|-1.28%|0.70489|-1.30%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe8d39afc4)|0.67162|0.68166|0.00166|0.67982|-4.80%|0.68001|-4.78%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58151|0.58454|0.00064|0.58240|0.00%|0.58228|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0df99742c4)|0.57721|0.58125|0.00076|0.57904|-0.58%|0.57914|-0.54%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe8d39afc4)|0.57742|0.58038|0.00067|0.57924|-0.54%|0.57917|-0.53%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe8d39afc4)|0.52208|0.52569|0.00067|0.52323|-10.16%|0.52316|-10.15%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21533|0.21915|0.00088|0.21670|0.00%|0.21660|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0df99742c4)|0.21649|0.22124|0.00115|0.21795|0.58%|0.21810|0.69%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe8d39afc4)|0.21551|0.21913|0.00074|0.21672|0.01%|0.21667|0.03%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe8d39afc4)|0.07551|0.07764|0.00063|0.07644|-64.72%|0.07622|-64.81%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33857|1.36431|0.00664|1.35202|0.00%|1.35111|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0df99742c4)|1.37303|1.39194|0.00474|1.38306|2.30%|1.38390|2.43%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/fe8d39afc4)|1.38220|1.39433|0.00335|1.38959|2.78%|1.39040|2.91%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fe8d39afc4)|0.53472|0.56112|0.00587|0.55110|-59.24%|0.55173|-59.16%|21.79 MB|
