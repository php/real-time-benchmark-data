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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-05-14 00:49:46 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43883|0.44943|0.00227|0.44053|0.00%|0.44000|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|0.43909|0.44617|0.00128|0.44054|0.00%|0.44028|0.07%|42.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|0.43891|0.44097|0.00047|0.43975|-0.18%|0.43965|-0.08%|42.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.42443|0.42647|0.00047|0.42520|-3.48%|0.42515|-3.37%|50.92 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71390|0.71764|0.00102|0.71525|0.00%|0.71506|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|0.70877|0.71245|0.00107|0.71019|-0.71%|0.70998|-0.71%|37.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|0.70860|0.72020|0.00200|0.70993|-0.74%|0.70944|-0.79%|37.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.68318|0.68590|0.00061|0.68427|-4.33%|0.68436|-4.29%|44.67 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58062|0.58346|0.00076|0.58190|0.00%|0.58188|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|0.57737|0.58353|0.00204|0.58069|-0.21%|0.58148|-0.07%|43.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|0.58072|0.58363|0.00054|0.58205|0.03%|0.58199|0.02%|43.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.52113|0.52271|0.00039|0.52215|-10.27%|0.52223|-10.25%|62.21 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21564|0.22036|0.00117|0.21727|0.00%|0.21700|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|0.21877|0.22281|0.00099|0.22063|1.55%|0.22058|1.65%|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|0.21744|0.21998|0.00053|0.21861|0.62%|0.21861|0.74%|26.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.07486|0.07847|0.00083|0.07648|-64.80%|0.07646|-64.76%|27.47 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34438|1.36051|0.00426|1.35179|0.00%|1.35118|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|1.29338|1.31037|0.00452|1.30087|-3.77%|1.30067|-3.74%|20.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/4122daa494)|1.29274|1.30687|0.00440|1.30030|-3.81%|1.30116|-3.70%|20.57 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4122daa494)|0.55151|0.57194|0.00454|0.55898|-58.65%|0.55791|-58.71%|21.89 MB|
