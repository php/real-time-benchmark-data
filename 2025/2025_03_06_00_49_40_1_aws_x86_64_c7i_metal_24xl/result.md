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
| Time          |2025-03-06 00:49:40 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43873|0.44856|0.00170|0.43973|0.00%|0.43946|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe8d39afc4)|0.43619|0.43940|0.00068|0.43708|-0.60%|0.43688|-0.59%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/0dede83264)|0.43659|0.44035|0.00087|0.43768|-0.47%|0.43740|-0.47%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0dede83264)|0.42608|0.42828|0.00048|0.42691|-2.92%|0.42678|-2.88%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71296|0.71598|0.00076|0.71406|0.00%|0.71386|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe8d39afc4)|0.69551|0.70657|0.00184|0.70489|-1.28%|0.70509|-1.23%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/0dede83264)|0.70353|0.70652|0.00080|0.70484|-1.29%|0.70476|-1.27%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0dede83264)|0.67912|0.68101|0.00051|0.67997|-4.77%|0.67995|-4.75%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58138|0.58340|0.00048|0.58215|0.00%|0.58208|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe8d39afc4)|0.57859|0.58129|0.00065|0.57973|-0.42%|0.57971|-0.41%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/0dede83264)|0.57684|0.57931|0.00049|0.57818|-0.68%|0.57823|-0.66%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0dede83264)|0.52148|0.52384|0.00052|0.52263|-10.22%|0.52255|-10.23%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21464|0.21864|0.00111|0.21627|0.00%|0.21615|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe8d39afc4)|0.21658|0.22025|0.00091|0.21818|0.89%|0.21804|0.87%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/0dede83264)|0.21636|0.21942|0.00075|0.21753|0.58%|0.21746|0.60%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0dede83264)|0.07463|0.07675|0.00057|0.07581|-64.95%|0.07587|-64.90%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33804|1.36820|0.00664|1.35079|0.00%|1.35082|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe8d39afc4)|1.37280|1.38717|0.00391|1.37898|2.09%|1.37804|2.01%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/0dede83264)|1.27328|1.29126|0.00444|1.28333|-4.99%|1.28251|-5.06%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0dede83264)|0.52464|0.53796|0.00364|0.53126|-60.67%|0.53146|-60.66%|21.79 MB|
