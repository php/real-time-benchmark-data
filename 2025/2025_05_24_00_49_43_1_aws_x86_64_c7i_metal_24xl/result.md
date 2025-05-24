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
| Time          |2025-05-24 00:49:43 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43841|0.45264|0.00248|0.43943|0.00%|0.43897|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|0.43741|0.44060|0.00070|0.43878|-0.15%|0.43862|-0.08%|42.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|0.43745|0.44022|0.00071|0.43862|-0.18%|0.43845|-0.12%|42.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.42256|0.42400|0.00043|0.42311|-3.71%|0.42306|-3.62%|50.93 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71377|0.71708|0.00083|0.71497|0.00%|0.71474|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|0.71338|0.71729|0.00068|0.71481|-0.02%|0.71477|0.00%|37.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|0.71359|0.71817|0.00088|0.71498|0.00%|0.71485|0.02%|37.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.67953|0.68178|0.00061|0.68069|-4.79%|0.68053|-4.79%|44.68 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58141|0.59189|0.00183|0.58261|0.00%|0.58227|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|0.58078|0.58252|0.00043|0.58157|-0.18%|0.58161|-0.11%|43.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|0.58113|0.58460|0.00068|0.58197|-0.11%|0.58182|-0.08%|43.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.52505|0.52800|0.00059|0.52605|-9.71%|0.52590|-9.68%|60.77 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21573|0.21850|0.00071|0.21669|0.00%|0.21658|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|0.21827|0.22337|0.00134|0.22027|1.65%|0.21974|1.46%|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|0.21799|0.22512|0.00146|0.21970|1.39%|0.21932|1.26%|26.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.07518|0.07807|0.00065|0.07666|-64.62%|0.07666|-64.60%|27.49 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33759|1.36137|0.00556|1.34953|0.00%|1.34936|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dfff6ac852)|1.28761|1.30715|0.00446|1.29849|-3.78%|1.29893|-3.74%|20.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/dfff6ac852)|1.28251|1.29941|0.00370|1.29115|-4.33%|1.29097|-4.33%|20.66 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dfff6ac852)|0.54287|0.55689|0.00321|0.54913|-59.31%|0.54849|-59.35%|21.91 MB|
