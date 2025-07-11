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
| Time          |2025-07-11 00:50:07 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43493|0.45156|0.00227|0.44094|0.00%|0.44077|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/964a404451)|0.43811|0.44040|0.00050|0.43895|-0.45%|0.43890|-0.42%|42.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/f6380e4a38)|0.43707|0.43982|0.00054|0.43791|-0.69%|0.43786|-0.66%|42.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f6380e4a38)|0.42244|0.42570|0.00059|0.42319|-4.02%|0.42311|-4.01%|51.60 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71214|0.71559|0.00066|0.71359|0.00%|0.71364|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/964a404451)|0.70927|0.71326|0.00090|0.71066|-0.41%|0.71037|-0.46%|38.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/f6380e4a38)|0.71157|0.71483|0.00084|0.71282|-0.11%|0.71262|-0.14%|38.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f6380e4a38)|0.67349|0.68189|0.00143|0.68014|-4.69%|0.68033|-4.67%|45.21 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58170|0.59149|0.00170|0.58312|0.00%|0.58276|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/964a404451)|0.58003|0.58305|0.00076|0.58133|-0.31%|0.58120|-0.27%|43.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/f6380e4a38)|0.58335|0.58547|0.00056|0.58437|0.21%|0.58440|0.28%|43.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f6380e4a38)|0.52188|0.52881|0.00175|0.52539|-9.90%|0.52621|-9.70%|61.64 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21311|0.21834|0.00118|0.21521|0.00%|0.21523|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/964a404451)|0.21722|0.22114|0.00112|0.21852|1.54%|0.21812|1.34%|26.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/f6380e4a38)|0.21344|0.21731|0.00104|0.21520|-0.01%|0.21504|-0.09%|26.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f6380e4a38)|0.07579|0.07858|0.00066|0.07685|-64.29%|0.07680|-64.32%|28.01 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42278|1.44085|0.00327|1.42795|0.00%|1.42813|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/964a404451)|1.27919|1.29185|0.00294|1.28481|-10.02%|1.28493|-10.03%|21.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/f6380e4a38)|1.32371|1.35150|0.00602|1.34177|-6.04%|1.34205|-6.03%|21.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f6380e4a38)|0.54388|0.56486|0.00387|0.55579|-61.08%|0.55577|-61.08%|22.46 MB|
