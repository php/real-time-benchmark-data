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
| Time          |2024-09-30 00:49:36 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43799|0.44856|0.00182|0.43889|0.00%|0.43856|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8cee06073)|0.43796|0.43980|0.00041|0.43864|-0.06%|0.43864|0.02%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/bca73f1c69)|0.43867|0.44068|0.00047|0.43965|0.17%|0.43952|0.22%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bca73f1c69)|0.43779|0.44054|0.00051|0.43864|-0.06%|0.43860|0.01%|41.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71412|0.71727|0.00069|0.71557|0.00%|0.71545|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8cee06073)|0.71485|0.71837|0.00091|0.71604|0.07%|0.71582|0.05%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/bca73f1c69)|0.71460|0.72117|0.00132|0.71583|0.04%|0.71541|-0.01%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bca73f1c69)|0.71459|0.71814|0.00092|0.71605|0.07%|0.71588|0.06%|37.38 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58032|0.58256|0.00062|0.58111|0.00%|0.58094|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8cee06073)|0.57563|0.57871|0.00073|0.57693|-0.72%|0.57677|-0.72%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/bca73f1c69)|0.57606|0.57790|0.00043|0.57703|-0.70%|0.57703|-0.67%|43.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bca73f1c69)|0.57565|0.57792|0.00052|0.57666|-0.77%|0.57661|-0.75%|43.00 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21581|0.21993|0.00096|0.21719|0.00%|0.21718|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8cee06073)|0.21410|0.21944|0.00141|0.21646|-0.33%|0.21615|-0.48%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/bca73f1c69)|0.21413|0.22146|0.00160|0.21646|-0.33%|0.21649|-0.32%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bca73f1c69)|0.21355|0.21838|0.00112|0.21593|-0.58%|0.21607|-0.51%|26.23 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34127|1.36016|0.00496|1.35101|0.00%|1.35093|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8cee06073)|1.41748|1.44715|0.00810|1.43167|5.97%|1.43219|6.02%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/bca73f1c69)|1.41783|1.43784|0.00619|1.42728|5.65%|1.42629|5.58%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bca73f1c69)|1.41685|1.44225|0.00670|1.42960|5.82%|1.43054|5.89%|20.48 MB|
