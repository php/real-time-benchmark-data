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
| Time          |2025-11-04 00:50:12 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47611|0.48051|0.00087|0.18%|0.47778|0.00%|0.47776|0.00%|0.530|0.999|180946139|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49c3ff6c89)|0.47083|0.47519|0.00092|0.19%|0.47294|-1.01%|0.47297|-1.00%|0.116|0.000|176332107|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/67e5d6cc2d)|0.46879|0.47371|0.00083|0.18%|0.47016|-1.59%|0.47011|-1.60%|0.826|0.000|176453426|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/67e5d6cc2d)|0.44482|0.45268|0.00098|0.22%|0.45088|-5.63%|0.45091|-5.62%|-2.180|0.000|147934140|53.34 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74137|0.75443|0.00178|0.24%|0.74430|0.00%|0.74407|0.00%|3.552|0.999|291621226|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49c3ff6c89)|0.73365|0.75195|0.00189|0.25%|0.74340|-0.12%|0.74311|-0.13%|0.509|0.000|287334714|40.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/67e5d6cc2d)|0.74080|0.75378|0.00178|0.24%|0.74435|0.01%|0.74394|-0.02%|2.121|0.803|290445061|40.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/67e5d6cc2d)|0.71171|0.72104|0.00116|0.16%|0.71729|-3.63%|0.71714|-3.62%|-0.670|0.000|270807908|47.81 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58152|0.58569|0.00077|0.13%|0.58279|0.00%|0.58269|0.00%|1.031|0.999|1123344211|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49c3ff6c89)|0.58408|0.58866|0.00078|0.13%|0.58545|0.46%|0.58529|0.45%|1.354|0.000|1120309165|44.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/67e5d6cc2d)|0.58006|0.58510|0.00081|0.14%|0.58171|-0.19%|0.58161|-0.19%|1.454|0.000|1120023352|44.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/67e5d6cc2d)|0.51717|0.51972|0.00053|0.10%|0.51859|-11.02%|0.51853|-11.01%|-0.036|0.000|866077097|61.45 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42762|0.43839|0.00203|0.47%|0.43362|0.00%|0.43361|0.00%|0.154|0.999|2020638188|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/49c3ff6c89)|0.42420|0.44018|0.00293|0.68%|0.42781|-1.34%|0.42703|-1.52%|2.336|0.000|2020586628|26.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/67e5d6cc2d)|0.42373|0.47727|0.00554|1.29%|0.42783|-1.34%|0.42660|-1.62%|7.394|0.000|2020586576|26.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/67e5d6cc2d)|0.14668|0.15156|0.00095|0.64%|0.14872|-65.70%|0.14872|-65.70%|0.152|0.000|536605538|27.69 MB|
