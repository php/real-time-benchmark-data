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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-05-22 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43835|0.44004|0.00050|0.43909|0.00%|0.43909|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/16a3fb1c3f)|0.43976|0.44228|0.00072|0.44052|0.33%|0.44029|0.27%|42.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd43536b27)|0.43730|0.43990|0.00059|0.43824|-0.19%|0.43821|-0.20%|42.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd43536b27)|0.42211|0.42392|0.00040|0.42267|-3.74%|0.42260|-3.76%|50.93 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71429|0.71817|0.00098|0.71585|0.00%|0.71560|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/16a3fb1c3f)|0.70799|0.71188|0.00073|0.70934|-0.91%|0.70940|-0.87%|37.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd43536b27)|0.71444|0.71954|0.00108|0.71580|-0.01%|0.71555|-0.01%|37.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd43536b27)|0.67994|0.68310|0.00085|0.68139|-4.81%|0.68128|-4.80%|44.68 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58177|0.58413|0.00055|0.58293|0.00%|0.58294|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/16a3fb1c3f)|0.57946|0.58320|0.00085|0.58113|-0.31%|0.58106|-0.32%|43.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd43536b27)|0.58062|0.58334|0.00056|0.58205|-0.15%|0.58203|-0.16%|43.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd43536b27)|0.52173|0.52708|0.00090|0.52606|-9.76%|0.52623|-9.73%|60.77 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21570|0.21933|0.00107|0.21722|0.00%|0.21691|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/16a3fb1c3f)|0.21461|0.21942|0.00134|0.21692|-0.14%|0.21692|0.00%|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd43536b27)|0.21707|0.22155|0.00113|0.21897|0.81%|0.21894|0.94%|26.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd43536b27)|0.07537|0.07837|0.00085|0.07695|-64.57%|0.07706|-64.47%|27.49 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33993|1.36293|0.00502|1.34905|0.00%|1.34801|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/16a3fb1c3f)|1.31226|1.32886|0.00469|1.31918|-2.21%|1.31790|-2.23%|20.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd43536b27)|1.29158|1.30519|0.00407|1.29784|-3.80%|1.29752|-3.75%|20.66 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd43536b27)|0.54424|0.55734|0.00324|0.54974|-59.25%|0.55002|-59.20%|21.91 MB|
