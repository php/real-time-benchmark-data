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
| Time          |2025-01-24 00:49:19 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43861|0.44798|0.00189|0.44008|0.00%|0.43959|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.43724|0.43926|0.00042|0.43786|-0.50%|0.43787|-0.39%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/10ccb6bf0d)|0.43838|0.44037|0.00047|0.43925|-0.19%|0.43923|-0.08%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10ccb6bf0d)|0.42791|0.42993|0.00041|0.42872|-2.58%|0.42871|-2.48%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71355|0.71783|0.00077|0.71506|0.00%|0.71498|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.71263|0.71644|0.00067|0.71387|-0.17%|0.71388|-0.15%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/10ccb6bf0d)|0.71270|0.71518|0.00060|0.71384|-0.17%|0.71378|-0.17%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10ccb6bf0d)|0.68430|0.68778|0.00073|0.68567|-4.11%|0.68560|-4.11%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58128|0.58447|0.00054|0.58238|0.00%|0.58232|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.57660|0.57954|0.00061|0.57770|-0.80%|0.57758|-0.81%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/10ccb6bf0d)|0.57771|0.58044|0.00061|0.57915|-0.55%|0.57908|-0.56%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10ccb6bf0d)|0.52051|0.52662|0.00084|0.52139|-10.47%|0.52130|-10.48%|62.49 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21459|0.21983|0.00115|0.21636|0.00%|0.21601|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cbf4e7f)|0.21488|0.21863|0.00090|0.21657|0.10%|0.21655|0.25%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/10ccb6bf0d)|0.21496|0.21790|0.00075|0.21601|-0.16%|0.21583|-0.08%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10ccb6bf0d)|0.07461|0.07731|0.00057|0.07580|-64.97%|0.07568|-64.96%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34071|1.36472|0.00628|1.35373|0.00%|1.35268|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cbf4e7f)|1.32406|1.34920|0.00506|1.34140|-0.91%|1.34160|-0.82%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/10ccb6bf0d)|1.27175|1.30219|0.00613|1.28959|-4.74%|1.28903|-4.71%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10ccb6bf0d)|0.54957|0.57025|0.00538|0.55885|-58.72%|0.55850|-58.71%|21.72 MB|
