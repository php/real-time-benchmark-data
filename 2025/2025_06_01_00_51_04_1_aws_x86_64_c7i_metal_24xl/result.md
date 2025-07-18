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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-06-01 00:51:04 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43781|0.44647|0.00191|0.43924|0.00%|0.43880|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b64daf9b3f)|0.43243|0.44011|0.00127|0.43883|-0.09%|0.43906|0.06%|42.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a156572e8)|0.43876|0.44038|0.00033|0.43956|0.07%|0.43953|0.17%|42.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a156572e8)|0.42166|0.42335|0.00040|0.42229|-3.86%|0.42221|-3.78%|51.28 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71501|0.71855|0.00091|0.71621|0.00%|0.71601|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b64daf9b3f)|0.71282|0.71580|0.00080|0.71400|-0.31%|0.71379|-0.31%|38.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a156572e8)|0.71047|0.71365|0.00087|0.71203|-0.58%|0.71189|-0.57%|38.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a156572e8)|0.67868|0.68108|0.00059|0.67984|-5.08%|0.67974|-5.07%|45.03 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58092|0.58301|0.00049|0.58189|0.00%|0.58194|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b64daf9b3f)|0.57994|0.58195|0.00046|0.58104|-0.14%|0.58108|-0.15%|43.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a156572e8)|0.58080|0.58392|0.00075|0.58195|0.01%|0.58169|-0.04%|43.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a156572e8)|0.52313|0.52617|0.00067|0.52499|-9.78%|0.52494|-9.79%|61.05 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21533|0.21887|0.00090|0.21701|0.00%|0.21691|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b64daf9b3f)|0.21850|0.22174|0.00085|0.21978|1.27%|0.21958|1.23%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a156572e8)|0.21231|0.21590|0.00074|0.21386|-1.45%|0.21362|-1.52%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a156572e8)|0.07638|0.07904|0.00060|0.07746|-64.31%|0.07737|-64.33%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34336|1.36446|0.00459|1.35167|0.00%|1.35024|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b64daf9b3f)|1.29275|1.31973|0.00690|1.30873|-3.18%|1.31055|-2.94%|20.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a156572e8)|1.29661|1.31083|0.00367|1.30257|-3.63%|1.30242|-3.54%|20.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a156572e8)|0.55276|0.57339|0.00424|0.56635|-58.10%|0.56691|-58.01%|22.20 MB|
