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
| OS            |Amazon Linux 2023.6.20250115|
| GCC           |11.4.1|
| Time          |2025-01-19 00:49:35 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43865|0.45214|0.00180|0.43998|0.00%|0.43969|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/709c0a9905)|0.43808|0.44616|0.00147|0.43913|-0.19%|0.43877|-0.21%|41.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/252c0c9164)|0.43818|0.44090|0.00056|0.43923|-0.17%|0.43914|-0.12%|41.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/252c0c9164)|0.42642|0.42814|0.00044|0.42729|-2.88%|0.42726|-2.83%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71280|0.71549|0.00065|0.71414|0.00%|0.71398|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/709c0a9905)|0.71259|0.72789|0.00210|0.71415|0.00%|0.71387|-0.02%|37.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/252c0c9164)|0.71181|0.71497|0.00069|0.71345|-0.10%|0.71330|-0.09%|37.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/252c0c9164)|0.68218|0.68466|0.00052|0.68325|-4.33%|0.68321|-4.31%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58084|0.58433|0.00067|0.58200|0.00%|0.58195|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/709c0a9905)|0.57862|0.58129|0.00064|0.57961|-0.41%|0.57960|-0.40%|42.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/252c0c9164)|0.57853|0.58109|0.00061|0.57958|-0.42%|0.57950|-0.42%|42.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/252c0c9164)|0.52044|0.52258|0.00047|0.52144|-10.40%|0.52134|-10.41%|61.98 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21475|0.22023|0.00098|0.21608|0.00%|0.21597|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/709c0a9905)|0.21572|0.22001|0.00097|0.21730|0.57%|0.21714|0.54%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/252c0c9164)|0.21495|0.21841|0.00087|0.21671|0.29%|0.21668|0.33%|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/252c0c9164)|0.07534|0.07782|0.00063|0.07634|-64.67%|0.07623|-64.70%|27.31 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34235|1.36479|0.00536|1.35200|0.00%|1.35154|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/709c0a9905)|1.32570|1.34978|0.00478|1.33988|-0.90%|1.33993|-0.86%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/252c0c9164)|1.33583|1.36287|0.00546|1.34574|-0.46%|1.34616|-0.40%|20.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/252c0c9164)|0.53130|0.54785|0.00420|0.53896|-60.14%|0.53868|-60.14%|21.73 MB|
