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
| Time          |2025-12-16 00:50:16 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47456|0.47736|0.00063|0.13%|0.47579|0.00%|0.47577|0.00%|0.318|0.999|180942846|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/683075b77c)|0.46655|0.47215|0.00085|0.18%|0.46804|-1.63%|0.46786|-1.66%|1.727|0.000|176338230|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/7dd5f31dde)|0.46878|0.47315|0.00067|0.14%|0.46996|-1.23%|0.46977|-1.26%|1.373|0.000|176395889|44.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7dd5f31dde)|0.44730|0.45232|0.00064|0.14%|0.44817|-5.81%|0.44806|-5.82%|3.075|0.000|147872340|53.52 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74299|0.75484|0.00129|0.17%|0.74457|0.00%|0.74445|0.00%|5.127|0.999|291622012|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/683075b77c)|0.74168|0.74761|0.00133|0.18%|0.74412|-0.06%|0.74386|-0.08%|0.651|0.002|290403188|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/7dd5f31dde)|0.74006|0.75228|0.00186|0.25%|0.74233|-0.30%|0.74190|-0.34%|3.087|0.000|290419081|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7dd5f31dde)|0.71711|0.72018|0.00070|0.10%|0.71851|-3.50%|0.71848|-3.49%|0.370|0.000|270763140|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57958|0.59200|0.00155|0.27%|0.58172|0.00%|0.58150|0.00%|5.254|0.999|1123345739|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/683075b77c)|0.58012|0.58449|0.00080|0.14%|0.58172|0.00%|0.58152|0.00%|1.090|0.256|1119625076|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/7dd5f31dde)|0.58318|0.58633|0.00063|0.11%|0.58429|0.44%|0.58422|0.47%|0.509|0.000|1119524398|44.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7dd5f31dde)|0.51648|0.51866|0.00049|0.09%|0.51752|-11.04%|0.51751|-11.00%|0.255|0.000|865586267|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42960|0.43962|0.00215|0.49%|0.43458|0.00%|0.43450|0.00%|0.092|0.999|2020638153|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/683075b77c)|0.42440|0.44168|0.00308|0.72%|0.42875|-1.34%|0.42781|-1.54%|1.975|0.000|2020586661|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/7dd5f31dde)|0.42329|0.43593|0.00281|0.66%|0.42704|-1.74%|0.42633|-1.88%|1.419|0.000|2020586659|27.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7dd5f31dde)|0.13817|0.15102|0.00171|1.17%|0.14664|-66.26%|0.14661|-66.26%|-1.400|0.000|536605493|27.93 MB|
