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
| Kernel        |6.1.132-147.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250414|
| GCC           |11.5.0|
| Time          |2025-04-30 00:49:43 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43431|0.44917|0.00255|0.43563|0.00%|0.43526|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6fa669a125)|0.43405|0.43556|0.00042|0.43481|-0.19%|0.43476|-0.11%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5f3281446)|0.43192|0.43550|0.00085|0.43326|-0.54%|0.43315|-0.49%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5f3281446)|0.41982|0.42171|0.00045|0.42048|-3.48%|0.42037|-3.42%|50.84 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71065|0.71446|0.00093|0.71179|0.00%|0.71144|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6fa669a125)|0.70581|0.71015|0.00117|0.70728|-0.63%|0.70691|-0.64%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5f3281446)|0.70251|0.71596|0.00235|0.70430|-1.05%|0.70378|-1.08%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5f3281446)|0.67301|0.68032|0.00125|0.67900|-4.61%|0.67924|-4.53%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57594|0.58059|0.00108|0.57828|0.00%|0.57796|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6fa669a125)|0.57652|0.57842|0.00046|0.57741|-0.15%|0.57745|-0.09%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5f3281446)|0.57776|0.58146|0.00091|0.57966|0.24%|0.57959|0.28%|43.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5f3281446)|0.51870|0.52008|0.00038|0.51931|-10.20%|0.51926|-10.16%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21561|0.22159|0.00131|0.21744|0.00%|0.21746|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6fa669a125)|0.21763|0.22146|0.00114|0.21898|0.70%|0.21852|0.49%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5f3281446)|0.21679|0.21947|0.00066|0.21770|0.12%|0.21761|0.07%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5f3281446)|0.07541|0.07952|0.00092|0.07681|-64.68%|0.07669|-64.73%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33970|1.36452|0.00645|1.35200|0.00%|1.35075|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6fa669a125)|1.28950|1.31217|0.00500|1.29966|-3.87%|1.29988|-3.77%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/c5f3281446)|1.29365|1.30683|0.00304|1.30097|-3.77%|1.30187|-3.62%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c5f3281446)|0.54701|0.56261|0.00474|0.55425|-59.01%|0.55424|-58.97%|21.82 MB|
