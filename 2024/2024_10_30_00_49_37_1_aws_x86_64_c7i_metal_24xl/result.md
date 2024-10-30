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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-10-30 00:49:37 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43813|0.44916|0.00181|0.43954|0.00%|0.43914|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb6212b073)|0.43584|0.43783|0.00045|0.43696|-0.59%|0.43690|-0.51%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/b564ccd504)|0.43589|0.43756|0.00039|0.43678|-0.63%|0.43676|-0.54%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b564ccd504)|0.42557|0.42731|0.00039|0.42639|-2.99%|0.42637|-2.91%|50.83 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71930|0.72243|0.00076|0.72052|0.00%|0.72042|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb6212b073)|0.71251|0.71564|0.00074|0.71374|-0.94%|0.71369|-0.93%|37.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/b564ccd504)|0.71206|0.71570|0.00080|0.71382|-0.93%|0.71371|-0.93%|37.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b564ccd504)|0.69199|0.69499|0.00057|0.69344|-3.76%|0.69346|-3.74%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58270|0.58535|0.00064|0.58371|0.00%|0.58368|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb6212b073)|0.57597|0.58396|0.00161|0.58070|-0.52%|0.58109|-0.44%|42.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/b564ccd504)|0.57869|0.58955|0.00164|0.58080|-0.50%|0.58037|-0.57%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b564ccd504)|0.52274|0.52563|0.00061|0.52440|-10.16%|0.52436|-10.16%|61.95 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21438|0.21946|0.00120|0.21634|0.00%|0.21588|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb6212b073)|0.21470|0.21936|0.00092|0.21684|0.23%|0.21663|0.35%|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/b564ccd504)|0.21511|0.21868|0.00079|0.21657|0.10%|0.21648|0.28%|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b564ccd504)|0.07331|0.07708|0.00082|0.07466|-65.49%|0.07447|-65.50%|27.37 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33375|1.35893|0.00549|1.34724|0.00%|1.34690|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb6212b073)|1.28432|1.29975|0.00357|1.29201|-4.10%|1.29182|-4.09%|20.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/b564ccd504)|1.28513|1.30515|0.00436|1.29339|-4.00%|1.29327|-3.98%|20.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b564ccd504)|0.52739|0.54391|0.00379|0.53630|-60.19%|0.53621|-60.19%|21.78 MB|
