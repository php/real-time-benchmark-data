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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20241001|
| GCC           |11.4.1|
| Time          |2024-10-12 00:49:14 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43770|0.44816|0.00180|0.43871|0.00%|0.43836|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e172f0ac1)|0.43573|0.43864|0.00056|0.43679|-0.44%|0.43673|-0.37%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/89533482a4)|0.43563|0.43744|0.00045|0.43661|-0.48%|0.43665|-0.39%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89533482a4)|0.42260|0.42367|0.00027|0.42317|-3.54%|0.42313|-3.47%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71353|0.71587|0.00058|0.71471|0.00%|0.71450|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e172f0ac1)|0.71014|0.71448|0.00098|0.71120|-0.49%|0.71101|-0.49%|37.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/89533482a4)|0.70859|0.71076|0.00063|0.70949|-0.73%|0.70950|-0.70%|37.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89533482a4)|0.68005|0.69251|0.00177|0.68759|-3.79%|0.68762|-3.76%|44.51 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57992|0.58227|0.00058|0.58086|0.00%|0.58074|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e172f0ac1)|0.57628|0.57860|0.00054|0.57713|-0.64%|0.57708|-0.63%|42.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/89533482a4)|0.57623|0.57795|0.00043|0.57721|-0.63%|0.57727|-0.60%|42.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89533482a4)|0.52006|0.52222|0.00044|0.52085|-10.33%|0.52077|-10.33%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21579|0.21894|0.00081|0.21686|0.00%|0.21653|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e172f0ac1)|0.21573|0.21869|0.00069|0.21746|0.28%|0.21754|0.47%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/89533482a4)|0.21538|0.21964|0.00102|0.21690|0.02%|0.21686|0.15%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89533482a4)|0.07442|0.07730|0.00075|0.07562|-65.13%|0.07540|-65.18%|27.35 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33987|1.36489|0.00616|1.35305|0.00%|1.35362|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e172f0ac1)|1.40492|1.44038|0.00860|1.42347|5.20%|1.42173|5.03%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/89533482a4)|1.39651|1.42091|0.00578|1.41148|4.32%|1.41201|4.31%|20.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89533482a4)|0.58774|0.61669|0.00550|0.59841|-55.77%|0.59732|-55.87%|21.76 MB|
