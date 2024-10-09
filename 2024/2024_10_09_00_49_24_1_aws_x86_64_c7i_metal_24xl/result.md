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
| Time          |2024-10-09 00:49:24 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43760|0.44029|0.00059|0.43862|0.00%|0.43855|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edc94a8d21)|0.43643|0.43820|0.00045|0.43720|-0.32%|0.43717|-0.32%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd0ced3046)|0.43639|0.43845|0.00048|0.43724|-0.32%|0.43713|-0.32%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd0ced3046)|0.42470|0.42663|0.00050|0.42542|-3.01%|0.42532|-3.02%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71387|0.71742|0.00094|0.71519|0.00%|0.71489|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edc94a8d21)|0.70974|0.71353|0.00088|0.71148|-0.52%|0.71147|-0.48%|37.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd0ced3046)|0.71132|0.72052|0.00162|0.71258|-0.36%|0.71236|-0.35%|37.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd0ced3046)|0.68697|0.69034|0.00072|0.68830|-3.76%|0.68827|-3.72%|44.51 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57977|0.58260|0.00060|0.58075|0.00%|0.58078|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edc94a8d21)|0.57700|0.58017|0.00071|0.57825|-0.43%|0.57822|-0.44%|42.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd0ced3046)|0.57651|0.57842|0.00050|0.57752|-0.56%|0.57743|-0.58%|42.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd0ced3046)|0.51940|0.52117|0.00047|0.52018|-10.43%|0.52010|-10.45%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21492|0.21828|0.00092|0.21616|0.00%|0.21591|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edc94a8d21)|0.21612|0.21984|0.00087|0.21775|0.73%|0.21761|0.79%|26.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd0ced3046)|0.21508|0.21983|0.00115|0.21667|0.23%|0.21646|0.26%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd0ced3046)|0.07431|0.07778|0.00078|0.07572|-64.97%|0.07551|-65.03%|27.35 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34146|1.36128|0.00524|1.35326|0.00%|1.35404|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/edc94a8d21)|1.39862|1.42230|0.00569|1.41043|4.22%|1.41107|4.21%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/dd0ced3046)|1.35207|1.37572|0.00607|1.36707|1.02%|1.36751|0.99%|20.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dd0ced3046)|0.61954|0.63724|0.00505|0.62676|-53.68%|0.62540|-53.81%|21.76 MB|
