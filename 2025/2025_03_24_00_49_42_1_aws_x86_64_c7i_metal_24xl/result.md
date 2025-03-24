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
| Kernel        |6.1.129-138.220.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250303|
| GCC           |11.4.1|
| Time          |2025-03-24 00:49:42 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43902|0.44761|0.00148|0.43990|0.00%|0.43967|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a28fb52719)|0.43621|0.43836|0.00041|0.43692|-0.68%|0.43688|-0.63%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/345d229385)|0.43763|0.43938|0.00038|0.43827|-0.37%|0.43824|-0.33%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/345d229385)|0.42568|0.42709|0.00039|0.42648|-3.05%|0.42648|-3.00%|50.81 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71359|0.71637|0.00072|0.71483|0.00%|0.71505|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a28fb52719)|0.70916|0.72095|0.00205|0.71056|-0.60%|0.71009|-0.69%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/345d229385)|0.70802|0.71103|0.00077|0.70913|-0.80%|0.70904|-0.84%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/345d229385)|0.67863|0.68069|0.00049|0.67947|-4.95%|0.67949|-4.97%|44.57 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58084|0.58300|0.00049|0.58171|0.00%|0.58176|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a28fb52719)|0.57754|0.58278|0.00161|0.57896|-0.47%|0.57824|-0.60%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/345d229385)|0.57767|0.58057|0.00069|0.57880|-0.50%|0.57867|-0.53%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/345d229385)|0.52127|0.52372|0.00057|0.52246|-10.19%|0.52242|-10.20%|60.58 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21479|0.21800|0.00091|0.21602|0.00%|0.21583|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a28fb52719)|0.21434|0.21693|0.00065|0.21542|-0.28%|0.21539|-0.20%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/345d229385)|0.21610|0.22017|0.00105|0.21761|0.74%|0.21747|0.76%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/345d229385)|0.07431|0.07775|0.00073|0.07612|-64.76%|0.07617|-64.71%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33569|1.36068|0.00620|1.34916|0.00%|1.34976|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a28fb52719)|1.25044|1.27283|0.00589|1.26015|-6.60%|1.25939|-6.70%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/345d229385)|1.35107|1.38432|0.00748|1.36683|1.31%|1.36622|1.22%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/345d229385)|0.54513|0.57179|0.00721|0.55638|-58.76%|0.55511|-58.87%|21.80 MB|
