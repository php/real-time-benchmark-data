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
| Time          |2025-01-17 00:49:20 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43894|0.44971|0.00179|0.43995|0.00%|0.43959|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39f1d253b1)|0.43822|0.44052|0.00051|0.43909|-0.20%|0.43904|-0.13%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0d8e6867a)|0.43992|0.44166|0.00041|0.44057|0.14%|0.44049|0.20%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0d8e6867a)|0.42715|0.43328|0.00086|0.42815|-2.68%|0.42800|-2.64%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71337|0.71682|0.00068|0.71469|0.00%|0.71454|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39f1d253b1)|0.71217|0.72670|0.00204|0.71347|-0.17%|0.71306|-0.21%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0d8e6867a)|0.71053|0.71268|0.00055|0.71156|-0.44%|0.71160|-0.41%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0d8e6867a)|0.68516|0.68739|0.00056|0.68611|-4.00%|0.68604|-3.99%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58089|0.59026|0.00132|0.58190|0.00%|0.58170|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39f1d253b1)|0.57889|0.58397|0.00096|0.58002|-0.32%|0.57977|-0.33%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0d8e6867a)|0.57762|0.64507|0.03059|0.60159|3.38%|0.57926|-0.42%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0d8e6867a)|0.58050|0.59032|0.00246|0.58629|0.75%|0.58647|0.82%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21479|0.22034|0.00125|0.21675|0.00%|0.21641|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39f1d253b1)|0.21575|0.22052|0.00088|0.21757|0.38%|0.21753|0.52%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0d8e6867a)|0.21464|0.21781|0.00070|0.21632|-0.20%|0.21637|-0.02%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0d8e6867a)|0.07465|0.07778|0.00075|0.07603|-64.92%|0.07592|-64.92%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33928|1.36796|0.00644|1.35410|0.00%|1.35437|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39f1d253b1)|1.32523|1.34742|0.00386|1.33935|-1.09%|1.33959|-1.09%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/d0d8e6867a)|1.26955|1.28874|0.00437|1.27680|-5.71%|1.27668|-5.74%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d0d8e6867a)|0.54476|0.56317|0.00417|0.55406|-59.08%|0.55419|-59.08%|21.72 MB|
