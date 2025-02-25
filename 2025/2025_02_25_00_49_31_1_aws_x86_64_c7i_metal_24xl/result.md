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
| Time          |2025-02-25 00:49:31 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43894|0.44852|0.00163|0.43996|0.00%|0.43966|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fa15abe92)|0.43469|0.43953|0.00090|0.43571|-0.97%|0.43557|-0.93%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a10b990f2)|0.43735|0.44437|0.00125|0.43815|-0.41%|0.43789|-0.40%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a10b990f2)|0.42503|0.42723|0.00046|0.42577|-3.22%|0.42573|-3.17%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71265|0.71572|0.00066|0.71363|0.00%|0.71358|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fa15abe92)|0.70199|0.70485|0.00077|0.70337|-1.44%|0.70327|-1.45%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a10b990f2)|0.70001|0.70933|0.00150|0.70700|-0.93%|0.70706|-0.91%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a10b990f2)|0.67846|0.68050|0.00057|0.67951|-4.78%|0.67949|-4.78%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58131|0.58326|0.00042|0.58195|0.00%|0.58188|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fa15abe92)|0.57957|0.58473|0.00129|0.58103|-0.16%|0.58059|-0.22%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a10b990f2)|0.57961|0.58177|0.00047|0.58032|-0.28%|0.58024|-0.28%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a10b990f2)|0.52164|0.52349|0.00046|0.52230|-10.25%|0.52225|-10.25%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21491|0.21851|0.00084|0.21610|0.00%|0.21598|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fa15abe92)|0.21846|0.22075|0.00059|0.21953|1.59%|0.21956|1.66%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a10b990f2)|0.21577|0.21910|0.00088|0.21738|0.59%|0.21740|0.66%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a10b990f2)|0.07496|0.07769|0.00069|0.07623|-64.72%|0.07615|-64.74%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33898|1.36505|0.00594|1.34956|0.00%|1.34992|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fa15abe92)|1.28356|1.29986|0.00501|1.29122|-4.32%|1.28914|-4.50%|20.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/1a10b990f2)|1.28159|1.30573|0.00538|1.29168|-4.29%|1.29186|-4.30%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1a10b990f2)|0.53655|0.55794|0.00625|0.54854|-59.35%|0.54813|-59.40%|21.79 MB|
