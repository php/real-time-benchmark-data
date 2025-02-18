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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250211|
| GCC           |11.4.1|
| Time          |2025-02-18 00:49:22 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43876|0.45311|0.00197|0.43982|0.00%|0.43951|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ccb35ec94)|0.43570|0.44355|0.00109|0.43651|-0.75%|0.43628|-0.74%|41.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/da38477544)|0.43695|0.44439|0.00103|0.43786|-0.44%|0.43766|-0.42%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da38477544)|0.42628|0.42784|0.00032|0.42696|-2.92%|0.42698|-2.85%|50.79 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71280|0.71666|0.00089|0.71419|0.00%|0.71410|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ccb35ec94)|0.70571|0.71083|0.00093|0.70713|-0.99%|0.70686|-1.01%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/da38477544)|0.70759|0.71260|0.00095|0.70891|-0.74%|0.70878|-0.74%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da38477544)|0.67944|0.68177|0.00065|0.68037|-4.74%|0.68015|-4.75%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58137|0.58487|0.00058|0.58241|0.00%|0.58237|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ccb35ec94)|0.58081|0.58275|0.00050|0.58177|-0.11%|0.58176|-0.11%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/da38477544)|0.57546|0.58130|0.00156|0.57746|-0.85%|0.57697|-0.93%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da38477544)|0.52131|0.52452|0.00064|0.52281|-10.23%|0.52274|-10.24%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21462|0.21926|0.00101|0.21633|0.00%|0.21614|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ccb35ec94)|0.21712|0.22163|0.00103|0.21961|1.52%|0.21978|1.68%|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/da38477544)|0.21172|0.21514|0.00082|0.21300|-1.54%|0.21294|-1.48%|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da38477544)|0.07523|0.07805|0.00072|0.07644|-64.66%|0.07638|-64.66%|27.37 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33554|1.35701|0.00492|1.34817|0.00%|1.34875|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6ccb35ec94)|1.28121|1.29745|0.00322|1.28859|-4.42%|1.28862|-4.46%|20.59 MB|
|[PHP - master](https://github.com/php/php-src/commit/da38477544)|1.25516|1.29115|0.00786|1.26932|-5.85%|1.26835|-5.96%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da38477544)|0.53382|0.56865|0.00680|0.54807|-59.35%|0.54833|-59.35%|21.79 MB|
