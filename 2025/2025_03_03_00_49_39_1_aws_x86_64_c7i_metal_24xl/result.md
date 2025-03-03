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
| Time          |2025-03-03 00:49:39 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43808|0.44736|0.00159|0.43916|0.00%|0.43889|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|0.43670|0.44114|0.00088|0.43790|-0.29%|0.43773|-0.27%|41.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ae2c871d0)|0.43510|0.43710|0.00042|0.43586|-0.75%|0.43581|-0.70%|41.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ae2c871d0)|0.42425|0.42596|0.00035|0.42518|-3.18%|0.42521|-3.12%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71168|0.71459|0.00073|0.71299|0.00%|0.71304|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|0.70642|0.71037|0.00074|0.70785|-0.72%|0.70771|-0.75%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ae2c871d0)|0.70217|0.71538|0.00232|0.70362|-1.32%|0.70315|-1.39%|37.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ae2c871d0)|0.67813|0.68062|0.00071|0.67939|-4.71%|0.67927|-4.74%|44.56 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57998|0.58268|0.00053|0.58104|0.00%|0.58099|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|0.57632|0.57892|0.00063|0.57732|-0.64%|0.57737|-0.62%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ae2c871d0)|0.57749|0.57914|0.00040|0.57807|-0.51%|0.57805|-0.51%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ae2c871d0)|0.52051|0.52259|0.00041|0.52126|-10.29%|0.52122|-10.29%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21509|0.21968|0.00104|0.21657|0.00%|0.21652|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|0.21656|0.22189|0.00132|0.21854|0.91%|0.21838|0.86%|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ae2c871d0)|0.21651|0.21924|0.00079|0.21770|0.52%|0.21770|0.55%|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ae2c871d0)|0.07429|0.07711|0.00070|0.07585|-64.98%|0.07564|-65.06%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34001|1.36533|0.00561|1.34918|0.00%|1.34779|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3677871347)|1.36568|1.38333|0.00441|1.37476|1.90%|1.37445|1.98%|20.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ae2c871d0)|1.27754|1.29613|0.00410|1.28549|-4.72%|1.28578|-4.60%|20.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ae2c871d0)|0.52902|0.54705|0.00412|0.53621|-60.26%|0.53584|-60.24%|21.80 MB|
