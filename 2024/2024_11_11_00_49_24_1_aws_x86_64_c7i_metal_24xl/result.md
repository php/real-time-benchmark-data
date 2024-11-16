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
| Kernel        |6.1.112-124.190.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241031|
| GCC           |11.4.1|
| Time          |2024-11-11 00:49:24 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43961|0.45400|0.00194|0.44076|0.00%|0.44052|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/62e53e6f49)|0.43741|0.44440|0.00096|0.43867|-0.47%|0.43861|-0.43%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/53df3ae1e5)|0.43668|0.43877|0.00048|0.43763|-0.71%|0.43754|-0.68%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/53df3ae1e5)|0.42662|0.42932|0.00068|0.42829|-2.83%|0.42836|-2.76%|50.86 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71998|0.72330|0.00074|0.72144|0.00%|0.72137|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/62e53e6f49)|0.71617|0.72135|0.00084|0.71784|-0.50%|0.71783|-0.49%|37.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/53df3ae1e5)|0.71773|0.72075|0.00062|0.71912|-0.32%|0.71907|-0.32%|37.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/53df3ae1e5)|0.69327|0.69708|0.00085|0.69486|-3.68%|0.69482|-3.68%|44.56 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57826|0.58530|0.00205|0.58209|0.00%|0.58301|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/62e53e6f49)|0.57792|0.58062|0.00058|0.57883|-0.56%|0.57872|-0.74%|43.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/53df3ae1e5)|0.57973|0.58268|0.00061|0.58091|-0.20%|0.58084|-0.37%|43.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/53df3ae1e5)|0.52133|0.52411|0.00064|0.52238|-10.26%|0.52224|-10.42%|62.00 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21441|0.21996|0.00097|0.21611|0.00%|0.21584|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/62e53e6f49)|0.21471|0.21809|0.00076|0.21596|-0.07%|0.21590|0.03%|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/53df3ae1e5)|0.21176|0.21779|0.00111|0.21348|-1.22%|0.21330|-1.18%|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/53df3ae1e5)|0.07285|0.07734|0.00084|0.07491|-65.34%|0.07488|-65.31%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.37261|1.39815|0.00580|1.38353|0.00%|1.38375|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/62e53e6f49)|1.25356|1.27492|0.00466|1.26612|-8.49%|1.26742|-8.41%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/53df3ae1e5)|1.27739|1.30127|0.00498|1.28840|-6.88%|1.28764|-6.95%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/53df3ae1e5)|0.53487|0.55333|0.00383|0.54291|-60.76%|0.54224|-60.81%|21.80 MB|