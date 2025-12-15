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
| Time          |2025-12-15 00:50:23 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47418|0.47717|0.00052|0.11%|0.47542|0.00%|0.47533|0.00%|0.723|0.999|180944703|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ab11e77e8)|0.46662|0.46947|0.00057|0.12%|0.46806|-1.55%|0.46802|-1.54%|0.308|0.000|176343076|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/683075b77c)|0.46630|0.46991|0.00070|0.15%|0.46744|-1.68%|0.46732|-1.68%|1.740|0.000|176414213|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/683075b77c)|0.44676|0.45205|0.00063|0.14%|0.45001|-5.35%|0.44996|-5.34%|-0.424|0.000|147907159|53.41 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74139|0.75374|0.00218|0.29%|0.74295|0.00%|0.74255|0.00%|3.966|0.999|291625156|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ab11e77e8)|0.74137|0.75388|0.00152|0.20%|0.74360|0.09%|0.74339|0.11%|3.538|0.000|290403297|40.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/683075b77c)|0.73933|0.74971|0.00213|0.29%|0.74144|-0.20%|0.74061|-0.26%|1.870|0.000|290400122|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/683075b77c)|0.71420|0.71902|0.00068|0.10%|0.71561|-3.68%|0.71552|-3.64%|1.350|0.000|270762310|47.87 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57857|0.59085|0.00133|0.23%|0.58076|0.00%|0.58063|0.00%|4.495|0.999|1123340006|43.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ab11e77e8)|0.57777|0.58336|0.00092|0.16%|0.58094|0.03%|0.58095|0.05%|-0.353|0.007|1119634929|44.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/683075b77c)|0.57785|0.59018|0.00138|0.24%|0.58065|-0.02%|0.58070|0.01%|3.086|0.954|1119634858|44.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/683075b77c)|0.51452|0.51995|0.00085|0.17%|0.51642|-11.08%|0.51647|-11.05%|0.219|0.000|865687885|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43045|0.44245|0.00208|0.48%|0.43456|0.00%|0.43429|0.00%|0.829|0.999|2020638127|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ab11e77e8)|0.42390|0.43902|0.00291|0.68%|0.42821|-1.46%|0.42753|-1.56%|1.879|0.000|2020586695|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/683075b77c)|0.42343|0.43689|0.00268|0.63%|0.42748|-1.63%|0.42665|-1.76%|1.904|0.000|2020586675|26.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/683075b77c)|0.14255|0.15386|0.00139|0.93%|0.14893|-65.73%|0.14895|-65.70%|-0.217|0.000|536605674|27.82 MB|
