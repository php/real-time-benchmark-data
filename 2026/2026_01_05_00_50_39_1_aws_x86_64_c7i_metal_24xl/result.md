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
| Time          |2026-01-05 00:50:39 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47421|0.48174|0.00086|0.18%|0.47543|0.00%|0.47535|0.00%|4.121|0.999|180946469|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb63e4f998)|0.46628|0.47206|0.00073|0.16%|0.46738|-1.69%|0.46722|-1.71%|2.904|0.000|176330429|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb63e4f998)|0.46157|0.47019|0.00104|0.22%|0.46728|-1.71%|0.46723|-1.71%|-2.383|0.000|176407842|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb63e4f998)|0.44804|0.45079|0.00042|0.09%|0.44912|-5.53%|0.44905|-5.53%|0.927|0.000|147892070|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74102|0.74467|0.00073|0.10%|0.74269|0.00%|0.74255|0.00%|0.556|0.999|291620645|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb63e4f998)|0.74054|0.75136|0.00165|0.22%|0.74247|-0.03%|0.74210|-0.06%|3.547|0.000|290408441|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb63e4f998)|0.73992|0.75142|0.00194|0.26%|0.74224|-0.06%|0.74174|-0.11%|2.778|0.000|290408436|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb63e4f998)|0.71459|0.71837|0.00075|0.11%|0.71592|-3.60%|0.71589|-3.59%|0.839|0.000|270763815|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57939|0.58276|0.00073|0.13%|0.58085|0.00%|0.58083|0.00%|0.366|0.999|1123397049|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb63e4f998)|0.57964|0.58273|0.00069|0.12%|0.58093|0.01%|0.58083|0.00%|0.417|0.434|1125685503|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb63e4f998)|0.57954|0.59134|0.00207|0.36%|0.58144|0.10%|0.58095|0.02%|3.622|0.082|1125689939|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb63e4f998)|0.51685|0.51969|0.00056|0.11%|0.51823|-10.78%|0.51826|-10.77%|-0.012|0.000|871751227|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42955|0.44162|0.00235|0.54%|0.43481|0.00%|0.43476|0.00%|0.166|0.999|2020638191|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb63e4f998)|0.42472|0.43774|0.00310|0.72%|0.42842|-1.47%|0.42731|-1.71%|1.544|0.000|2020586714|27.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb63e4f998)|0.42503|0.43983|0.00293|0.69%|0.42807|-1.55%|0.42718|-1.74%|2.506|0.000|2020586731|27.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb63e4f998)|0.14463|0.15142|0.00133|0.90%|0.14694|-66.21%|0.14675|-66.25%|0.718|0.000|536605658|27.93 MB|
