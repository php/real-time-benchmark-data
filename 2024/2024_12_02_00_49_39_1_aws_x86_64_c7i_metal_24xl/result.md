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
| OS            |Amazon Linux 2023.6.20241121|
| GCC           |11.4.1|
| Time          |2024-12-02 00:49:39 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43901|0.44998|0.00150|0.43989|0.00%|0.43965|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b06f2bc67c)|0.43713|0.43952|0.00043|0.43809|-0.41%|0.43808|-0.36%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/1d2c544cca)|0.43761|0.43926|0.00039|0.43836|-0.35%|0.43834|-0.30%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1d2c544cca)|0.42473|0.42620|0.00034|0.42534|-3.31%|0.42529|-3.27%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71218|0.71542|0.00072|0.71389|0.00%|0.71388|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b06f2bc67c)|0.71069|0.71468|0.00076|0.71190|-0.28%|0.71179|-0.29%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/1d2c544cca)|0.71001|0.71352|0.00083|0.71130|-0.36%|0.71115|-0.38%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1d2c544cca)|0.67524|0.68361|0.00113|0.68180|-4.50%|0.68196|-4.47%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58055|0.58301|0.00065|0.58167|0.00%|0.58155|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b06f2bc67c)|0.57664|0.57907|0.00064|0.57776|-0.67%|0.57772|-0.66%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/1d2c544cca)|0.57564|0.57886|0.00074|0.57718|-0.77%|0.57709|-0.77%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1d2c544cca)|0.51949|0.52186|0.00046|0.52067|-10.49%|0.52058|-10.48%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21500|0.21887|0.00102|0.21685|0.00%|0.21677|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b06f2bc67c)|0.21529|0.21803|0.00068|0.21640|-0.21%|0.21635|-0.19%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/1d2c544cca)|0.21512|0.21859|0.00076|0.21650|-0.16%|0.21641|-0.17%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1d2c544cca)|0.07487|0.07857|0.00100|0.07666|-64.65%|0.07662|-64.65%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34464|1.37763|0.00687|1.35826|0.00%|1.35683|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b06f2bc67c)|1.24920|1.27126|0.00512|1.26107|-7.16%|1.26067|-7.09%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/1d2c544cca)|1.25039|1.27236|0.00496|1.26017|-7.22%|1.26088|-7.07%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1d2c544cca)|0.53637|0.56608|0.00531|0.55501|-59.14%|0.55536|-59.07%|21.70 MB|
