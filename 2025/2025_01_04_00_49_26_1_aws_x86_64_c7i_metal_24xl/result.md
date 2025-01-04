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
| Time          |2025-01-04 00:49:26 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43859|0.44425|0.00075|0.43974|0.00%|0.43961|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60252b7845)|0.43538|0.43775|0.00053|0.43617|-0.81%|0.43605|-0.81%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/209e0d6ad2)|0.43539|0.44279|0.00101|0.43637|-0.77%|0.43620|-0.78%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/209e0d6ad2)|0.42525|0.42744|0.00045|0.42608|-3.11%|0.42604|-3.09%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71258|0.71601|0.00079|0.71404|0.00%|0.71384|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60252b7845)|0.70780|0.71161|0.00084|0.70926|-0.67%|0.70908|-0.67%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/209e0d6ad2)|0.70785|0.71246|0.00075|0.70976|-0.60%|0.70970|-0.58%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/209e0d6ad2)|0.68141|0.68396|0.00065|0.68275|-4.38%|0.68267|-4.37%|44.48 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58072|0.58332|0.00052|0.58189|0.00%|0.58184|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60252b7845)|0.57741|0.58123|0.00068|0.57843|-0.59%|0.57834|-0.60%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/209e0d6ad2)|0.57289|0.57979|0.00165|0.57779|-0.70%|0.57838|-0.60%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/209e0d6ad2)|0.51959|0.52150|0.00048|0.52058|-10.54%|0.52058|-10.53%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21487|0.21951|0.00110|0.21635|0.00%|0.21607|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60252b7845)|0.21447|0.21761|0.00070|0.21595|-0.18%|0.21596|-0.05%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/209e0d6ad2)|0.21449|0.21903|0.00088|0.21608|-0.12%|0.21603|-0.02%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/209e0d6ad2)|0.07331|0.07765|0.00089|0.07514|-65.27%|0.07497|-65.30%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34132|1.36660|0.00570|1.35485|0.00%|1.35627|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/60252b7845)|1.30632|1.33199|0.00616|1.31863|-2.67%|1.31839|-2.79%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/209e0d6ad2)|1.26012|1.28259|0.00441|1.26933|-6.31%|1.26911|-6.43%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/209e0d6ad2)|0.54027|0.56226|0.00554|0.55135|-59.31%|0.55248|-59.26%|21.66 MB|
