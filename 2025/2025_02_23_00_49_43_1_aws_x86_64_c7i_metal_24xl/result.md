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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-02-23 00:49:43 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43968|0.44796|0.00143|0.44066|0.00%|0.44031|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49d798abcc)|0.43594|0.43892|0.00066|0.43679|-0.88%|0.43658|-0.85%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1841fdfa2)|0.43558|0.44297|0.00129|0.43673|-0.89%|0.43651|-0.86%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1841fdfa2)|0.42533|0.42711|0.00051|0.42606|-3.31%|0.42604|-3.24%|50.78 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71274|0.71562|0.00075|0.71406|0.00%|0.71407|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49d798abcc)|0.69641|0.70743|0.00175|0.70455|-1.33%|0.70468|-1.31%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1841fdfa2)|0.70470|0.70881|0.00080|0.70573|-1.17%|0.70562|-1.18%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1841fdfa2)|0.67865|0.68415|0.00101|0.68061|-4.68%|0.68038|-4.72%|44.54 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58143|0.58433|0.00055|0.58275|0.00%|0.58276|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49d798abcc)|0.57973|0.58254|0.00054|0.58086|-0.32%|0.58077|-0.34%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1841fdfa2)|0.57971|0.58219|0.00058|0.58088|-0.32%|0.58081|-0.33%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1841fdfa2)|0.52108|0.52324|0.00045|0.52210|-10.41%|0.52210|-10.41%|61.90 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21481|0.21902|0.00110|0.21638|0.00%|0.21609|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49d798abcc)|0.21334|0.21758|0.00077|0.21509|-0.60%|0.21503|-0.49%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1841fdfa2)|0.21199|0.21478|0.00071|0.21304|-1.54%|0.21288|-1.48%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1841fdfa2)|0.07511|0.07767|0.00060|0.07619|-64.79%|0.07611|-64.78%|27.36 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34251|1.35888|0.00444|1.34905|0.00%|1.34993|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49d798abcc)|1.25461|1.28117|0.00679|1.26376|-6.32%|1.26227|-6.49%|20.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1841fdfa2)|1.25146|1.26755|0.00410|1.26128|-6.51%|1.26203|-6.51%|20.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1841fdfa2)|0.53904|0.56423|0.00612|0.55277|-59.03%|0.55370|-58.98%|21.78 MB|
