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
| Time          |2025-10-21 00:50:11 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47520|0.48179|0.00081|0.17%|0.47643|0.00%|0.47630|0.00%|3.361|0.999|180946569|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c52bc26a)|0.46142|0.47500|0.00115|0.24%|0.46833|-1.70%|0.46821|-1.70%|-0.004|0.000|176336300|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/17652409b8)|0.46814|0.47090|0.00054|0.11%|0.46903|-1.55%|0.46896|-1.54%|0.987|0.000|176404424|44.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17652409b8)|0.45024|0.45514|0.00062|0.14%|0.45138|-5.26%|0.45128|-5.25%|3.124|0.000|147875554|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74015|0.75159|0.00124|0.17%|0.74177|0.00%|0.74158|0.00%|5.200|0.999|291621472|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c52bc26a)|0.72755|0.74654|0.00172|0.23%|0.73744|-0.58%|0.73739|-0.56%|-0.231|0.000|287322291|40.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/17652409b8)|0.73141|0.74354|0.00163|0.22%|0.73344|-1.12%|0.73316|-1.13%|3.158|0.000|287318806|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17652409b8)|0.69823|0.70767|0.00105|0.15%|0.70606|-4.81%|0.70601|-4.80%|-4.020|0.000|267681799|47.79 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57995|0.59184|0.00129|0.22%|0.58221|0.00%|0.58195|0.00%|4.561|0.999|1123343627|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c52bc26a)|0.58237|0.58642|0.00076|0.13%|0.58406|0.32%|0.58400|0.35%|0.520|0.000|1120065640|44.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/17652409b8)|0.58159|0.58583|0.00076|0.13%|0.58347|0.22%|0.58330|0.23%|0.594|0.000|1120075712|44.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17652409b8)|0.51705|0.52042|0.00059|0.11%|0.51852|-10.94%|0.51847|-10.91%|0.371|0.000|866123104|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42968|0.44420|0.00245|0.56%|0.43382|0.00%|0.43358|0.00%|1.441|0.999|2020638188|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c52bc26a)|0.42412|0.48203|0.00776|1.81%|0.42831|-1.27%|0.42661|-1.61%|6.116|0.000|2020586586|26.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/17652409b8)|0.42433|0.43949|0.00308|0.72%|0.42737|-1.49%|0.42632|-1.67%|2.027|0.000|2020586602|26.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17652409b8)|0.14394|0.14982|0.00124|0.84%|0.14672|-66.18%|0.14665|-66.18%|0.208|0.000|536605618|27.68 MB|
