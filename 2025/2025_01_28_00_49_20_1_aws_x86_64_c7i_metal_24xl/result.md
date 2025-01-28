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
| Kernel        |6.1.124-134.200.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250123|
| GCC           |11.4.1|
| Time          |2025-01-28 00:49:20 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43890|0.44844|0.00146|0.43996|0.00%|0.43967|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60ee42eb3e)|0.43842|0.44190|0.00075|0.43951|-0.10%|0.43939|-0.06%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/06c41ec6c5)|0.43706|0.44143|0.00074|0.43913|-0.19%|0.43906|-0.14%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06c41ec6c5)|0.42712|0.42994|0.00062|0.42848|-2.61%|0.42849|-2.54%|50.79 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71325|0.71892|0.00109|0.71622|0.00%|0.71610|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60ee42eb3e)|0.71638|0.73304|0.00229|0.71907|0.40%|0.71884|0.38%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/06c41ec6c5)|0.71273|0.71695|0.00095|0.71566|-0.08%|0.71585|-0.04%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06c41ec6c5)|0.68457|0.69251|0.00128|0.69013|-3.64%|0.69023|-3.61%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58142|0.58540|0.00084|0.58282|0.00%|0.58270|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60ee42eb3e)|0.57714|0.58110|0.00087|0.57898|-0.66%|0.57898|-0.64%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/06c41ec6c5)|0.57865|0.58292|0.00112|0.58083|-0.34%|0.58088|-0.31%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06c41ec6c5)|0.51941|0.52305|0.00096|0.52134|-10.55%|0.52134|-10.53%|62.47 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21438|0.21888|0.00101|0.21592|0.00%|0.21561|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60ee42eb3e)|0.21543|0.21858|0.00070|0.21680|0.41%|0.21681|0.56%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/06c41ec6c5)|0.21553|0.21936|0.00092|0.21702|0.51%|0.21690|0.60%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06c41ec6c5)|0.07468|0.07739|0.00062|0.07600|-64.80%|0.07585|-64.82%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33944|1.36726|0.00658|1.35259|0.00%|1.35134|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60ee42eb3e)|1.26710|1.29291|0.00596|1.27883|-5.45%|1.27776|-5.44%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/06c41ec6c5)|1.31398|1.33200|0.00426|1.32316|-2.18%|1.32269|-2.12%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06c41ec6c5)|0.54552|0.56901|0.00489|0.55520|-58.95%|0.55555|-58.89%|21.71 MB|
