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
| OS            |Amazon Linux 2023.6.20250107|
| GCC           |11.4.1|
| Time          |2025-01-11 00:49:32 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43856|0.45289|0.00191|0.43992|0.00%|0.43974|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d79ed6b3e)|0.43896|0.44124|0.00046|0.43974|-0.04%|0.43969|-0.01%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/11937b3df7)|0.43932|0.44158|0.00055|0.44012|0.04%|0.44007|0.08%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11937b3df7)|0.42557|0.42836|0.00049|0.42661|-3.03%|0.42659|-2.99%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71409|0.71684|0.00073|0.71529|0.00%|0.71520|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d79ed6b3e)|0.71366|0.72946|0.00216|0.71483|-0.06%|0.71444|-0.11%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/11937b3df7)|0.71401|0.71742|0.00068|0.71554|0.04%|0.71538|0.03%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11937b3df7)|0.68345|0.68915|0.00091|0.68505|-4.23%|0.68499|-4.22%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58106|0.58501|0.00070|0.58257|0.00%|0.58251|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d79ed6b3e)|0.58016|0.58346|0.00058|0.58134|-0.21%|0.58132|-0.20%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/11937b3df7)|0.57988|0.58404|0.00070|0.58093|-0.28%|0.58095|-0.27%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11937b3df7)|0.52039|0.52300|0.00051|0.52165|-10.46%|0.52152|-10.47%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21460|0.21944|0.00117|0.21632|0.00%|0.21597|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d79ed6b3e)|0.21260|0.21744|0.00098|0.21449|-0.85%|0.21430|-0.77%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/11937b3df7)|0.21236|0.21933|0.00132|0.21406|-1.04%|0.21361|-1.09%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11937b3df7)|0.07511|0.07865|0.00072|0.07633|-64.71%|0.07617|-64.73%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34165|1.37174|0.00632|1.35434|0.00%|1.35357|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d79ed6b3e)|1.24827|1.27050|0.00442|1.25625|-7.24%|1.25675|-7.15%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/11937b3df7)|1.24713|1.26959|0.00412|1.25807|-7.11%|1.25792|-7.07%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11937b3df7)|0.53084|0.54852|0.00429|0.54051|-60.09%|0.54015|-60.09%|21.72 MB|
