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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-12 00:49:37 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43837|0.44019|0.00041|0.43917|0.00%|0.43913|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10b2754056)|0.43823|0.44027|0.00045|0.43894|-0.05%|0.43892|-0.05%|41.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/fd7ebd4d15)|0.43965|0.44217|0.00071|0.44057|0.32%|0.44036|0.28%|41.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fd7ebd4d15)|0.42679|0.42837|0.00041|0.42737|-2.69%|0.42735|-2.68%|50.88 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71160|0.71511|0.00086|0.71308|0.00%|0.71287|0.00%|37.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10b2754056)|0.70695|0.71013|0.00073|0.70818|-0.69%|0.70809|-0.67%|37.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/fd7ebd4d15)|0.70946|0.71224|0.00061|0.71072|-0.33%|0.71069|-0.31%|37.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fd7ebd4d15)|0.67976|0.68283|0.00066|0.68136|-4.45%|0.68131|-4.43%|44.62 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58019|0.58358|0.00063|0.58149|0.00%|0.58134|0.00%|43.07 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10b2754056)|0.57710|0.58291|0.00188|0.57877|-0.47%|0.57788|-0.60%|42.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/fd7ebd4d15)|0.57766|0.58107|0.00080|0.57929|-0.38%|0.57928|-0.35%|42.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fd7ebd4d15)|0.52105|0.52309|0.00051|0.52208|-10.22%|0.52210|-10.19%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21543|0.21985|0.00100|0.21675|0.00%|0.21643|0.00%|26.23 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10b2754056)|0.21395|0.21696|0.00079|0.21545|-0.60%|0.21537|-0.49%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/fd7ebd4d15)|0.21573|0.21886|0.00090|0.21705|0.14%|0.21685|0.19%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fd7ebd4d15)|0.07455|0.07828|0.00086|0.07603|-64.92%|0.07596|-64.91%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33650|1.36247|0.00606|1.34754|0.00%|1.34622|0.00%|20.49 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10b2754056)|1.28793|1.31089|0.00631|1.30005|-3.52%|1.29983|-3.45%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/fd7ebd4d15)|1.25435|1.27287|0.00455|1.26500|-6.13%|1.26512|-6.02%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fd7ebd4d15)|0.53045|0.54724|0.00387|0.53800|-60.08%|0.53784|-60.05%|21.83 MB|
