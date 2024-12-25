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
| Time          |2024-12-25 00:49:26 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43866|0.44081|0.00048|0.43976|0.00%|0.43974|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e9cde758e)|0.43639|0.43814|0.00038|0.43716|-0.59%|0.43713|-0.59%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/48b37fe384)|0.43677|0.43861|0.00050|0.43745|-0.53%|0.43734|-0.55%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/48b37fe384)|0.42435|0.42643|0.00040|0.42504|-3.35%|0.42500|-3.35%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71263|0.71623|0.00071|0.71425|0.00%|0.71423|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e9cde758e)|0.71061|0.71457|0.00086|0.71215|-0.29%|0.71199|-0.31%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/48b37fe384)|0.70995|0.71297|0.00061|0.71126|-0.42%|0.71110|-0.44%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/48b37fe384)|0.68338|0.68585|0.00062|0.68447|-4.17%|0.68432|-4.19%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58072|0.58482|0.00110|0.58227|0.00%|0.58214|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e9cde758e)|0.57868|0.58188|0.00065|0.57964|-0.45%|0.57956|-0.44%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/48b37fe384)|0.57411|0.58021|0.00138|0.57825|-0.69%|0.57852|-0.62%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/48b37fe384)|0.52086|0.52303|0.00046|0.52179|-10.39%|0.52181|-10.36%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21435|0.22063|0.00112|0.21612|0.00%|0.21581|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e9cde758e)|0.21575|0.22173|0.00133|0.21765|0.71%|0.21736|0.72%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/48b37fe384)|0.21546|0.22028|0.00103|0.21711|0.46%|0.21701|0.55%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/48b37fe384)|0.07367|0.07721|0.00083|0.07541|-65.11%|0.07533|-65.09%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33871|1.36646|0.00616|1.35187|0.00%|1.35170|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e9cde758e)|1.33259|1.36287|0.00641|1.35153|-0.03%|1.35241|0.05%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/48b37fe384)|1.33801|1.36159|0.00537|1.35085|-0.08%|1.35104|-0.05%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/48b37fe384)|0.52220|0.54829|0.00417|0.53487|-60.43%|0.53472|-60.44%|21.65 MB|
