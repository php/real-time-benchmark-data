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
| OS            |Amazon Linux 2023.5.20240916|
| GCC           |11.4.1|
| Time          |2024-09-29 00:49:46 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43815|0.44390|0.00097|0.43907|0.00%|0.43892|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/332e9a47ae)|0.43788|0.43963|0.00043|0.43857|-0.11%|0.43853|-0.09%|41.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8cee06073)|0.43887|0.44220|0.00074|0.43998|0.21%|0.43992|0.23%|41.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8cee06073)|0.43829|0.44088|0.00069|0.43927|0.05%|0.43917|0.06%|41.81 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71429|0.71661|0.00065|0.71538|0.00%|0.71541|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/332e9a47ae)|0.71281|0.72846|0.00267|0.71458|-0.11%|0.71402|-0.19%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8cee06073)|0.71381|0.71714|0.00085|0.71503|-0.05%|0.71479|-0.09%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8cee06073)|0.71379|0.71852|0.00089|0.71536|-0.00%|0.71524|-0.02%|37.39 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58167|0.58425|0.00063|0.58260|0.00%|0.58251|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/332e9a47ae)|0.57847|0.58082|0.00058|0.57931|-0.57%|0.57915|-0.58%|43.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8cee06073)|0.57886|0.58870|0.00174|0.58017|-0.42%|0.57971|-0.48%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8cee06073)|0.57568|0.58159|0.00156|0.57938|-0.55%|0.57979|-0.47%|43.01 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21506|0.21899|0.00098|0.21673|0.00%|0.21660|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/332e9a47ae)|0.21268|0.21886|0.00149|0.21590|-0.38%|0.21641|-0.09%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8cee06073)|0.21346|0.21732|0.00097|0.21522|-0.70%|0.21499|-0.74%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8cee06073)|0.21446|0.22036|0.00154|0.21676|0.01%|0.21631|-0.13%|26.25 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33938|1.36398|0.00662|1.35235|0.00%|1.35176|0.00%|20.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/332e9a47ae)|1.35216|1.36575|0.00368|1.35987|0.56%|1.36023|0.63%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8cee06073)|1.41819|1.43634|0.00500|1.42779|5.58%|1.42744|5.60%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8cee06073)|1.41415|1.44041|0.00596|1.43025|5.76%|1.43068|5.84%|20.50 MB|
