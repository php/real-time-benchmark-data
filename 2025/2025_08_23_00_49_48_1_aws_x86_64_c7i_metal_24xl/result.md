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
| GCC           |11.5.0|
| Time          |2025-08-23 00:49:48 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47057|0.47606|0.00080|0.17%|0.47377|0.00%|0.47378|0.00%|-0.318|0.999|181824459|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a1789cc34)|0.46867|0.47195|0.00060|0.13%|0.47015|-0.76%|0.47018|-0.76%|0.015|0.000|177215904|43.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/94d0b41db1)|0.46666|0.46945|0.00062|0.13%|0.46814|-1.19%|0.46831|-1.16%|-0.343|0.000|177214798|43.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/94d0b41db1)|0.45229|0.45629|0.00064|0.14%|0.45476|-4.01%|0.45483|-4.00%|-0.777|0.000|149588842|53.79 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74138|0.74879|0.00161|0.22%|0.74426|0.00%|0.74420|0.00%|0.408|0.999|292377476|39.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a1789cc34)|0.73651|0.74796|0.00231|0.31%|0.73967|-0.62%|0.73943|-0.64%|1.575|0.000|288309834|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/94d0b41db1)|0.73015|0.74785|0.00285|0.39%|0.73707|-0.97%|0.73663|-1.02%|1.507|0.000|288309832|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/94d0b41db1)|0.70061|0.71269|0.00166|0.23%|0.70790|-4.89%|0.70795|-4.87%|-0.306|0.000|267478392|48.06 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58164|0.58662|0.00081|0.14%|0.58403|0.00%|0.58401|0.00%|-0.101|0.999|1133181994|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a1789cc34)|0.58148|0.58623|0.00082|0.14%|0.58421|0.03%|0.58424|0.04%|-0.502|0.059|1129313802|43.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/94d0b41db1)|0.57714|0.58347|0.00083|0.14%|0.58187|-0.37%|0.58194|-0.36%|-2.163|0.000|1129314889|43.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/94d0b41db1)|0.51475|0.51832|0.00063|0.12%|0.51713|-11.45%|0.51717|-11.45%|-1.233|0.000|867869344|61.47 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42810|0.43584|0.00163|0.38%|0.43146|0.00%|0.43136|0.00%|0.173|0.999|2031002254|26.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4a1789cc34)|0.42763|0.60170|0.02705|6.21%|0.43550|0.94%|0.42982|-0.36%|4.950|0.000|2031543256|26.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/94d0b41db1)|0.43418|0.59834|0.03451|7.73%|0.44662|3.51%|0.43647|1.18%|3.220|0.000|2031543272|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/94d0b41db1)|0.14587|0.15332|0.00137|0.92%|0.14832|-65.62%|0.14814|-65.66%|1.092|0.000|537062352|27.91 MB|
