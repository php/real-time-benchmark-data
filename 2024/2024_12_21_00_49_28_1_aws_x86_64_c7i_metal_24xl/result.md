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
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2024-12-21 00:49:28 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43848|0.44077|0.00046|0.43960|0.00%|0.43954|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.43424|0.43658|0.00051|0.43514|-1.02%|0.43510|-1.01%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/afc1f0d99b)|0.43518|0.43754|0.00046|0.43612|-0.79%|0.43610|-0.78%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/afc1f0d99b)|0.42373|0.42531|0.00036|0.42453|-3.43%|0.42454|-3.41%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71301|0.71679|0.00078|0.71412|0.00%|0.71398|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.70954|0.72530|0.00223|0.71137|-0.38%|0.71087|-0.43%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/afc1f0d99b)|0.70888|0.71315|0.00077|0.71053|-0.50%|0.71044|-0.50%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/afc1f0d99b)|0.68102|0.68424|0.00064|0.68215|-4.48%|0.68213|-4.46%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58090|0.58363|0.00055|0.58202|0.00%|0.58191|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.57727|0.57994|0.00058|0.57838|-0.63%|0.57829|-0.62%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/afc1f0d99b)|0.57501|0.57987|0.00069|0.57845|-0.61%|0.57841|-0.60%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/afc1f0d99b)|0.51905|0.52173|0.00051|0.52019|-10.62%|0.52011|-10.62%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21497|0.21983|0.00108|0.21682|0.00%|0.21667|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4b1c3cf0b6)|0.21538|0.21847|0.00065|0.21664|-0.09%|0.21661|-0.03%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/afc1f0d99b)|0.21411|0.21820|0.00078|0.21546|-0.63%|0.21534|-0.61%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/afc1f0d99b)|0.07391|0.07748|0.00083|0.07526|-65.29%|0.07504|-65.37%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34019|1.36753|0.00638|1.35414|0.00%|1.35402|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4b1c3cf0b6)|1.34009|1.36546|0.00618|1.35140|-0.20%|1.35100|-0.22%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/afc1f0d99b)|1.30362|1.32994|0.00734|1.31635|-2.79%|1.31682|-2.75%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/afc1f0d99b)|0.54852|0.57380|0.00604|0.56259|-58.45%|0.56314|-58.41%|21.65 MB|
