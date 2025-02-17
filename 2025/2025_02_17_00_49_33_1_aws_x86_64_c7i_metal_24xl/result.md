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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250211|
| GCC           |11.4.1|
| Time          |2025-02-17 00:49:33 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43929|0.44992|0.00147|0.44013|0.00%|0.43984|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c696087e32)|0.43681|0.43849|0.00035|0.43734|-0.63%|0.43734|-0.57%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ccb35ec94)|0.43659|0.43909|0.00051|0.43765|-0.56%|0.43760|-0.51%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ccb35ec94)|0.42566|0.42820|0.00044|0.42634|-3.13%|0.42625|-3.09%|50.78 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71275|0.71544|0.00064|0.71398|0.00%|0.71393|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c696087e32)|0.70923|0.72578|0.00227|0.71092|-0.43%|0.71047|-0.48%|37.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ccb35ec94)|0.70555|0.70938|0.00080|0.70668|-1.02%|0.70647|-1.04%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ccb35ec94)|0.67967|0.68279|0.00077|0.68073|-4.66%|0.68064|-4.66%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58115|0.58377|0.00062|0.58219|0.00%|0.58219|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c696087e32)|0.57226|0.64345|0.01523|0.58142|-0.13%|0.57757|-0.79%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ccb35ec94)|0.58072|0.58381|0.00066|0.58192|-0.05%|0.58193|-0.05%|42.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ccb35ec94)|0.52366|0.52567|0.00046|0.52460|-9.89%|0.52459|-9.89%|61.96 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21494|0.22107|0.00145|0.21699|0.00%|0.21661|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c696087e32)|0.21523|0.22029|0.00106|0.21720|0.10%|0.21697|0.17%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ccb35ec94)|0.21688|0.22224|0.00131|0.21916|1.00%|0.21894|1.08%|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ccb35ec94)|0.07532|0.07795|0.00055|0.07641|-64.79%|0.07640|-64.73%|27.42 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33510|1.35942|0.00568|1.34867|0.00%|1.34848|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c696087e32)|1.27403|1.31049|0.00694|1.28950|-4.39%|1.28928|-4.39%|20.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/6ccb35ec94)|1.28253|1.29466|0.00312|1.28767|-4.52%|1.28719|-4.55%|20.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6ccb35ec94)|0.54071|0.56566|0.00517|0.55242|-59.04%|0.55230|-59.04%|21.84 MB|
