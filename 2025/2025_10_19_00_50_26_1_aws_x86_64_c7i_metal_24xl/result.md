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
| Time          |2025-10-19 00:50:26 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47692|0.47983|0.00054|0.11%|0.47800|0.00%|0.47793|0.00%|0.759|0.999|180947022|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d4f3ae90d2)|0.46938|0.47259|0.00060|0.13%|0.47077|-1.51%|0.47068|-1.52%|0.851|0.000|176331821|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/81fef09d01)|0.46950|0.47439|0.00072|0.15%|0.47083|-1.50%|0.47072|-1.51%|1.668|0.000|176406292|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/81fef09d01)|0.45223|0.45588|0.00063|0.14%|0.45312|-5.20%|0.45302|-5.21%|1.968|0.000|147868688|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74182|0.75339|0.00126|0.17%|0.74362|0.00%|0.74344|0.00%|4.855|0.999|291621380|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d4f3ae90d2)|0.73641|0.74764|0.00196|0.27%|0.73886|-0.64%|0.73844|-0.67%|2.217|0.000|287318810|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/81fef09d01)|0.73620|0.74854|0.00179|0.24%|0.73886|-0.64%|0.73837|-0.68%|2.498|0.000|287319083|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/81fef09d01)|0.70787|0.71220|0.00092|0.13%|0.70960|-4.57%|0.70941|-4.58%|0.808|0.000|267681730|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58135|0.58536|0.00072|0.12%|0.58331|0.00%|0.58321|0.00%|0.696|0.999|1123343088|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d4f3ae90d2)|0.58320|0.58929|0.00094|0.16%|0.58599|0.46%|0.58584|0.45%|0.624|0.000|1120067032|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/81fef09d01)|0.58037|0.58848|0.00095|0.16%|0.58573|0.41%|0.58573|0.43%|-1.470|0.000|1120074130|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/81fef09d01)|0.51800|0.52102|0.00049|0.09%|0.51957|-10.93%|0.51950|-10.93%|0.418|0.000|866124179|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42816|0.43971|0.00210|0.49%|0.43360|0.00%|0.43342|0.00%|0.330|0.999|2020638207|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d4f3ae90d2)|0.42350|0.43679|0.00267|0.62%|0.42679|-1.57%|0.42599|-1.71%|2.212|0.000|2020586576|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/81fef09d01)|0.42376|0.48088|0.00768|1.80%|0.42745|-1.42%|0.42590|-1.73%|6.208|0.000|2020586631|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/81fef09d01)|0.14088|0.15011|0.00132|0.90%|0.14661|-66.19%|0.14656|-66.18%|-0.359|0.000|536605627|27.67 MB|
