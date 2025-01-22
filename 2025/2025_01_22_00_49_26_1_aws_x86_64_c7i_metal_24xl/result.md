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
| Time          |2025-01-22 00:49:26 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43872|0.45325|0.00194|0.44011|0.00%|0.43978|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f8340d0a5)|0.43866|0.44085|0.00044|0.43949|-0.14%|0.43945|-0.08%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/3337f22eb1)|0.43743|0.43956|0.00051|0.43841|-0.38%|0.43831|-0.33%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3337f22eb1)|0.42660|0.42886|0.00048|0.42747|-2.87%|0.42741|-2.81%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71344|0.71617|0.00064|0.71482|0.00%|0.71472|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f8340d0a5)|0.71093|0.71362|0.00065|0.71207|-0.38%|0.71194|-0.39%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/3337f22eb1)|0.71215|0.71548|0.00070|0.71381|-0.14%|0.71373|-0.14%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3337f22eb1)|0.68542|0.68854|0.00071|0.68721|-3.86%|0.68731|-3.83%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58084|0.58429|0.00078|0.58229|0.00%|0.58230|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f8340d0a5)|0.57738|0.58181|0.00097|0.57936|-0.50%|0.57936|-0.50%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/3337f22eb1)|0.57530|0.57826|0.00065|0.57711|-0.89%|0.57712|-0.89%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3337f22eb1)|0.51898|0.52119|0.00047|0.51994|-10.71%|0.51992|-10.71%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21506|0.21909|0.00098|0.21645|0.00%|0.21619|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f8340d0a5)|0.21509|0.21966|0.00096|0.21683|0.18%|0.21667|0.22%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/3337f22eb1)|0.21471|0.21742|0.00069|0.21620|-0.11%|0.21614|-0.02%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3337f22eb1)|0.07469|0.07771|0.00074|0.07614|-64.82%|0.07601|-64.84%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34127|1.36660|0.00580|1.35180|0.00%|1.35142|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f8340d0a5)|1.26909|1.28538|0.00415|1.27756|-5.49%|1.27721|-5.49%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/3337f22eb1)|1.32128|1.34262|0.00516|1.33301|-1.39%|1.33267|-1.39%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3337f22eb1)|0.53447|0.56283|0.00678|0.54858|-59.42%|0.54844|-59.42%|21.72 MB|
