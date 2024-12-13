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
| Time          |2024-12-13 00:49:43 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43883|0.44136|0.00048|0.43986|0.00%|0.43984|0.00%|41.83 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4ef1c5fb91)|0.43626|0.43868|0.00047|0.43716|-0.61%|0.43708|-0.63%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/c630801ae7)|0.43673|0.44455|0.00105|0.43786|-0.45%|0.43770|-0.49%|41.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c630801ae7)|0.42485|0.42630|0.00036|0.42545|-3.28%|0.42535|-3.30%|50.76 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71400|0.72819|0.00200|0.71532|0.00%|0.71495|0.00%|37.35 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4ef1c5fb91)|0.70792|0.72591|0.00247|0.70976|-0.78%|0.70935|-0.78%|37.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/c630801ae7)|0.70771|0.71099|0.00079|0.70880|-0.91%|0.70856|-0.89%|37.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c630801ae7)|0.68188|0.68409|0.00053|0.68293|-4.53%|0.68294|-4.48%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58210|0.58507|0.00059|0.58291|0.00%|0.58278|0.00%|42.97 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4ef1c5fb91)|0.57842|0.58098|0.00059|0.57935|-0.61%|0.57925|-0.61%|42.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/c630801ae7)|0.57807|0.58085|0.00064|0.57927|-0.62%|0.57911|-0.63%|42.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c630801ae7)|0.52115|0.52419|0.00062|0.52226|-10.41%|0.52212|-10.41%|61.64 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21451|0.21927|0.00102|0.21590|0.00%|0.21570|0.00%|26.14 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4ef1c5fb91)|0.21491|0.21978|0.00103|0.21668|0.36%|0.21643|0.34%|26.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/c630801ae7)|0.21548|0.21997|0.00098|0.21706|0.54%|0.21700|0.60%|26.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c630801ae7)|0.07400|0.07712|0.00072|0.07554|-65.01%|0.07558|-64.96%|27.24 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34286|1.36971|0.00630|1.35443|0.00%|1.35462|0.00%|20.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4ef1c5fb91)|1.32448|1.35094|0.00562|1.33673|-1.31%|1.33753|-1.26%|20.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/c630801ae7)|1.32555|1.35066|0.00491|1.33731|-1.26%|1.33756|-1.26%|20.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c630801ae7)|0.52909|0.55749|0.00583|0.54437|-59.81%|0.54366|-59.87%|21.66 MB|
