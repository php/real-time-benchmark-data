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
| Time          |2025-03-11 00:49:31 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44049|0.44329|0.00067|0.44135|0.00%|0.44111|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33c4ca36e4)|0.43923|0.44203|0.00058|0.44034|-0.23%|0.44031|-0.18%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/9d60dc16b8)|0.43928|0.44314|0.00077|0.44036|-0.22%|0.44025|-0.20%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9d60dc16b8)|0.42695|0.42911|0.00047|0.42789|-3.05%|0.42799|-2.98%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71600|0.71965|0.00079|0.71722|0.00%|0.71713|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33c4ca36e4)|0.70876|0.71241|0.00098|0.71003|-1.00%|0.70975|-1.03%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/9d60dc16b8)|0.70852|0.71983|0.00197|0.70994|-1.02%|0.70941|-1.08%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9d60dc16b8)|0.68303|0.68609|0.00078|0.68430|-4.59%|0.68430|-4.58%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58139|0.58345|0.00053|0.58245|0.00%|0.58237|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33c4ca36e4)|0.57859|0.58104|0.00060|0.57960|-0.49%|0.57956|-0.48%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/9d60dc16b8)|0.57856|0.58114|0.00081|0.57938|-0.53%|0.57909|-0.56%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9d60dc16b8)|0.52089|0.52228|0.00039|0.52150|-10.47%|0.52153|-10.45%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21603|0.21950|0.00090|0.21724|0.00%|0.21707|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33c4ca36e4)|0.21387|0.21597|0.00058|0.21495|-1.05%|0.21492|-0.99%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/9d60dc16b8)|0.21163|0.21574|0.00086|0.21290|-2.00%|0.21273|-2.00%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9d60dc16b8)|0.07534|0.07758|0.00060|0.07652|-64.78%|0.07636|-64.82%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34329|1.36506|0.00568|1.35158|0.00%|1.34944|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33c4ca36e4)|1.25896|1.27312|0.00391|1.26659|-6.29%|1.26664|-6.14%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/9d60dc16b8)|1.25794|1.27557|0.00431|1.26512|-6.40%|1.26486|-6.27%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9d60dc16b8)|0.52575|0.54100|0.00318|0.53479|-60.43%|0.53489|-60.36%|21.79 MB|
