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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250203|
| GCC           |11.4.1|
| Time          |2025-02-11 00:49:21 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43880|0.44786|0.00124|0.43973|0.00%|0.43948|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bce1f4aeb1)|0.43667|0.43920|0.00057|0.43763|-0.48%|0.43764|-0.42%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c570a22f)|0.43775|0.44510|0.00108|0.43875|-0.22%|0.43856|-0.21%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c570a22f)|0.42528|0.42717|0.00037|0.42620|-3.08%|0.42621|-3.02%|50.80 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70667|0.71455|0.00115|0.71262|0.00%|0.71256|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bce1f4aeb1)|0.70765|0.71244|0.00082|0.70917|-0.48%|0.70917|-0.48%|37.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c570a22f)|0.70636|0.71047|0.00079|0.70810|-0.64%|0.70800|-0.64%|37.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c570a22f)|0.68185|0.68543|0.00080|0.68332|-4.11%|0.68323|-4.12%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58108|0.59108|0.00140|0.58208|0.00%|0.58195|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bce1f4aeb1)|0.57646|0.58827|0.00166|0.57786|-0.73%|0.57754|-0.76%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c570a22f)|0.57747|0.58039|0.00054|0.57847|-0.62%|0.57847|-0.60%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c570a22f)|0.51645|0.52264|0.00080|0.52089|-10.51%|0.52093|-10.48%|61.93 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21479|0.22110|0.00123|0.21641|0.00%|0.21621|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bce1f4aeb1)|0.21539|0.22152|0.00093|0.21675|0.16%|0.21648|0.13%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c570a22f)|0.21508|0.21937|0.00073|0.21624|-0.08%|0.21612|-0.04%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c570a22f)|0.07399|0.07759|0.00092|0.07542|-65.15%|0.07547|-65.09%|27.35 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33976|1.36410|0.00567|1.35046|0.00%|1.35022|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bce1f4aeb1)|1.27272|1.28971|0.00437|1.28087|-5.15%|1.28066|-5.15%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6c570a22f)|1.26754|1.28795|0.00401|1.28049|-5.18%|1.28115|-5.12%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6c570a22f)|0.52788|0.55439|0.00570|0.54033|-59.99%|0.54040|-59.98%|21.77 MB|
