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
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2025-12-12 00:50:19 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46900|0.48124|0.00105|0.22%|0.47602|0.00%|0.47600|0.00%|-1.601|0.999|180944211|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c27368c939)|0.46650|0.47318|0.00075|0.16%|0.46984|-1.30%|0.46974|-1.32%|0.428|0.000|176333488|44.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/19deb91002)|0.46850|0.47576|0.00087|0.19%|0.46982|-1.30%|0.46971|-1.32%|3.383|0.000|176405092|44.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/19deb91002)|0.45080|0.45447|0.00062|0.14%|0.45181|-5.09%|0.45167|-5.11%|1.792|0.000|147894928|53.41 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74100|0.75224|0.00125|0.17%|0.74243|0.00%|0.74228|0.00%|5.110|0.999|291621956|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c27368c939)|0.74172|0.75173|0.00138|0.19%|0.74358|0.16%|0.74327|0.13%|2.772|0.000|290398740|40.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/19deb91002)|0.74183|0.74731|0.00121|0.16%|0.74351|0.15%|0.74326|0.13%|1.154|0.000|290399891|40.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/19deb91002)|0.71431|0.71762|0.00064|0.09%|0.71559|-3.61%|0.71547|-3.61%|0.602|0.000|270761901|47.88 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57944|0.59151|0.00158|0.27%|0.58094|0.00%|0.58065|0.00%|5.294|0.999|1123402646|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c27368c939)|0.57970|0.59106|0.00128|0.22%|0.58165|0.12%|0.58148|0.14%|4.211|0.000|1119680585|44.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/19deb91002)|0.57628|0.59040|0.00153|0.26%|0.58161|0.12%|0.58142|0.13%|3.323|0.000|1119688460|44.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/19deb91002)|0.51752|0.51983|0.00052|0.10%|0.51877|-10.70%|0.51877|-10.66%|0.077|0.000|864865486|61.71 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43112|0.44651|0.00230|0.53%|0.43468|0.00%|0.43451|0.00%|1.525|0.999|2020638184|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c27368c939)|0.42350|0.43764|0.00255|0.60%|0.42718|-1.73%|0.42637|-1.87%|1.876|0.000|2020586747|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/19deb91002)|0.42371|0.43520|0.00199|0.47%|0.42682|-1.81%|0.42617|-1.92%|1.730|0.000|2020586662|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/19deb91002)|0.14685|0.15159|0.00103|0.69%|0.14896|-65.73%|0.14881|-65.75%|0.259|0.000|536605637|27.76 MB|
