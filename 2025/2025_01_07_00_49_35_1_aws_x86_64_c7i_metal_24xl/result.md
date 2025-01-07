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
| Time          |2025-01-07 00:49:35 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43899|0.45295|0.00213|0.44018|0.00%|0.43967|0.00%|41.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4ad271073)|0.43500|0.43681|0.00047|0.43575|-1.01%|0.43563|-0.92%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c49f52b0d)|0.43900|0.44713|0.00137|0.44016|-0.00%|0.43994|0.06%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c49f52b0d)|0.42664|0.42818|0.00038|0.42728|-2.93%|0.42721|-2.83%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71298|0.71658|0.00073|0.71446|0.00%|0.71444|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4ad271073)|0.71182|0.71517|0.00070|0.71338|-0.15%|0.71326|-0.17%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c49f52b0d)|0.71091|0.71349|0.00057|0.71203|-0.34%|0.71202|-0.34%|37.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c49f52b0d)|0.68300|0.68593|0.00062|0.68411|-4.25%|0.68404|-4.25%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58032|0.58507|0.00081|0.58210|0.00%|0.58204|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4ad271073)|0.57557|0.57920|0.00078|0.57764|-0.77%|0.57767|-0.75%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c49f52b0d)|0.57366|0.58120|0.00199|0.57668|-0.93%|0.57673|-0.91%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c49f52b0d)|0.51785|0.52150|0.00081|0.51963|-10.73%|0.51952|-10.74%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21498|0.21900|0.00111|0.21647|0.00%|0.21614|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4ad271073)|0.21557|0.21906|0.00087|0.21733|0.40%|0.21731|0.54%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c49f52b0d)|0.21172|0.21650|0.00105|0.21329|-1.47%|0.21314|-1.39%|26.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c49f52b0d)|0.07494|0.07767|0.00074|0.07609|-64.85%|0.07587|-64.90%|27.24 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34247|1.36564|0.00602|1.35340|0.00%|1.35418|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4ad271073)|1.26015|1.27690|0.00408|1.26943|-6.20%|1.26989|-6.22%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/2c49f52b0d)|1.25539|1.27709|0.00470|1.26227|-6.73%|1.26146|-6.85%|20.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2c49f52b0d)|0.52792|0.55303|0.00413|0.53873|-60.19%|0.53845|-60.24%|21.66 MB|
