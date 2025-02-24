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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-02-24 00:49:46 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44107|0.45587|0.00256|0.44230|0.00%|0.44185|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1841fdfa2)|0.43740|0.43950|0.00056|0.43821|-0.92%|0.43824|-0.82%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fa15abe92)|0.43765|0.44068|0.00065|0.43863|-0.83%|0.43851|-0.75%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fa15abe92)|0.42652|0.42842|0.00048|0.42740|-3.37%|0.42742|-3.26%|50.78 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71533|0.71931|0.00093|0.71704|0.00%|0.71697|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1841fdfa2)|0.70992|0.71308|0.00077|0.71090|-0.86%|0.71073|-0.87%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fa15abe92)|0.70683|0.71062|0.00086|0.70788|-1.28%|0.70765|-1.30%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fa15abe92)|0.67984|0.68238|0.00070|0.68091|-5.04%|0.68085|-5.04%|44.54 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58193|0.58400|0.00048|0.58289|0.00%|0.58292|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1841fdfa2)|0.58031|0.58208|0.00048|0.58116|-0.30%|0.58124|-0.29%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fa15abe92)|0.58006|0.58227|0.00052|0.58096|-0.33%|0.58084|-0.36%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fa15abe92)|0.52164|0.52375|0.00047|0.52243|-10.37%|0.52239|-10.38%|61.90 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21474|0.21698|0.00051|0.21562|0.00%|0.21555|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1841fdfa2)|0.21482|0.21875|0.00099|0.21654|0.43%|0.21662|0.49%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fa15abe92)|0.21737|0.22106|0.00106|0.21901|1.57%|0.21907|1.63%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fa15abe92)|0.07472|0.07717|0.00051|0.07599|-64.76%|0.07594|-64.77%|27.36 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33623|1.36450|0.00709|1.34835|0.00%|1.34899|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b1841fdfa2)|1.25292|1.27243|0.00557|1.26214|-6.39%|1.26036|-6.57%|20.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fa15abe92)|1.28324|1.29756|0.00462|1.29120|-4.24%|1.29106|-4.29%|20.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fa15abe92)|0.55409|0.57471|0.00594|0.56344|-58.21%|0.56244|-58.31%|21.78 MB|
