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
| Time          |2024-10-28 00:49:30 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43913|0.44133|0.00040|0.43991|0.00%|0.43986|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8d388eb3a)|0.43681|0.43936|0.00056|0.43773|-0.50%|0.43755|-0.52%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/e8a1781c52)|0.43689|0.44378|0.00093|0.43795|-0.45%|0.43786|-0.46%|41.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e8a1781c52)|0.42742|0.42930|0.00040|0.42820|-2.66%|0.42813|-2.67%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.72011|0.72296|0.00067|0.72129|0.00%|0.72125|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8d388eb3a)|0.71395|0.71878|0.00082|0.71666|-0.64%|0.71665|-0.64%|37.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/e8a1781c52)|0.70520|0.71520|0.00131|0.71329|-1.11%|0.71337|-1.09%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e8a1781c52)|0.69239|0.69501|0.00060|0.69350|-3.85%|0.69351|-3.85%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58237|0.58505|0.00069|0.58375|0.00%|0.58371|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8d388eb3a)|0.58403|0.58763|0.00068|0.58566|0.33%|0.58569|0.34%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/e8a1781c52)|0.57875|0.58252|0.00077|0.58066|-0.53%|0.58073|-0.51%|42.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e8a1781c52)|0.52380|0.52632|0.00052|0.52475|-10.11%|0.52469|-10.11%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21481|0.21889|0.00107|0.21627|0.00%|0.21579|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8d388eb3a)|0.21350|0.21736|0.00081|0.21462|-0.76%|0.21456|-0.57%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/e8a1781c52)|0.21504|0.21956|0.00124|0.21692|0.30%|0.21670|0.42%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e8a1781c52)|0.07317|0.07746|0.00096|0.07483|-65.40%|0.07464|-65.41%|27.37 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33280|1.35797|0.00555|1.34718|0.00%|1.34753|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8d388eb3a)|1.26773|1.28709|0.00344|1.27838|-5.11%|1.27863|-5.11%|20.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/e8a1781c52)|1.34607|1.36603|0.00498|1.35532|0.60%|1.35554|0.59%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e8a1781c52)|0.52674|0.54355|0.00410|0.53441|-60.33%|0.53437|-60.34%|21.78 MB|
