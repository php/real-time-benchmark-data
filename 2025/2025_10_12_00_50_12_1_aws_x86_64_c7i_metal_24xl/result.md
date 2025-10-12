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
| Time          |2025-10-12 00:50:12 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47618|0.48292|0.00083|0.17%|0.47746|0.00%|0.47733|0.00%|3.323|0.999|180946376|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/106079a462)|0.47031|0.47491|0.00072|0.15%|0.47145|-1.26%|0.47133|-1.26%|1.932|0.000|176327172|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/f543f4951c)|0.46763|0.47125|0.00055|0.12%|0.46867|-1.84%|0.46857|-1.84%|1.316|0.000|176399524|44.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f543f4951c)|0.44929|0.45144|0.00047|0.10%|0.45024|-5.70%|0.45020|-5.69%|0.474|0.000|147876037|53.45 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73262|0.75388|0.00202|0.27%|0.74305|0.00%|0.74290|0.00%|1.392|0.999|291621393|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/106079a462)|0.73148|0.75207|0.00196|0.26%|0.74302|-0.00%|0.74275|-0.02%|-0.280|0.480|287318800|40.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/f543f4951c)|0.73584|0.74860|0.00204|0.28%|0.73819|-0.65%|0.73758|-0.72%|2.520|0.000|287319177|40.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f543f4951c)|0.70684|0.71106|0.00065|0.09%|0.70835|-4.67%|0.70830|-4.66%|0.840|0.000|267681399|47.84 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58179|0.59336|0.00127|0.22%|0.58299|0.00%|0.58273|0.00%|5.802|0.999|1123344689|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/106079a462)|0.57868|0.58634|0.00094|0.16%|0.58423|0.21%|0.58416|0.24%|-1.558|0.000|1120201279|44.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/f543f4951c)|0.58418|0.58810|0.00078|0.13%|0.58567|0.46%|0.58551|0.48%|0.772|0.000|1120246041|44.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f543f4951c)|0.51868|0.52123|0.00048|0.09%|0.51995|-10.81%|0.52000|-10.77%|-0.070|0.000|866300332|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42967|0.43906|0.00199|0.46%|0.43336|0.00%|0.43309|0.00%|0.614|0.999|2020638150|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/106079a462)|0.43679|0.55123|0.02004|4.51%|0.44391|2.43%|0.43962|1.51%|4.736|0.000|2020595011|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/f543f4951c)|0.43780|0.55609|0.01871|4.21%|0.44426|2.51%|0.44085|1.79%|5.516|0.000|2020595025|27.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f543f4951c)|0.14506|0.14995|0.00105|0.71%|0.14760|-65.94%|0.14756|-65.93%|-0.031|0.000|536613134|27.80 MB|
