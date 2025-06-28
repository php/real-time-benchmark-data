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
| Time          |2025-06-28 00:49:49 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44050|0.44179|0.00037|0.44113|0.00%|0.44112|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1b7f4567cb)|0.43855|0.44047|0.00046|0.43939|-0.39%|0.43933|-0.41%|42.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/22e444c5c7)|0.43887|0.44094|0.00044|0.43954|-0.36%|0.43946|-0.38%|42.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/22e444c5c7)|0.42649|0.42778|0.00035|0.42723|-3.15%|0.42723|-3.15%|51.58 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71355|0.71691|0.00078|0.71477|0.00%|0.71459|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1b7f4567cb)|0.70739|0.71219|0.00108|0.70947|-0.74%|0.70924|-0.75%|38.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/22e444c5c7)|0.70768|0.71263|0.00115|0.70913|-0.79%|0.70890|-0.80%|38.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/22e444c5c7)|0.67928|0.68118|0.00055|0.68016|-4.84%|0.68005|-4.83%|45.20 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58005|0.58256|0.00057|0.58146|0.00%|0.58138|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1b7f4567cb)|0.57888|0.58223|0.00072|0.58030|-0.20%|0.58021|-0.20%|43.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/22e444c5c7)|0.57993|0.58338|0.00076|0.58173|0.05%|0.58188|0.09%|43.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/22e444c5c7)|0.52383|0.52646|0.00058|0.52505|-9.70%|0.52493|-9.71%|61.63 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21437|0.21922|0.00132|0.21654|0.00%|0.21611|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1b7f4567cb)|0.21629|0.22189|0.00133|0.21905|1.16%|0.21914|1.40%|26.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/22e444c5c7)|0.21728|0.21927|0.00049|0.21817|0.75%|0.21808|0.91%|26.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/22e444c5c7)|0.07524|0.07750|0.00060|0.07656|-64.65%|0.07655|-64.58%|28.00 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42112|1.44503|0.00537|1.42922|0.00%|1.42861|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1b7f4567cb)|1.31245|1.32784|0.00419|1.31962|-7.67%|1.31990|-7.61%|21.04 MB|
|[PHP - master](https://github.com/php/php-src/commit/22e444c5c7)|1.30635|1.32799|0.00457|1.31952|-7.68%|1.32036|-7.58%|21.04 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/22e444c5c7)|0.56045|0.58075|0.00502|0.57276|-59.93%|0.57357|-59.85%|22.43 MB|
