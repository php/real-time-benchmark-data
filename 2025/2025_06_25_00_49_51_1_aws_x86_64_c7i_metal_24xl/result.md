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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-25 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44047|0.44999|0.00160|0.44169|0.00%|0.44140|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecc602e3bb)|0.43953|0.44147|0.00046|0.44048|-0.27%|0.44051|-0.20%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/aab281546c)|0.43865|0.44173|0.00085|0.43964|-0.46%|0.43941|-0.45%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aab281546c)|0.42642|0.42798|0.00043|0.42706|-3.31%|0.42701|-3.26%|51.41 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71676|0.71986|0.00070|0.71818|0.00%|0.71805|0.00%|37.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecc602e3bb)|0.71278|0.72606|0.00324|0.71544|-0.38%|0.71438|-0.51%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/aab281546c)|0.70826|0.71349|0.00103|0.70998|-1.14%|0.70971|-1.16%|38.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aab281546c)|0.67845|0.68141|0.00078|0.67992|-5.33%|0.67995|-5.31%|45.08 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58221|0.58456|0.00059|0.58329|0.00%|0.58326|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecc602e3bb)|0.58136|0.58333|0.00051|0.58219|-0.19%|0.58224|-0.17%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/aab281546c)|0.58118|0.58317|0.00049|0.58213|-0.20%|0.58217|-0.19%|43.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aab281546c)|0.52580|0.53014|0.00076|0.52702|-9.65%|0.52691|-9.66%|61.40 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21540|0.21965|0.00107|0.21736|0.00%|0.21703|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecc602e3bb)|0.21777|0.22237|0.00116|0.21916|0.83%|0.21872|0.78%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/aab281546c)|0.21727|0.22076|0.00083|0.21867|0.60%|0.21863|0.74%|26.66 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aab281546c)|0.07620|0.07925|0.00077|0.07753|-64.33%|0.07737|-64.35%|27.89 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34874|1.37578|0.00634|1.35761|0.00%|1.35706|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ecc602e3bb)|1.31011|1.32439|0.00389|1.31660|-3.02%|1.31514|-3.09%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/aab281546c)|1.26555|1.28390|0.00442|1.27238|-6.28%|1.27201|-6.27%|20.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aab281546c)|0.54496|0.55224|0.00204|0.54755|-59.67%|0.54738|-59.66%|22.34 MB|
