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
| Time          |2025-11-29 00:50:08 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47701|0.48403|0.00086|0.18%|0.47832|0.00%|0.47822|0.00%|3.136|0.999|180944626|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ada7400690)|0.47024|0.47272|0.00055|0.12%|0.47125|-1.48%|0.47120|-1.47%|0.334|0.000|176334703|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/56795d2810)|0.46643|0.47659|0.00109|0.23%|0.47282|-1.15%|0.47267|-1.16%|-1.257|0.000|176409013|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56795d2810)|0.45144|0.45757|0.00073|0.16%|0.45355|-5.18%|0.45344|-5.18%|2.522|0.000|147884756|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74443|0.75741|0.00177|0.24%|0.74645|0.00%|0.74604|0.00%|4.181|0.999|291621921|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ada7400690)|0.73599|0.75263|0.00212|0.29%|0.74320|-0.44%|0.74276|-0.44%|2.277|0.000|290398660|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/56795d2810)|0.74605|0.75086|0.00102|0.14%|0.74744|0.13%|0.74727|0.16%|1.115|0.000|290399517|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56795d2810)|0.71708|0.72348|0.00084|0.12%|0.71994|-3.55%|0.71986|-3.51%|0.670|0.000|270762029|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57659|0.64088|0.00638|1.10%|0.57878|0.00%|0.57784|0.00%|9.507|0.999|1123344967|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ada7400690)|0.57463|0.64292|0.00672|1.16%|0.57768|-0.19%|0.57668|-0.20%|9.449|0.000|1119622838|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/56795d2810)|0.57714|0.64386|0.00674|1.16%|0.57949|0.12%|0.57825|0.07%|9.026|0.000|1119632589|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56795d2810)|0.51367|0.58436|0.00699|1.36%|0.51563|-10.91%|0.51472|-10.92%|9.785|0.000|865682803|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42612|0.44262|0.00295|0.68%|0.43406|0.00%|0.43423|0.00%|-0.457|0.999|2020638124|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ada7400690)|0.42170|0.43877|0.00319|0.75%|0.42685|-1.66%|0.42603|-1.89%|1.937|0.000|2020586697|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/56795d2810)|0.42179|0.44170|0.00332|0.78%|0.42763|-1.48%|0.42666|-1.74%|1.594|0.000|2020586664|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/56795d2810)|0.14121|0.15198|0.00195|1.31%|0.14835|-65.82%|0.14875|-65.74%|-1.973|0.000|536605625|27.74 MB|
