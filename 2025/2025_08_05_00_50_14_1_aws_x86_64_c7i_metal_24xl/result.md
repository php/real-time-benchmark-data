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
| Kernel        |6.1.144-170.251.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250721|
| GCC           |11.5.0|
| Time          |2025-08-05 00:50:14 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47249|0.49484|0.00387|0.47457|0.00%|0.47370|0.00%|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55a3e33bb1)|0.46645|0.46900|0.00070|0.46766|-1.46%|0.46766|-1.27%|43.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e014dfbe)|0.46584|0.46800|0.00052|0.46697|-1.60%|0.46697|-1.42%|43.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e014dfbe)|0.44938|0.45251|0.00064|0.45096|-4.98%|0.45091|-4.81%|53.73 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74296|0.75183|0.00161|0.74647|0.00%|0.74632|0.00%|39.94 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55a3e33bb1)|0.72945|0.73752|0.00175|0.73159|-1.99%|0.73128|-2.02%|40.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e014dfbe)|0.73004|0.73765|0.00203|0.73269|-1.85%|0.73181|-1.95%|40.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e014dfbe)|0.70098|0.70738|0.00158|0.70263|-5.87%|0.70213|-5.92%|47.77 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57861|0.58458|0.00181|0.58044|0.00%|0.57964|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55a3e33bb1)|0.57773|0.58020|0.00061|0.57877|-0.29%|0.57867|-0.17%|43.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e014dfbe)|0.57988|0.58171|0.00046|0.58073|0.05%|0.58071|0.18%|43.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e014dfbe)|0.51687|0.51947|0.00060|0.51772|-10.80%|0.51764|-10.70%|61.36 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21287|0.21706|0.00110|0.21513|0.00%|0.21531|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55a3e33bb1)|0.21611|0.22025|0.00095|0.21810|1.38%|0.21802|1.26%|26.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e014dfbe)|0.21218|0.21614|0.00119|0.21417|-0.45%|0.21425|-0.49%|26.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e014dfbe)|0.07262|0.07635|0.00099|0.07389|-65.65%|0.07360|-65.82%|27.77 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42397|1.44381|0.00537|1.43281|0.00%|1.43304|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/55a3e33bb1)|1.24791|1.28079|0.00768|1.26545|-11.68%|1.26616|-11.64%|20.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e014dfbe)|1.34015|1.35686|0.00410|1.34719|-5.98%|1.34698|-6.01%|20.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e014dfbe)|0.56106|0.58891|0.00632|0.57235|-60.05%|0.57121|-60.14%|22.21 MB|
