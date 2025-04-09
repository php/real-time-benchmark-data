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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-09 00:49:37 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43847|0.44052|0.00044|0.43944|0.00%|0.43951|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/633400bb56)|0.43653|0.43912|0.00066|0.43741|-0.46%|0.43728|-0.51%|41.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/c20b429a90)|0.43742|0.43983|0.00052|0.43814|-0.30%|0.43813|-0.31%|41.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c20b429a90)|0.42472|0.42600|0.00031|0.42529|-3.22%|0.42524|-3.25%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71216|0.71854|0.00114|0.71379|0.00%|0.71358|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/633400bb56)|0.70938|0.71258|0.00074|0.71051|-0.46%|0.71031|-0.46%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/c20b429a90)|0.70582|0.70821|0.00053|0.70665|-1.00%|0.70659|-0.98%|37.57 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c20b429a90)|0.67607|0.68315|0.00118|0.68135|-4.55%|0.68130|-4.52%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58062|0.58368|0.00057|0.58151|0.00%|0.58148|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/633400bb56)|0.57983|0.58164|0.00043|0.58084|-0.12%|0.58084|-0.11%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/c20b429a90)|0.57736|0.58038|0.00074|0.57890|-0.45%|0.57882|-0.46%|42.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c20b429a90)|0.52130|0.52284|0.00045|0.52197|-10.24%|0.52194|-10.24%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21513|0.22001|0.00103|0.21662|0.00%|0.21654|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/633400bb56)|0.21745|0.22163|0.00096|0.21999|1.55%|0.22006|1.63%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/c20b429a90)|0.21600|0.21848|0.00067|0.21704|0.19%|0.21692|0.18%|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c20b429a90)|0.07520|0.07830|0.00078|0.07650|-64.69%|0.07645|-64.70%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33586|1.35957|0.00536|1.34577|0.00%|1.34556|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/633400bb56)|1.29153|1.31236|0.00573|1.30184|-3.26%|1.30154|-3.27%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/c20b429a90)|1.30362|1.32121|0.00441|1.31374|-2.38%|1.31519|-2.26%|20.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c20b429a90)|0.54493|0.56693|0.00660|0.55740|-58.58%|0.55867|-58.48%|21.82 MB|
