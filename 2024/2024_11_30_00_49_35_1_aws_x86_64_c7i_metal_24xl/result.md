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
| Time          |2024-11-30 00:49:35 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43953|0.44320|0.00061|0.44047|0.00%|0.44041|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c05e6c247)|0.43726|0.44483|0.00102|0.43824|-0.51%|0.43811|-0.52%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/fdd3839d80)|0.43802|0.44413|0.00086|0.43907|-0.32%|0.43889|-0.34%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fdd3839d80)|0.42528|0.42676|0.00035|0.42599|-3.29%|0.42602|-3.27%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71308|0.71721|0.00073|0.71421|0.00%|0.71415|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c05e6c247)|0.70799|0.71182|0.00087|0.70923|-0.70%|0.70898|-0.72%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/fdd3839d80)|0.71040|0.71412|0.00081|0.71164|-0.36%|0.71150|-0.37%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fdd3839d80)|0.68136|0.68429|0.00066|0.68229|-4.47%|0.68223|-4.47%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58014|0.58361|0.00066|0.58169|0.00%|0.58176|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c05e6c247)|0.57915|0.58119|0.00051|0.58012|-0.27%|0.58015|-0.28%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/fdd3839d80)|0.57700|0.58031|0.00069|0.57814|-0.61%|0.57797|-0.65%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fdd3839d80)|0.52055|0.52281|0.00045|0.52139|-10.37%|0.52134|-10.39%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21542|0.21935|0.00107|0.21668|0.00%|0.21621|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c05e6c247)|0.21149|0.21510|0.00085|0.21283|-1.78%|0.21269|-1.63%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/fdd3839d80)|0.21476|0.21804|0.00076|0.21631|-0.17%|0.21616|-0.02%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fdd3839d80)|0.07424|0.07864|0.00096|0.07592|-64.96%|0.07573|-64.97%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34338|1.36821|0.00625|1.35603|0.00%|1.35538|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5c05e6c247)|1.27280|1.29056|0.00366|1.28000|-5.61%|1.27976|-5.58%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/fdd3839d80)|1.24971|1.26929|0.00454|1.25817|-7.22%|1.25779|-7.20%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fdd3839d80)|0.54646|0.56848|0.00491|0.55537|-59.04%|0.55565|-59.00%|21.70 MB|
