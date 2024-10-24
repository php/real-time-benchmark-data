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
| Time          |2024-10-24 00:49:27 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43879|0.45361|0.00200|0.43995|0.00%|0.43966|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55e8ebe29b)|0.43582|0.43779|0.00047|0.43653|-0.78%|0.43640|-0.74%|41.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/551a9ef5e6)|0.43634|0.43982|0.00053|0.43720|-0.63%|0.43711|-0.58%|41.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/551a9ef5e6)|0.42750|0.42948|0.00043|0.42834|-2.64%|0.42828|-2.59%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71893|0.72457|0.00094|0.72260|0.00%|0.72266|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55e8ebe29b)|0.71356|0.71689|0.00063|0.71507|-1.04%|0.71501|-1.06%|37.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/551a9ef5e6)|0.70295|0.71576|0.00168|0.71277|-1.36%|0.71283|-1.36%|37.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/551a9ef5e6)|0.68943|0.69336|0.00083|0.69080|-4.40%|0.69059|-4.44%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58288|0.58514|0.00061|0.58394|0.00%|0.58397|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55e8ebe29b)|0.57882|0.58119|0.00052|0.57982|-0.71%|0.57981|-0.71%|42.84 MB|
|[PHP - master](https://github.com/php/php-src/commit/551a9ef5e6)|0.58045|0.58258|0.00049|0.58114|-0.48%|0.58106|-0.50%|42.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/551a9ef5e6)|0.52409|0.52635|0.00048|0.52531|-10.04%|0.52528|-10.05%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21501|0.21941|0.00091|0.21649|0.00%|0.21636|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55e8ebe29b)|0.21522|0.22044|0.00103|0.21728|0.36%|0.21732|0.44%|26.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/551a9ef5e6)|0.21486|0.21941|0.00089|0.21670|0.10%|0.21653|0.08%|26.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/551a9ef5e6)|0.07404|0.07650|0.00053|0.07507|-65.32%|0.07507|-65.30%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33460|1.36073|0.00550|1.34786|0.00%|1.34718|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55e8ebe29b)|1.27749|1.29557|0.00363|1.28676|-4.53%|1.28617|-4.53%|20.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/551a9ef5e6)|1.28613|1.30441|0.00311|1.29394|-4.00%|1.29407|-3.94%|20.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/551a9ef5e6)|0.53197|0.55126|0.00354|0.53923|-59.99%|0.53928|-59.97%|21.64 MB|
