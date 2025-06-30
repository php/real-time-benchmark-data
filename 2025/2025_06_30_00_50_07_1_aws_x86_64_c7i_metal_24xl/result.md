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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-06-30 00:50:07 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43642|0.45114|0.00202|0.44184|0.00%|0.44158|0.00%|42.03 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/761478a032)|0.43949|0.44583|0.00113|0.44058|-0.29%|0.44036|-0.28%|42.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/db157e3168)|0.43927|0.44206|0.00078|0.44018|-0.38%|0.43997|-0.36%|42.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/db157e3168)|0.42357|0.42570|0.00045|0.42425|-3.98%|0.42420|-3.94%|51.60 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71362|0.71739|0.00087|0.71479|0.00%|0.71459|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/761478a032)|0.70634|0.71048|0.00100|0.70796|-0.96%|0.70773|-0.96%|38.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/db157e3168)|0.70554|0.70928|0.00082|0.70673|-1.13%|0.70661|-1.12%|38.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/db157e3168)|0.67890|0.68112|0.00062|0.67978|-4.90%|0.67974|-4.88%|45.21 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58134|0.58560|0.00114|0.58331|0.00%|0.58341|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/761478a032)|0.58168|0.58530|0.00073|0.58280|-0.09%|0.58267|-0.13%|43.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/db157e3168)|0.58260|0.58576|0.00090|0.58415|0.14%|0.58416|0.13%|43.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/db157e3168)|0.52432|0.52837|0.00099|0.52618|-9.79%|0.52615|-9.81%|61.65 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21368|0.21719|0.00087|0.21516|0.00%|0.21507|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/761478a032)|0.21619|0.22056|0.00096|0.21856|1.58%|0.21848|1.59%|26.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/db157e3168)|0.21456|0.21781|0.00098|0.21592|0.35%|0.21591|0.39%|26.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/db157e3168)|0.07545|0.07859|0.00087|0.07685|-64.28%|0.07691|-64.24%|28.01 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41887|1.43587|0.00466|1.42653|0.00%|1.42639|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/761478a032)|1.33072|1.34286|0.00319|1.33674|-6.29%|1.33714|-6.26%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/db157e3168)|1.29203|1.30623|0.00377|1.29885|-8.95%|1.29902|-8.93%|21.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/db157e3168)|0.55108|0.56926|0.00400|0.55962|-60.77%|0.55885|-60.82%|22.44 MB|
