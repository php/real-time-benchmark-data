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
| Time          |2024-11-25 00:49:38 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43986|0.45416|0.00240|0.44106|0.00%|0.44054|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.43759|0.44023|0.00052|0.43870|-0.54%|0.43871|-0.42%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/32ff46b633)|0.43724|0.43909|0.00041|0.43784|-0.73%|0.43786|-0.61%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32ff46b633)|0.42706|0.42883|0.00045|0.42777|-3.02%|0.42771|-2.91%|50.74 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71389|0.71719|0.00068|0.71537|0.00%|0.71538|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.70764|0.71133|0.00075|0.70865|-0.94%|0.70849|-0.96%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/32ff46b633)|0.70814|0.71301|0.00100|0.70957|-0.81%|0.70932|-0.85%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32ff46b633)|0.68202|0.68577|0.00073|0.68311|-4.51%|0.68295|-4.53%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58049|0.59056|0.00133|0.58196|0.00%|0.58173|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.57802|0.58857|0.00143|0.57933|-0.45%|0.57910|-0.45%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/32ff46b633)|0.57301|0.57959|0.00222|0.57597|-1.03%|0.57467|-1.21%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32ff46b633)|0.52263|0.52502|0.00052|0.52350|-10.05%|0.52345|-10.02%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21472|0.22000|0.00112|0.21664|0.00%|0.21644|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|0.21504|0.21830|0.00074|0.21641|-0.11%|0.21641|-0.01%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/32ff46b633)|0.21501|0.21978|0.00091|0.21688|0.11%|0.21680|0.17%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32ff46b633)|0.07400|0.07695|0.00073|0.07531|-65.24%|0.07529|-65.21%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33951|1.36711|0.00601|1.35187|0.00%|1.35252|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c84b7ed0c5)|1.27717|1.30151|0.00592|1.28927|-4.63%|1.28966|-4.65%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/32ff46b633)|1.34877|1.37165|0.00526|1.35831|0.48%|1.35823|0.42%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/32ff46b633)|0.52586|0.54589|0.00376|0.53709|-60.27%|0.53678|-60.31%|21.69 MB|
