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
| Time          |2024-12-14 00:49:36 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43882|0.44726|0.00114|0.43984|0.00%|0.43968|0.00%|41.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c630801ae7)|0.43618|0.44370|0.00105|0.43709|-0.63%|0.43693|-0.63%|41.68 MB|
|[PHP - master](https://github.com/php/php-src/commit/bb6dbdcf94)|0.43181|0.43935|0.00104|0.43839|-0.33%|0.43849|-0.27%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bb6dbdcf94)|0.42548|0.42798|0.00046|0.42644|-3.05%|0.42636|-3.03%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71314|0.72973|0.00302|0.71524|0.00%|0.71453|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c630801ae7)|0.70752|0.71216|0.00083|0.70925|-0.84%|0.70912|-0.76%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/bb6dbdcf94)|0.70741|0.71099|0.00068|0.70916|-0.85%|0.70914|-0.75%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bb6dbdcf94)|0.68107|0.68444|0.00078|0.68263|-4.56%|0.68249|-4.48%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58133|0.58398|0.00060|0.58241|0.00%|0.58235|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c630801ae7)|0.57800|0.58043|0.00055|0.57883|-0.61%|0.57874|-0.62%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/bb6dbdcf94)|0.57683|0.57943|0.00054|0.57795|-0.77%|0.57780|-0.78%|42.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bb6dbdcf94)|0.51928|0.52198|0.00053|0.52032|-10.66%|0.52028|-10.66%|61.62 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21474|0.21789|0.00070|0.21606|0.00%|0.21593|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c630801ae7)|0.21536|0.21863|0.00080|0.21660|0.25%|0.21648|0.25%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/bb6dbdcf94)|0.21435|0.21969|0.00109|0.21602|-0.02%|0.21579|-0.06%|26.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bb6dbdcf94)|0.07367|0.07715|0.00086|0.07510|-65.24%|0.07508|-65.23%|27.22 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33671|1.36355|0.00590|1.35207|0.00%|1.35166|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c630801ae7)|1.32864|1.34762|0.00442|1.33677|-1.13%|1.33612|-1.15%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/bb6dbdcf94)|1.26411|1.28437|0.00451|1.27532|-5.68%|1.27608|-5.59%|20.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bb6dbdcf94)|0.53993|0.55815|0.00420|0.54897|-59.40%|0.54915|-59.37%|21.64 MB|
