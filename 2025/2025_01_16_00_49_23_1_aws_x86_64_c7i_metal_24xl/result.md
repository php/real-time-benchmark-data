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
| OS            |Amazon Linux 2023.6.20250107|
| GCC           |11.4.1|
| Time          |2025-01-16 00:49:23 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43865|0.44119|0.00054|0.43963|0.00%|0.43952|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4c84ed4d98)|0.43874|0.44163|0.00059|0.43954|-0.02%|0.43945|-0.02%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/39f1d253b1)|0.43926|0.44575|0.00090|0.44022|0.13%|0.44007|0.13%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39f1d253b1)|0.42695|0.42838|0.00034|0.42765|-2.73%|0.42767|-2.70%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71438|0.72857|0.00194|0.71544|0.00%|0.71503|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4c84ed4d98)|0.71162|0.72761|0.00218|0.71286|-0.36%|0.71256|-0.35%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/39f1d253b1)|0.71134|0.71538|0.00075|0.71268|-0.39%|0.71258|-0.34%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39f1d253b1)|0.68526|0.68768|0.00063|0.68633|-4.07%|0.68619|-4.03%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58117|0.58357|0.00052|0.58202|0.00%|0.58189|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4c84ed4d98)|0.57762|0.58088|0.00062|0.57876|-0.56%|0.57870|-0.55%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/39f1d253b1)|0.57845|0.58131|0.00055|0.57981|-0.38%|0.57976|-0.37%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39f1d253b1)|0.52139|0.52752|0.00089|0.52230|-10.26%|0.52215|-10.27%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21553|0.22155|0.00123|0.21726|0.00%|0.21680|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4c84ed4d98)|0.21506|0.21901|0.00097|0.21659|-0.31%|0.21650|-0.14%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/39f1d253b1)|0.21528|0.22022|0.00118|0.21723|-0.01%|0.21701|0.09%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39f1d253b1)|0.07498|0.07714|0.00055|0.07612|-64.96%|0.07605|-64.92%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34234|1.37477|0.00617|1.35388|0.00%|1.35334|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4c84ed4d98)|1.26741|1.28799|0.00416|1.27783|-5.62%|1.27823|-5.55%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/39f1d253b1)|1.33136|1.35103|0.00423|1.33809|-1.17%|1.33732|-1.18%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39f1d253b1)|0.53147|0.55666|0.00535|0.54253|-59.93%|0.54227|-59.93%|21.72 MB|
