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
| Time          |2024-12-23 00:49:33 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43899|0.44129|0.00055|0.43978|0.00%|0.43971|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/26244c7dcd)|0.43552|0.43732|0.00039|0.43619|-0.82%|0.43619|-0.80%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.43660|0.43913|0.00044|0.43766|-0.48%|0.43755|-0.49%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.42440|0.42601|0.00037|0.42516|-3.33%|0.42511|-3.32%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71332|0.71604|0.00067|0.71467|0.00%|0.71465|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/26244c7dcd)|0.71379|0.71685|0.00070|0.71527|0.08%|0.71524|0.08%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.71075|0.71420|0.00075|0.71249|-0.30%|0.71248|-0.30%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.68424|0.68666|0.00054|0.68540|-4.10%|0.68531|-4.10%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58199|0.58427|0.00050|0.58284|0.00%|0.58277|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/26244c7dcd)|0.57948|0.58254|0.00065|0.58058|-0.39%|0.58049|-0.39%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.57371|0.58161|0.00210|0.57751|-0.91%|0.57867|-0.70%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.52100|0.52311|0.00049|0.52210|-10.42%|0.52210|-10.41%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21481|0.21968|0.00110|0.21637|0.00%|0.21613|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/26244c7dcd)|0.21585|0.21882|0.00076|0.21674|0.17%|0.21652|0.18%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.21495|0.22044|0.00131|0.21693|0.26%|0.21666|0.24%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.07410|0.07790|0.00082|0.07569|-65.02%|0.07565|-65.00%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34279|1.36858|0.00607|1.35596|0.00%|1.35621|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/26244c7dcd)|1.33423|1.35846|0.00536|1.34448|-0.85%|1.34457|-0.86%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5e6c5f2d)|1.33880|1.36440|0.00562|1.35288|-0.23%|1.35368|-0.19%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5e6c5f2d)|0.52622|0.54337|0.00334|0.53631|-60.45%|0.53629|-60.46%|21.65 MB|
