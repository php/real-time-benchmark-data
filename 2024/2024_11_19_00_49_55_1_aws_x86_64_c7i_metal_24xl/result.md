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
| OS            |Amazon Linux 2023.6.20241111|
| GCC           |11.4.1|
| Time          |2024-11-19 00:49:55 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43946|0.44157|0.00049|0.44021|0.00%|0.44016|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b112d27ff5)|0.43660|0.43882|0.00052|0.43771|-0.57%|0.43762|-0.58%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff5b42b839)|0.43718|0.43980|0.00053|0.43813|-0.47%|0.43806|-0.48%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff5b42b839)|0.42544|0.42729|0.00040|0.42628|-3.17%|0.42626|-3.16%|50.74 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71345|0.72804|0.00205|0.71534|0.00%|0.71486|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b112d27ff5)|0.71372|0.73066|0.00236|0.71569|0.05%|0.71530|0.06%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff5b42b839)|0.70931|0.71539|0.00112|0.71108|-0.60%|0.71086|-0.56%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff5b42b839)|0.68114|0.68417|0.00072|0.68236|-4.61%|0.68224|-4.56%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57535|0.58344|0.00210|0.58085|0.00%|0.58201|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b112d27ff5)|0.57962|0.58237|0.00065|0.58077|-0.01%|0.58080|-0.21%|43.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff5b42b839)|0.57700|0.57994|0.00064|0.57811|-0.47%|0.57803|-0.68%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff5b42b839)|0.52029|0.52248|0.00049|0.52110|-10.29%|0.52099|-10.48%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21498|0.22075|0.00113|0.21702|0.00%|0.21702|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b112d27ff5)|0.21151|0.21600|0.00110|0.21304|-1.83%|0.21274|-1.97%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff5b42b839)|0.21516|0.21902|0.00081|0.21676|-0.12%|0.21671|-0.15%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff5b42b839)|0.07386|0.07684|0.00073|0.07513|-65.38%|0.07513|-65.38%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33731|1.36505|0.00658|1.35257|0.00%|1.35323|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b112d27ff5)|1.27174|1.29418|0.00556|1.28451|-5.03%|1.28316|-5.18%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff5b42b839)|1.27363|1.29954|0.00598|1.28743|-4.82%|1.28738|-4.87%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff5b42b839)|0.52091|0.54771|0.00578|0.53360|-60.55%|0.53296|-60.62%|21.69 MB|
