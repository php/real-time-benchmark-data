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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-10-26 00:49:17 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43826|0.44049|0.00052|0.43926|0.00%|0.43924|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1e08c15512)|0.43587|0.43763|0.00040|0.43655|-0.62%|0.43647|-0.63%|41.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/bfca4c7ba9)|0.43659|0.43950|0.00052|0.43784|-0.33%|0.43776|-0.34%|41.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bfca4c7ba9)|0.42753|0.42891|0.00033|0.42826|-2.51%|0.42826|-2.50%|50.76 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71978|0.72275|0.00075|0.72085|0.00%|0.72076|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1e08c15512)|0.71142|0.72854|0.00233|0.71279|-1.12%|0.71242|-1.16%|37.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/bfca4c7ba9)|0.71186|0.71421|0.00067|0.71278|-1.12%|0.71255|-1.14%|37.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bfca4c7ba9)|0.69029|0.69381|0.00071|0.69162|-4.05%|0.69156|-4.05%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58202|0.58498|0.00060|0.58286|0.00%|0.58268|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1e08c15512)|0.57473|0.58357|0.00212|0.57868|-0.72%|0.57967|-0.52%|42.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/bfca4c7ba9)|0.57944|0.58241|0.00060|0.58090|-0.34%|0.58081|-0.32%|42.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bfca4c7ba9)|0.52282|0.52468|0.00047|0.52382|-10.13%|0.52380|-10.10%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21500|0.21833|0.00087|0.21660|0.00%|0.21659|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1e08c15512)|0.21577|0.22069|0.00104|0.21726|0.31%|0.21700|0.19%|26.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/bfca4c7ba9)|0.21497|0.21894|0.00085|0.21650|-0.05%|0.21645|-0.06%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bfca4c7ba9)|0.07427|0.07759|0.00061|0.07550|-65.14%|0.07543|-65.17%|27.25 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33811|1.36623|0.00624|1.35224|0.00%|1.35364|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1e08c15512)|1.28134|1.30001|0.00359|1.28949|-4.64%|1.28904|-4.77%|20.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/bfca4c7ba9)|1.25200|1.27070|0.00466|1.26059|-6.78%|1.26002|-6.92%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bfca4c7ba9)|0.54531|0.56781|0.00470|0.55255|-59.14%|0.55120|-59.28%|21.66 MB|
