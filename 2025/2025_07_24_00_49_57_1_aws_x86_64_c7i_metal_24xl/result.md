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
| Kernel        |6.1.141-165.249.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250715|
| GCC           |11.5.0|
| Time          |2025-07-24 00:49:57 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43639|0.44278|0.00140|0.44194|0.00%|0.44236|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d292968f7c)|0.43737|0.44152|0.00082|0.44032|-0.37%|0.44035|-0.45%|42.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/2645663d9b)|0.43896|0.44127|0.00059|0.44010|-0.41%|0.44005|-0.52%|42.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2645663d9b)|0.42443|0.42671|0.00063|0.42548|-3.72%|0.42535|-3.85%|51.46 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71613|0.71927|0.00082|0.71765|0.00%|0.71780|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d292968f7c)|0.71451|0.71848|0.00092|0.71603|-0.23%|0.71594|-0.26%|38.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/2645663d9b)|0.71426|0.71715|0.00062|0.71593|-0.24%|0.71594|-0.26%|38.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2645663d9b)|0.68300|0.68593|0.00067|0.68408|-4.68%|0.68391|-4.72%|45.07 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58186|0.58485|0.00063|0.58265|0.00%|0.58254|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d292968f7c)|0.58037|0.58233|0.00051|0.58138|-0.22%|0.58144|-0.19%|43.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/2645663d9b)|0.58078|0.58388|0.00065|0.58172|-0.16%|0.58163|-0.16%|43.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2645663d9b)|0.52581|0.52817|0.00054|0.52688|-9.57%|0.52683|-9.56%|62.43 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21391|0.21978|0.00127|0.21584|0.00%|0.21545|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d292968f7c)|0.21630|0.22149|0.00124|0.21822|1.10%|0.21817|1.26%|26.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/2645663d9b)|0.21513|0.21944|0.00113|0.21671|0.40%|0.21649|0.48%|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2645663d9b)|0.07543|0.07848|0.00083|0.07659|-64.52%|0.07640|-64.54%|27.91 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.41412|1.44205|0.00604|1.42926|0.00%|1.42878|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d292968f7c)|1.29100|1.31170|0.00576|1.29888|-9.12%|1.29930|-9.06%|21.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/2645663d9b)|1.28276|1.31069|0.00626|1.29875|-9.13%|1.29948|-9.05%|21.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2645663d9b)|0.56047|0.58125|0.00546|0.57085|-60.06%|0.57036|-60.08%|22.36 MB|
