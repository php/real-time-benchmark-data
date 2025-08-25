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
| Time          |2025-08-25 00:49:59 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47201|0.47751|0.00084|0.18%|0.47350|0.00%|0.47337|0.00%|1.841|0.999|181824345|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f041c13c94)|0.46289|0.47404|0.00094|0.20%|0.46851|-1.05%|0.46842|-1.04%|0.001|0.000|177212673|43.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.46779|0.47035|0.00052|0.11%|0.46887|-0.98%|0.46887|-0.95%|0.352|0.000|177212742|43.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.45157|0.45381|0.00050|0.11%|0.45262|-4.41%|0.45262|-4.38%|0.190|0.000|149597207|53.79 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74236|0.74642|0.00092|0.12%|0.74417|0.00%|0.74399|0.00%|0.601|0.999|292385322|39.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f041c13c94)|0.73351|0.74599|0.00218|0.30%|0.73559|-1.15%|0.73516|-1.19%|3.189|0.000|288310130|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.73361|0.74095|0.00117|0.16%|0.73556|-1.16%|0.73533|-1.16%|1.935|0.000|288310010|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.70307|0.70760|0.00096|0.14%|0.70468|-5.31%|0.70451|-5.31%|1.076|0.000|267475146|48.06 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58262|0.59259|0.00106|0.18%|0.58436|0.00%|0.58420|0.00%|4.936|0.999|1133179724|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f041c13c94)|0.58379|0.58771|0.00070|0.12%|0.58487|0.09%|0.58471|0.09%|1.216|0.000|1129324392|43.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.57892|0.58651|0.00084|0.14%|0.58478|0.07%|0.58482|0.11%|-3.315|0.000|1129325456|43.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.51693|0.51931|0.00045|0.09%|0.51806|-11.35%|0.51809|-11.32%|0.093|0.000|867867141|61.47 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42801|0.44004|0.00191|0.44%|0.43143|0.00%|0.43098|0.00%|1.198|0.999|2031002351|26.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f041c13c94)|0.42884|0.59116|0.02574|5.88%|0.43762|1.43%|0.43276|0.41%|5.175|0.000|2031543233|26.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.42962|0.54505|0.03075|6.93%|0.44387|2.88%|0.43342|0.57%|2.549|0.000|2031543270|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fc0dd9d4ca)|0.14625|0.15269|0.00129|0.86%|0.14914|-65.43%|0.14910|-65.41%|0.335|0.000|537062386|27.90 MB|
