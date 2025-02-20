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
| OS            |Amazon Linux 2023.6.20250211|
| GCC           |11.4.1|
| Time          |2025-02-20 00:49:31 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43900|0.44236|0.00060|0.43974|0.00%|0.43960|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da38477544)|0.43634|0.43845|0.00039|0.43712|-0.59%|0.43709|-0.57%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/bcf0ee185b)|0.43625|0.43824|0.00053|0.43685|-0.66%|0.43674|-0.65%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bcf0ee185b)|0.42379|0.42547|0.00032|0.42425|-3.52%|0.42423|-3.50%|50.78 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71203|0.71543|0.00078|0.71369|0.00%|0.71368|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da38477544)|0.70701|0.71123|0.00107|0.70808|-0.79%|0.70769|-0.84%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/bcf0ee185b)|0.70618|0.71047|0.00103|0.70756|-0.86%|0.70726|-0.90%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bcf0ee185b)|0.67804|0.68103|0.00073|0.67952|-4.79%|0.67958|-4.78%|44.54 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57984|0.58302|0.00069|0.58078|0.00%|0.58067|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da38477544)|0.57839|0.58168|0.00076|0.57978|-0.17%|0.57992|-0.13%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/bcf0ee185b)|0.57911|0.58232|0.00079|0.58118|0.07%|0.58133|0.11%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bcf0ee185b)|0.52280|0.52432|0.00040|0.52351|-9.86%|0.52351|-9.84%|61.90 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21530|0.21951|0.00115|0.21658|0.00%|0.21603|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da38477544)|0.21389|0.21603|0.00063|0.21469|-0.87%|0.21442|-0.75%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/bcf0ee185b)|0.21635|0.22044|0.00123|0.21838|0.83%|0.21809|0.95%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bcf0ee185b)|0.07570|0.07845|0.00077|0.07682|-64.53%|0.07680|-64.45%|27.36 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34103|1.36819|0.00547|1.35163|0.00%|1.35102|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da38477544)|1.24638|1.27943|0.00816|1.26271|-6.58%|1.26264|-6.54%|20.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/bcf0ee185b)|1.28549|1.30117|0.00410|1.29064|-4.51%|1.29054|-4.48%|20.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bcf0ee185b)|0.53779|0.55418|0.00427|0.54610|-59.60%|0.54516|-59.65%|21.78 MB|
