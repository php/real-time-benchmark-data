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
| Kernel        |6.1.112-124.190.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241031|
| GCC           |11.4.1|
| Time          |2024-11-08 00:49:29 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43858|0.44773|0.00157|0.43982|0.00%|0.43951|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96d1cd00b7)|0.43588|0.44236|0.00087|0.43713|-0.61%|0.43705|-0.56%|41.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1bf3acf44)|0.43632|0.43792|0.00042|0.43702|-0.64%|0.43698|-0.58%|41.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1bf3acf44)|0.42639|0.42878|0.00042|0.42698|-2.92%|0.42686|-2.88%|50.85 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71970|0.73453|0.00275|0.72146|0.00%|0.72085|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96d1cd00b7)|0.71219|0.71569|0.00065|0.71357|-1.09%|0.71354|-1.01%|37.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1bf3acf44)|0.71506|0.71729|0.00053|0.71607|-0.75%|0.71601|-0.67%|37.49 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1bf3acf44)|0.69130|0.69432|0.00073|0.69257|-4.00%|0.69237|-3.95%|44.56 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58171|0.58480|0.00071|0.58305|0.00%|0.58302|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96d1cd00b7)|0.57935|0.58289|0.00090|0.58075|-0.40%|0.58050|-0.43%|43.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1bf3acf44)|0.57706|0.57907|0.00053|0.57807|-0.86%|0.57806|-0.85%|43.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1bf3acf44)|0.52217|0.52465|0.00053|0.52307|-10.29%|0.52303|-10.29%|62.00 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21464|0.21817|0.00084|0.21642|0.00%|0.21626|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96d1cd00b7)|0.21571|0.22288|0.00153|0.21835|0.89%|0.21829|0.94%|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1bf3acf44)|0.21505|0.21870|0.00077|0.21640|-0.01%|0.21634|0.03%|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1bf3acf44)|0.07319|0.07652|0.00077|0.07467|-65.50%|0.07459|-65.51%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33353|1.36544|0.00542|1.34714|0.00%|1.34571|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96d1cd00b7)|1.28759|1.31741|0.00591|1.30061|-3.45%|1.30008|-3.39%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/c1bf3acf44)|1.25611|1.27483|0.00475|1.26583|-6.04%|1.26596|-5.93%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c1bf3acf44)|0.53709|0.56777|0.00760|0.54963|-59.20%|0.54901|-59.20%|21.80 MB|
