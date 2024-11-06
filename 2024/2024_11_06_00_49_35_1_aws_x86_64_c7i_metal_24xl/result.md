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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-11-06 00:49:35 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43802|0.44571|0.00132|0.43925|0.00%|0.43895|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64f2d11e38)|0.43592|0.43816|0.00051|0.43693|-0.53%|0.43686|-0.48%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/228c27112a)|0.43570|0.43745|0.00042|0.43650|-0.63%|0.43652|-0.55%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/228c27112a)|0.42447|0.42627|0.00041|0.42506|-3.23%|0.42508|-3.16%|50.87 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71820|0.73392|0.00210|0.72001|0.00%|0.71968|0.00%|37.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64f2d11e38)|0.71518|0.71890|0.00077|0.71696|-0.42%|0.71690|-0.39%|37.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/228c27112a)|0.71159|0.71551|0.00082|0.71301|-0.97%|0.71294|-0.94%|37.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/228c27112a)|0.68436|0.69395|0.00122|0.69068|-4.07%|0.69067|-4.03%|44.57 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58179|0.58401|0.00049|0.58274|0.00%|0.58265|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64f2d11e38)|0.57934|0.58602|0.00207|0.58218|-0.10%|0.58130|-0.23%|43.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/228c27112a)|0.58114|0.58470|0.00075|0.58227|-0.08%|0.58228|-0.06%|43.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/228c27112a)|0.52143|0.52413|0.00055|0.52280|-10.29%|0.52279|-10.28%|62.01 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21477|0.22227|0.00155|0.21711|0.00%|0.21670|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64f2d11e38)|0.21358|0.21679|0.00066|0.21481|-1.06%|0.21474|-0.91%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/228c27112a)|0.21197|0.21621|0.00085|0.21327|-1.77%|0.21301|-1.70%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/228c27112a)|0.07360|0.07657|0.00079|0.07509|-65.41%|0.07504|-65.37%|27.41 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33890|1.36589|0.00557|1.35160|0.00%|1.35152|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64f2d11e38)|1.26726|1.27748|0.00255|1.27262|-5.84%|1.27301|-5.81%|20.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/228c27112a)|1.28470|1.30620|0.00437|1.29467|-4.21%|1.29431|-4.23%|20.49 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/228c27112a)|0.53792|0.56106|0.00466|0.54562|-59.63%|0.54534|-59.65%|21.82 MB|
