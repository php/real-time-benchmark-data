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
| Kernel        |6.1.112-124.190.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241031|
| GCC           |11.4.1|
| Time          |2024-11-07 00:49:20 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43775|0.44014|0.00050|0.43900|0.00%|0.43904|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/228c27112a)|0.43570|0.43808|0.00048|0.43656|-0.56%|0.43644|-0.59%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/96d1cd00b7)|0.43590|0.43921|0.00054|0.43700|-0.46%|0.43696|-0.47%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96d1cd00b7)|0.42623|0.42755|0.00033|0.42683|-2.77%|0.42682|-2.78%|50.85 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71867|0.72164|0.00067|0.71998|0.00%|0.71986|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/228c27112a)|0.71267|0.71715|0.00094|0.71395|-0.84%|0.71368|-0.86%|37.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/96d1cd00b7)|0.71076|0.71542|0.00095|0.71259|-1.03%|0.71248|-1.03%|37.49 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96d1cd00b7)|0.68605|0.69293|0.00096|0.69147|-3.96%|0.69143|-3.95%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58113|0.58467|0.00075|0.58335|0.00%|0.58333|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/228c27112a)|0.57812|0.58473|0.00221|0.58113|-0.38%|0.58240|-0.16%|43.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/96d1cd00b7)|0.58102|0.58362|0.00055|0.58185|-0.26%|0.58177|-0.27%|43.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96d1cd00b7)|0.52271|0.52489|0.00049|0.52367|-10.23%|0.52364|-10.23%|61.99 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21493|0.21950|0.00114|0.21647|0.00%|0.21621|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/228c27112a)|0.21155|0.21550|0.00079|0.21297|-1.62%|0.21279|-1.58%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/96d1cd00b7)|0.21500|0.22086|0.00121|0.21776|0.59%|0.21785|0.76%|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96d1cd00b7)|0.07322|0.07719|0.00094|0.07488|-65.41%|0.07495|-65.33%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34063|1.36118|0.00479|1.34980|0.00%|1.34953|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/228c27112a)|1.28424|1.30476|0.00448|1.29537|-4.03%|1.29588|-3.98%|20.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/96d1cd00b7)|1.29094|1.31401|0.00509|1.30058|-3.65%|1.30049|-3.63%|20.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96d1cd00b7)|0.53420|0.55840|0.00508|0.54574|-59.57%|0.54518|-59.60%|21.80 MB|
