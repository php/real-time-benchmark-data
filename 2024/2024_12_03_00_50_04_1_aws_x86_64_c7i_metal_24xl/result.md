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
| Time          |2024-12-03 00:50:04 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43895|0.44097|0.00038|0.43985|0.00%|0.43986|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d2c544cca)|0.43746|0.43948|0.00042|0.43849|-0.31%|0.43851|-0.31%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/01093b7c13)|0.43669|0.43878|0.00044|0.43755|-0.52%|0.43756|-0.52%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/01093b7c13)|0.42458|0.42641|0.00044|0.42563|-3.23%|0.42568|-3.22%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71260|0.72858|0.00285|0.71445|0.00%|0.71394|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d2c544cca)|0.71034|0.71324|0.00061|0.71170|-0.39%|0.71167|-0.32%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/01093b7c13)|0.71047|0.71483|0.00080|0.71205|-0.34%|0.71194|-0.28%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/01093b7c13)|0.68339|0.68613|0.00061|0.68475|-4.16%|0.68469|-4.10%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58112|0.58352|0.00054|0.58202|0.00%|0.58201|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d2c544cca)|0.57730|0.57961|0.00061|0.57830|-0.64%|0.57828|-0.64%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/01093b7c13)|0.57659|0.57979|0.00067|0.57789|-0.71%|0.57782|-0.72%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/01093b7c13)|0.51885|0.52062|0.00042|0.51963|-10.72%|0.51954|-10.73%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21502|0.21846|0.00074|0.21643|0.00%|0.21631|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d2c544cca)|0.21471|0.21929|0.00091|0.21626|-0.08%|0.21610|-0.10%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/01093b7c13)|0.21485|0.21839|0.00081|0.21620|-0.10%|0.21609|-0.10%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/01093b7c13)|0.07344|0.07800|0.00094|0.07552|-65.11%|0.07529|-65.19%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33902|1.36231|0.00605|1.35057|0.00%|1.35078|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d2c544cca)|1.24515|1.26918|0.00428|1.25917|-6.77%|1.25885|-6.81%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/01093b7c13)|1.24505|1.26944|0.00515|1.25866|-6.81%|1.25901|-6.79%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/01093b7c13)|0.53573|0.56212|0.00630|0.55018|-59.26%|0.55046|-59.25%|21.70 MB|
