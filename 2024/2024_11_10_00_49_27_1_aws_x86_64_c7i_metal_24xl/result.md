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
| Kernel        |6.1.112-124.190.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241031|
| GCC           |11.4.1|
| Time          |2024-11-10 00:49:27 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43900|0.44254|0.00064|0.44019|0.00%|0.44017|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/963511bffa)|0.43683|0.43946|0.00058|0.43814|-0.46%|0.43812|-0.47%|41.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/62e53e6f49)|0.43790|0.43966|0.00046|0.43866|-0.35%|0.43873|-0.33%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/62e53e6f49)|0.42881|0.43060|0.00044|0.42967|-2.39%|0.42961|-2.40%|50.86 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.72061|0.72543|0.00098|0.72282|0.00%|0.72265|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/963511bffa)|0.71823|0.73476|0.00228|0.72072|-0.29%|0.72038|-0.31%|37.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/62e53e6f49)|0.71672|0.71984|0.00069|0.71827|-0.63%|0.71838|-0.59%|37.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/62e53e6f49)|0.69388|0.69726|0.00081|0.69552|-3.78%|0.69544|-3.76%|44.56 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57859|0.58502|0.00206|0.58193|0.00%|0.58303|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/963511bffa)|0.57947|0.59028|0.00146|0.58071|-0.21%|0.58047|-0.44%|43.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/62e53e6f49)|0.57716|0.57959|0.00055|0.57851|-0.59%|0.57853|-0.77%|43.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/62e53e6f49)|0.52275|0.52504|0.00051|0.52379|-9.99%|0.52379|-10.16%|60.71 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21414|0.21912|0.00111|0.21621|0.00%|0.21594|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/963511bffa)|0.21606|0.21982|0.00071|0.21728|0.49%|0.21720|0.58%|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/62e53e6f49)|0.21486|0.21943|0.00096|0.21621|-0.00%|0.21600|0.03%|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/62e53e6f49)|0.07326|0.07644|0.00078|0.07454|-65.52%|0.07432|-65.58%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33662|1.36878|0.00610|1.35045|0.00%|1.34897|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/963511bffa)|1.32567|1.36005|0.00697|1.33816|-0.91%|1.33753|-0.85%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/62e53e6f49)|1.25289|1.27961|0.00498|1.26668|-6.20%|1.26627|-6.13%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/62e53e6f49)|0.53271|0.55856|0.00603|0.54278|-59.81%|0.54290|-59.75%|21.80 MB|
