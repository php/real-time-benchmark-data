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
| Time          |2025-10-04 00:49:55 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46948|0.47911|0.00121|0.25%|0.47693|0.00%|0.47699|0.00%|-4.408|0.999|180946254|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/28fd7597ba)|0.46920|0.47592|0.00100|0.21%|0.47038|-1.37%|0.47016|-1.43%|2.852|0.000|176328650|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c956f9838)|0.46410|0.47508|0.00095|0.20%|0.47018|-1.42%|0.47014|-1.44%|-1.115|0.000|176400655|44.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c956f9838)|0.44944|0.45336|0.00056|0.12%|0.45024|-5.60%|0.45011|-5.64%|2.438|0.000|147881362|53.45 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74137|0.75301|0.00133|0.18%|0.74309|0.00%|0.74296|0.00%|4.387|0.999|291620736|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/28fd7597ba)|0.73625|0.75386|0.00240|0.32%|0.73862|-0.60%|0.73796|-0.67%|3.899|0.000|287356206|40.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c956f9838)|0.73679|0.74672|0.00160|0.22%|0.73865|-0.60%|0.73806|-0.66%|2.309|0.000|287354216|40.57 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c956f9838)|0.70894|0.71474|0.00075|0.11%|0.71060|-4.37%|0.71050|-4.37%|1.886|0.000|267717295|47.85 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58019|0.59101|0.00134|0.23%|0.58257|0.00%|0.58250|0.00%|2.462|0.999|1123344173|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/28fd7597ba)|0.58047|0.58604|0.00113|0.19%|0.58285|0.05%|0.58283|0.06%|-0.006|0.015|1120247735|44.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c956f9838)|0.58193|0.58802|0.00111|0.19%|0.58442|0.32%|0.58447|0.34%|0.176|0.000|1120254584|44.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c956f9838)|0.51660|0.52087|0.00092|0.18%|0.51875|-10.96%|0.51882|-10.93%|-0.208|0.000|866315254|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42954|0.43823|0.00200|0.46%|0.43330|0.00%|0.43330|0.00%|0.212|0.999|2020638178|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/28fd7597ba)|0.43287|0.56284|0.02841|6.36%|0.44670|3.09%|0.43827|1.15%|3.170|0.000|2020595094|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c956f9838)|0.43459|0.55612|0.03201|7.13%|0.44877|3.57%|0.43780|1.04%|2.581|0.000|2020595066|27.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c956f9838)|0.14106|0.15196|0.00123|0.82%|0.14898|-65.62%|0.14891|-65.63%|-2.327|0.000|536613204|27.81 MB|
