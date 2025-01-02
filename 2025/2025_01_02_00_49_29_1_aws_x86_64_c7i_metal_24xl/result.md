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
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2025-01-02 00:49:29 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43893|0.44091|0.00050|0.43973|0.00%|0.43970|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90121f4056)|0.43559|0.43829|0.00056|0.43666|-0.70%|0.43654|-0.72%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/249d2dac28)|0.43572|0.43784|0.00044|0.43663|-0.70%|0.43662|-0.70%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/249d2dac28)|0.42696|0.42896|0.00038|0.42770|-2.74%|0.42763|-2.75%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71314|0.71609|0.00067|0.71487|0.00%|0.71484|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90121f4056)|0.71007|0.71383|0.00083|0.71171|-0.44%|0.71153|-0.46%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/249d2dac28)|0.70878|0.71311|0.00079|0.71025|-0.65%|0.71012|-0.66%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/249d2dac28)|0.68223|0.68566|0.00074|0.68343|-4.40%|0.68323|-4.42%|44.48 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58090|0.58407|0.00062|0.58257|0.00%|0.58250|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90121f4056)|0.57739|0.58027|0.00069|0.57886|-0.64%|0.57881|-0.63%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/249d2dac28)|0.57358|0.58910|0.00211|0.57826|-0.74%|0.57840|-0.70%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/249d2dac28)|0.51817|0.52150|0.00089|0.51983|-10.77%|0.51990|-10.75%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21484|0.21833|0.00085|0.21632|0.00%|0.21614|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90121f4056)|0.21594|0.21930|0.00061|0.21705|0.34%|0.21699|0.39%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/249d2dac28)|0.21461|0.21810|0.00075|0.21592|-0.18%|0.21583|-0.15%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/249d2dac28)|0.07335|0.07759|0.00079|0.07576|-64.98%|0.07566|-64.99%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34359|1.36252|0.00459|1.35382|0.00%|1.35450|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/90121f4056)|1.25991|1.28679|0.00513|1.27035|-6.17%|1.26993|-6.24%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/249d2dac28)|1.30544|1.33268|0.00563|1.31908|-2.57%|1.31800|-2.69%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/249d2dac28)|0.52830|0.55284|0.00549|0.54515|-59.73%|0.54598|-59.69%|21.66 MB|
