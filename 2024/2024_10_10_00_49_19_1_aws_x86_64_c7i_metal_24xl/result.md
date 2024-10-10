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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20241001|
| GCC           |11.4.1|
| Time          |2024-10-10 00:49:19 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43788|0.43996|0.00055|0.43866|0.00%|0.43859|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd0ced3046)|0.43635|0.43896|0.00052|0.43707|-0.36%|0.43703|-0.36%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/df8f298d8d)|0.43585|0.43771|0.00047|0.43697|-0.39%|0.43690|-0.39%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df8f298d8d)|0.42378|0.42563|0.00044|0.42479|-3.16%|0.42484|-3.14%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71398|0.72240|0.00148|0.71551|0.00%|0.71525|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd0ced3046)|0.71119|0.71500|0.00087|0.71264|-0.40%|0.71251|-0.38%|37.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/df8f298d8d)|0.71008|0.71312|0.00062|0.71124|-0.60%|0.71115|-0.57%|37.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df8f298d8d)|0.68643|0.68975|0.00064|0.68777|-3.88%|0.68781|-3.84%|44.51 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58041|0.58297|0.00061|0.58141|0.00%|0.58128|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd0ced3046)|0.57698|0.57888|0.00046|0.57789|-0.61%|0.57778|-0.60%|42.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/df8f298d8d)|0.58129|0.58347|0.00056|0.58215|0.13%|0.58211|0.14%|42.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df8f298d8d)|0.51993|0.52268|0.00062|0.52127|-10.34%|0.52120|-10.34%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21547|0.22063|0.00134|0.21666|0.00%|0.21623|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd0ced3046)|0.21488|0.21916|0.00104|0.21671|0.02%|0.21652|0.13%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/df8f298d8d)|0.21194|0.21633|0.00098|0.21320|-1.60%|0.21311|-1.44%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df8f298d8d)|0.07428|0.07642|0.00056|0.07540|-65.20%|0.07541|-65.13%|27.35 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34829|1.36478|0.00418|1.35519|0.00%|1.35509|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dd0ced3046)|1.36605|1.39303|0.00616|1.37870|1.73%|1.37771|1.67%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/df8f298d8d)|1.32075|1.33878|0.00529|1.32872|-1.95%|1.32898|-1.93%|20.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/df8f298d8d)|0.58634|0.60273|0.00355|0.59324|-56.22%|0.59279|-56.26%|21.76 MB|
