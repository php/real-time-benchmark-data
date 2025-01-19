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
| OS            |Amazon Linux 2023.6.20250114|
| GCC           |11.4.1|
| Time          |2025-01-15 00:49:34 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43841|0.44663|0.00113|0.43963|0.00%|0.43946|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e1fbf97f4)|0.43757|0.44640|0.00121|0.43890|-0.17%|0.43874|-0.16%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c84ed4d98)|0.44006|0.44256|0.00052|0.44090|0.29%|0.44082|0.31%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c84ed4d98)|0.42722|0.42897|0.00040|0.42789|-2.67%|0.42779|-2.65%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71364|0.72885|0.00212|0.71515|0.00%|0.71475|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e1fbf97f4)|0.70734|0.71066|0.00081|0.70874|-0.90%|0.70865|-0.85%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c84ed4d98)|0.70998|0.71404|0.00085|0.71153|-0.51%|0.71124|-0.49%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c84ed4d98)|0.68155|0.68467|0.00067|0.68293|-4.51%|0.68292|-4.45%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58082|0.59136|0.00147|0.58209|0.00%|0.58186|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e1fbf97f4)|0.57766|0.58211|0.00090|0.57996|-0.37%|0.58004|-0.31%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c84ed4d98)|0.57746|0.57994|0.00057|0.57868|-0.59%|0.57866|-0.55%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c84ed4d98)|0.51905|0.52144|0.00049|0.52050|-10.58%|0.52049|-10.55%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21459|0.22009|0.00088|0.21608|0.00%|0.21584|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e1fbf97f4)|0.21646|0.22037|0.00083|0.21804|0.91%|0.21784|0.93%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c84ed4d98)|0.21424|0.21847|0.00095|0.21608|0.00%|0.21611|0.12%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c84ed4d98)|0.07181|0.07721|0.00159|0.07396|-65.77%|0.07351|-65.94%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33815|1.37326|0.00789|1.35575|0.00%|1.35516|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e1fbf97f4)|1.28728|1.31142|0.00514|1.30264|-3.92%|1.30367|-3.80%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/4c84ed4d98)|1.26434|1.28307|0.00419|1.27608|-5.88%|1.27612|-5.83%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4c84ed4d98)|0.55048|0.57207|0.00528|0.56091|-58.63%|0.56057|-58.63%|21.72 MB|