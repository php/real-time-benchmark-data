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
| OS            |Amazon Linux 2023.6.20250115|
| GCC           |11.4.1|
| Time          |2025-01-20 00:49:25 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43818|0.44085|0.00048|0.43942|0.00%|0.43941|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/252c0c9164)|0.43783|0.44473|0.00097|0.43894|-0.11%|0.43879|-0.14%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.43872|0.44165|0.00057|0.43987|0.10%|0.43977|0.08%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.42565|0.43165|0.00085|0.42659|-2.92%|0.42641|-2.96%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71284|0.72911|0.00216|0.71489|0.00%|0.71463|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/252c0c9164)|0.71259|0.71531|0.00064|0.71361|-0.18%|0.71352|-0.16%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.71017|0.71379|0.00079|0.71177|-0.44%|0.71166|-0.42%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.68294|0.68532|0.00061|0.68387|-4.34%|0.68382|-4.31%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58124|0.58354|0.00055|0.58226|0.00%|0.58223|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/252c0c9164)|0.57837|0.58122|0.00065|0.57990|-0.41%|0.57989|-0.40%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.57843|0.58129|0.00059|0.57944|-0.48%|0.57935|-0.49%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.51873|0.52142|0.00053|0.52051|-10.61%|0.52057|-10.59%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21476|0.22020|0.00095|0.21634|0.00%|0.21625|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/252c0c9164)|0.21498|0.21959|0.00101|0.21702|0.31%|0.21698|0.33%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.21487|0.22163|0.00114|0.21654|0.09%|0.21656|0.14%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.07440|0.07743|0.00077|0.07569|-65.01%|0.07539|-65.14%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34149|1.36542|0.00627|1.35144|0.00%|1.35235|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/252c0c9164)|1.33204|1.35547|0.00491|1.34050|-0.81%|1.34021|-0.90%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/6bd2b8dfa5)|1.26428|1.28698|0.00497|1.27658|-5.54%|1.27707|-5.57%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6bd2b8dfa5)|0.55256|0.56989|0.00398|0.56238|-58.39%|0.56254|-58.40%|21.72 MB|