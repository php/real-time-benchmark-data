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
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250818|
| GCC           |14.2.1|
| Time          |2025-09-24 00:50:01 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47507|0.47867|0.00065|0.14%|0.47677|0.00%|0.47665|0.00%|0.798|0.999|180946049|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e1b1900f0)|0.46038|0.46789|0.00077|0.17%|0.46511|-2.45%|0.46501|-2.44%|-1.344|0.000|176281197|44.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/5b8a5320df)|0.46705|0.46974|0.00050|0.11%|0.46793|-1.85%|0.46786|-1.84%|1.010|0.000|176403566|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5b8a5320df)|0.44903|0.45103|0.00042|0.09%|0.44995|-5.63%|0.44992|-5.61%|0.358|0.000|147875927|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73943|0.75305|0.00206|0.28%|0.74140|0.00%|0.74105|0.00%|4.355|0.999|291622864|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e1b1900f0)|0.73353|0.74505|0.00180|0.25%|0.73523|-0.83%|0.73476|-0.85%|3.137|0.000|287319486|40.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/5b8a5320df)|0.73329|0.74546|0.00204|0.28%|0.73520|-0.84%|0.73468|-0.86%|3.119|0.000|287354547|40.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5b8a5320df)|0.70757|0.71128|0.00073|0.10%|0.70911|-4.36%|0.70901|-4.32%|0.575|0.000|267691079|47.58 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57721|0.59509|0.00187|0.32%|0.58260|0.00%|0.58234|0.00%|4.434|0.999|1123342975|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e1b1900f0)|0.57651|0.58260|0.00084|0.14%|0.58043|-0.37%|0.58040|-0.33%|-0.634|0.000|1119773954|44.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/5b8a5320df)|0.57776|0.58236|0.00079|0.14%|0.57924|-0.58%|0.57914|-0.55%|0.999|0.000|1120257768|44.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5b8a5320df)|0.51795|0.52086|0.00057|0.11%|0.51923|-10.88%|0.51921|-10.84%|0.007|0.000|866318956|61.56 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42818|0.43849|0.00190|0.44%|0.43290|0.00%|0.43279|0.00%|0.303|0.999|2020638242|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e1b1900f0)|0.42466|0.59352|0.02595|6.00%|0.43271|-0.04%|0.42735|-1.26%|4.989|0.000|2020645054|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/5b8a5320df)|0.42569|0.53257|0.01902|4.39%|0.43333|0.10%|0.42891|-0.90%|4.664|0.000|2020595138|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5b8a5320df)|0.14746|0.15259|0.00106|0.71%|0.14923|-65.53%|0.14905|-65.56%|1.071|0.000|536613211|27.74 MB|
