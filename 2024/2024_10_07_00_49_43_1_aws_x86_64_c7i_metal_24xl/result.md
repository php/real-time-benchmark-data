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
| OS            |Amazon Linux 2023.5.20241001|
| GCC           |11.4.1|
| Time          |2024-10-07 00:49:43 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43771|0.45145|0.00235|0.43909|0.00%|0.43859|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39ae00fa0a)|0.43589|0.43798|0.00045|0.43701|-0.47%|0.43693|-0.38%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d3990c50a)|0.43487|0.43682|0.00038|0.43573|-0.77%|0.43568|-0.66%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d3990c50a)|0.42873|0.42984|0.00026|0.42936|-2.22%|0.42937|-2.10%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71455|0.72185|0.00137|0.71600|0.00%|0.71564|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39ae00fa0a)|0.70781|0.70990|0.00057|0.70881|-1.00%|0.70880|-0.96%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d3990c50a)|0.70954|0.71272|0.00077|0.71067|-0.74%|0.71058|-0.71%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d3990c50a)|0.68703|0.69041|0.00083|0.68805|-3.90%|0.68789|-3.88%|44.52 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58075|0.58313|0.00057|0.58166|0.00%|0.58153|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39ae00fa0a)|0.57706|0.57885|0.00048|0.57801|-0.63%|0.57805|-0.60%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d3990c50a)|0.57651|0.57927|0.00060|0.57759|-0.70%|0.57758|-0.68%|43.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d3990c50a)|0.51920|0.52186|0.00064|0.52067|-10.49%|0.52075|-10.45%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21570|0.21975|0.00093|0.21669|0.00%|0.21648|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39ae00fa0a)|0.21649|0.22005|0.00077|0.21816|0.68%|0.21834|0.86%|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d3990c50a)|0.21578|0.21988|0.00093|0.21726|0.26%|0.21718|0.32%|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d3990c50a)|0.07476|0.07765|0.00060|0.07567|-65.08%|0.07563|-65.06%|27.29 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34440|1.36495|0.00419|1.35465|0.00%|1.35336|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/39ae00fa0a)|1.40631|1.42480|0.00521|1.41547|4.49%|1.41573|4.61%|20.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d3990c50a)|1.39314|1.41851|0.00683|1.40752|3.90%|1.40805|4.04%|20.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d3990c50a)|0.61924|0.64761|0.00577|0.63430|-53.18%|0.63610|-53.00%|21.70 MB|
