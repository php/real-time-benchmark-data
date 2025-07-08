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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-07-08 00:50:01 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43474|0.44222|0.00124|0.44104|0.00%|0.44122|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1ed6088a6)|0.43942|0.44145|0.00055|0.44024|-0.18%|0.44029|-0.21%|42.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/64e2832bc8)|0.43743|0.44034|0.00052|0.43858|-0.56%|0.43846|-0.63%|42.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64e2832bc8)|0.42238|0.42541|0.00061|0.42397|-3.87%|0.42387|-3.93%|51.61 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71459|0.71948|0.00087|0.71613|0.00%|0.71609|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1ed6088a6)|0.71096|0.71518|0.00108|0.71267|-0.48%|0.71273|-0.47%|38.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/64e2832bc8)|0.71113|0.72600|0.00325|0.71337|-0.39%|0.71262|-0.48%|38.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64e2832bc8)|0.68260|0.68599|0.00083|0.68404|-4.48%|0.68390|-4.50%|45.23 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58071|0.58373|0.00074|0.58237|0.00%|0.58228|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1ed6088a6)|0.58195|0.58485|0.00070|0.58336|0.17%|0.58310|0.14%|43.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/64e2832bc8)|0.58021|0.58249|0.00068|0.58136|-0.17%|0.58114|-0.20%|43.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64e2832bc8)|0.52395|0.52659|0.00065|0.52492|-9.87%|0.52481|-9.87%|61.66 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21419|0.21843|0.00110|0.21585|0.00%|0.21563|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1ed6088a6)|0.21884|0.22355|0.00109|0.22020|2.01%|0.21983|1.95%|26.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/64e2832bc8)|0.21608|0.22205|0.00118|0.21933|1.61%|0.21923|1.67%|26.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64e2832bc8)|0.07525|0.07866|0.00081|0.07698|-64.34%|0.07690|-64.34%|28.02 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42223|1.43825|0.00392|1.42968|0.00%|1.42915|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c1ed6088a6)|1.28759|1.29911|0.00284|1.29226|-9.61%|1.29190|-9.60%|21.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/64e2832bc8)|1.55872|1.57295|0.00387|1.56577|9.52%|1.56590|9.57%|21.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/64e2832bc8)|0.54960|0.56070|0.00313|0.55498|-61.18%|0.55538|-61.14%|22.47 MB|
