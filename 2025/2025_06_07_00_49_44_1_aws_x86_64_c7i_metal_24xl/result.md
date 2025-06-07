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
| OS            |Amazon Linux 2023.7.20250527|
| GCC           |11.5.0|
| Time          |2025-06-07 00:49:44 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44061|0.45001|0.00161|0.44175|0.00%|0.44132|0.00%|41.89 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2751064692)|0.44187|0.44317|0.00035|0.44247|0.16%|0.44246|0.26%|42.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/cce0efdff8)|0.44175|0.44323|0.00044|0.44240|0.15%|0.44236|0.23%|42.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cce0efdff8)|0.42658|0.43059|0.00070|0.42793|-3.13%|0.42791|-3.04%|51.20 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71555|0.73202|0.00288|0.71706|0.00%|0.71631|0.00%|37.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2751064692)|0.71171|0.71396|0.00063|0.71290|-0.58%|0.71273|-0.50%|37.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/cce0efdff8)|0.71093|0.71460|0.00082|0.71258|-0.62%|0.71260|-0.52%|37.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cce0efdff8)|0.68059|0.68367|0.00075|0.68173|-4.93%|0.68164|-4.84%|44.96 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58093|0.58343|0.00062|0.58195|0.00%|0.58180|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2751064692)|0.58175|0.58370|0.00048|0.58262|0.11%|0.58260|0.14%|43.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/cce0efdff8)|0.58214|0.58375|0.00043|0.58282|0.15%|0.58278|0.17%|43.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cce0efdff8)|0.52589|0.52794|0.00049|0.52687|-9.47%|0.52693|-9.43%|60.98 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21582|0.21976|0.00101|0.21741|0.00%|0.21746|0.00%|26.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2751064692)|0.21127|0.21493|0.00097|0.21312|-1.97%|0.21293|-2.08%|26.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/cce0efdff8)|0.21243|0.21762|0.00106|0.21420|-1.47%|0.21404|-1.58%|26.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cce0efdff8)|0.07542|0.07799|0.00070|0.07669|-64.72%|0.07654|-64.80%|27.71 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34126|1.35536|0.00406|1.35011|0.00%|1.35064|0.00%|20.53 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2751064692)|1.29746|1.31359|0.00453|1.30673|-3.21%|1.30689|-3.24%|20.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/cce0efdff8)|1.28765|1.30739|0.00396|1.29868|-3.81%|1.29881|-3.84%|20.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cce0efdff8)|0.56090|0.57944|0.00492|0.57177|-57.65%|0.57256|-57.61%|22.13 MB|
