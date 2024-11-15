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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241111|
| GCC           |11.4.1|
| Time          |2024-11-15 00:49:39 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43930|0.45327|0.00188|0.44040|0.00%|0.44015|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3815a773a1)|0.43538|0.43702|0.00039|0.43622|-0.95%|0.43622|-0.89%|41.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/3f4bcd8cba)|0.43579|0.43754|0.00035|0.43654|-0.88%|0.43652|-0.82%|41.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3f4bcd8cba)|0.42544|0.42711|0.00041|0.42607|-3.25%|0.42600|-3.22%|50.80 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71369|0.71723|0.00074|0.71492|0.00%|0.71485|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3815a773a1)|0.70961|0.71424|0.00080|0.71117|-0.52%|0.71116|-0.52%|37.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/3f4bcd8cba)|0.70904|0.71285|0.00083|0.71120|-0.52%|0.71125|-0.50%|37.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3f4bcd8cba)|0.67957|0.68529|0.00085|0.68129|-4.70%|0.68120|-4.71%|44.51 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57680|0.58368|0.00224|0.58047|0.00%|0.58179|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3815a773a1)|0.57959|0.58303|0.00076|0.58109|0.11%|0.58083|-0.17%|43.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/3f4bcd8cba)|0.57957|0.58195|0.00051|0.58105|0.10%|0.58109|-0.12%|43.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3f4bcd8cba)|0.51993|0.52309|0.00062|0.52107|-10.23%|0.52085|-10.47%|61.95 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21569|0.21994|0.00095|0.21716|0.00%|0.21699|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3815a773a1)|0.21167|0.21657|0.00104|0.21340|-1.73%|0.21329|-1.71%|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/3f4bcd8cba)|0.21192|0.21934|0.00123|0.21351|-1.68%|0.21331|-1.70%|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3f4bcd8cba)|0.07292|0.07692|0.00093|0.07485|-65.53%|0.07475|-65.55%|27.34 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34212|1.36366|0.00516|1.35189|0.00%|1.35233|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3815a773a1)|1.27412|1.29199|0.00401|1.28367|-5.05%|1.28300|-5.13%|20.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/3f4bcd8cba)|1.27558|1.29726|0.00459|1.28501|-4.95%|1.28416|-5.04%|20.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3f4bcd8cba)|0.53420|0.55570|0.00391|0.54455|-59.72%|0.54496|-59.70%|21.75 MB|
