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
| Time          |2025-05-28 00:49:56 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43777|0.44500|0.00127|0.43868|0.00%|0.43846|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de785f9127)|0.43888|0.44862|0.00213|0.44013|0.33%|0.43956|0.25%|42.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/c4fba3708c)|0.43874|0.44128|0.00057|0.43979|0.25%|0.43954|0.25%|42.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c4fba3708c)|0.42150|0.42361|0.00044|0.42232|-3.73%|0.42232|-3.68%|51.28 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71281|0.71705|0.00111|0.71435|0.00%|0.71430|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de785f9127)|0.70960|0.71265|0.00083|0.71079|-0.50%|0.71070|-0.50%|38.09 MB|
|[PHP - master](https://github.com/php/php-src/commit/c4fba3708c)|0.71153|0.71492|0.00084|0.71320|-0.16%|0.71311|-0.17%|38.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c4fba3708c)|0.68079|0.68381|0.00072|0.68181|-4.55%|0.68174|-4.56%|45.03 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57997|0.59153|0.00254|0.58208|0.00%|0.58145|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de785f9127)|0.58139|0.58402|0.00072|0.58239|0.05%|0.58225|0.14%|43.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/c4fba3708c)|0.58277|0.59195|0.00159|0.58375|0.29%|0.58336|0.33%|43.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c4fba3708c)|0.52568|0.52808|0.00054|0.52664|-9.53%|0.52659|-9.44%|61.05 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21537|0.21911|0.00095|0.21682|0.00%|0.21673|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de785f9127)|0.21703|0.22070|0.00091|0.21881|0.92%|0.21858|0.85%|26.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/c4fba3708c)|0.21585|0.22009|0.00097|0.21745|0.29%|0.21736|0.29%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c4fba3708c)|0.07691|0.07868|0.00047|0.07771|-64.16%|0.07767|-64.16%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34033|1.36240|0.00529|1.35032|0.00%|1.35009|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de785f9127)|1.28874|1.31277|0.00637|1.30166|-3.60%|1.30219|-3.55%|20.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/c4fba3708c)|1.31021|1.33065|0.00475|1.31783|-2.41%|1.31692|-2.46%|20.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c4fba3708c)|0.55675|0.57896|0.00576|0.56752|-57.97%|0.56653|-58.04%|22.20 MB|
