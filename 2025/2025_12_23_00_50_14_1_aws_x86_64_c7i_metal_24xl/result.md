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
| Time          |2025-12-23 00:50:14 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47441|0.47771|0.00063|0.13%|0.47544|0.00%|0.47532|0.00%|0.932|0.999|180943497|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1faf17b017)|0.46821|0.47308|0.00100|0.21%|0.46940|-1.27%|0.46907|-1.32%|1.641|0.000|176333463|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/ef87a146fb)|0.46190|0.47394|0.00119|0.25%|0.46919|-1.31%|0.46903|-1.32%|-1.154|0.000|176405597|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ef87a146fb)|0.44824|0.45297|0.00088|0.20%|0.44910|-5.54%|0.44883|-5.57%|2.821|0.000|147895692|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74137|0.75473|0.00174|0.23%|0.74303|0.00%|0.74277|0.00%|5.194|0.999|291622010|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1faf17b017)|0.73975|0.75018|0.00125|0.17%|0.74126|-0.24%|0.74099|-0.24%|4.040|0.000|290414598|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/ef87a146fb)|0.73810|0.75034|0.00153|0.21%|0.74000|-0.41%|0.73974|-0.41%|3.710|0.000|290409551|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ef87a146fb)|0.71359|0.71739|0.00081|0.11%|0.71562|-3.69%|0.71555|-3.66%|0.222|0.000|270766434|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57924|0.64707|0.02855|4.76%|0.59969|0.00%|0.58160|0.00%|0.893|0.999|1123403258|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1faf17b017)|0.57982|0.64797|0.02862|4.77%|0.60021|0.09%|0.58175|0.03%|0.886|0.143|1119592245|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/ef87a146fb)|0.57765|0.65096|0.02870|4.80%|0.59794|-0.29%|0.57959|-0.35%|0.898|0.000|1119594935|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ef87a146fb)|0.51585|0.58628|0.02848|5.32%|0.53554|-10.70%|0.51722|-11.07%|0.905|0.000|864779661|61.82 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43021|0.44052|0.00215|0.50%|0.43468|0.00%|0.43465|0.00%|0.444|0.999|2020638119|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1faf17b017)|0.42345|0.48039|0.00774|1.81%|0.42850|-1.42%|0.42703|-1.75%|5.928|0.000|2020586639|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/ef87a146fb)|0.42487|0.48164|0.00599|1.40%|0.42792|-1.56%|0.42656|-1.86%|7.604|0.000|2020586638|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ef87a146fb)|0.13920|0.15006|0.00152|1.03%|0.14714|-66.15%|0.14718|-66.14%|-1.182|0.000|536605660|27.87 MB|
