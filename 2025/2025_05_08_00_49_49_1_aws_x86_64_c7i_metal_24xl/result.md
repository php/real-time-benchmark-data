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
| Time          |2025-05-08 00:49:49 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43422|0.44857|0.00261|0.43546|0.00%|0.43487|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50dc301f96)|0.43229|0.43464|0.00056|0.43310|-0.54%|0.43289|-0.46%|41.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3715cddf0)|0.43392|0.43660|0.00058|0.43484|-0.14%|0.43478|-0.02%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3715cddf0)|0.42127|0.42299|0.00043|0.42193|-3.11%|0.42185|-2.99%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70834|0.71254|0.00100|0.70951|0.00%|0.70920|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50dc301f96)|0.70505|0.70996|0.00113|0.70636|-0.44%|0.70593|-0.46%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3715cddf0)|0.70399|0.70716|0.00084|0.70558|-0.55%|0.70559|-0.51%|37.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3715cddf0)|0.67582|0.68125|0.00093|0.67949|-4.23%|0.67960|-4.17%|44.61 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57836|0.58014|0.00042|0.57945|0.00%|0.57948|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50dc301f96)|0.57900|0.58187|0.00064|0.58006|0.10%|0.57996|0.08%|43.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3715cddf0)|0.58251|0.64938|0.02366|0.59398|2.51%|0.58353|0.70%|43.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3715cddf0)|0.52022|0.58959|0.02296|0.53097|-8.37%|0.52128|-10.04%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21542|0.21936|0.00096|0.21685|0.00%|0.21672|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50dc301f96)|0.21409|0.21944|0.00150|0.21646|-0.18%|0.21645|-0.13%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3715cddf0)|0.21159|0.21796|0.00195|0.21371|-1.44%|0.21284|-1.79%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3715cddf0)|0.07465|0.07852|0.00091|0.07670|-64.63%|0.07655|-64.68%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34258|1.35724|0.00358|1.35112|0.00%|1.35090|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/50dc301f96)|1.28951|1.29826|0.00240|1.29392|-4.23%|1.29405|-4.21%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3715cddf0)|1.26625|1.29292|0.00653|1.27928|-5.32%|1.27768|-5.42%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3715cddf0)|0.56465|0.57726|0.00318|0.57140|-57.71%|0.57103|-57.73%|21.83 MB|
