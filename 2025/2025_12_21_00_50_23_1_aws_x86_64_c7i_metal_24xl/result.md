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
| Time          |2025-12-21 00:50:23 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47430|0.47712|0.00053|0.11%|0.47552|0.00%|0.47547|0.00%|0.579|0.999|180943813|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/420f3dce52)|0.46728|0.47206|0.00077|0.16%|0.46838|-1.50%|0.46819|-1.53%|2.004|0.000|176332275|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/5dd5a4267f)|0.46655|0.47215|0.00067|0.14%|0.46956|-1.25%|0.46951|-1.25%|0.153|0.000|176408945|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5dd5a4267f)|0.44801|0.45224|0.00062|0.14%|0.44886|-5.61%|0.44876|-5.62%|2.258|0.000|147892341|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74215|0.74574|0.00072|0.10%|0.74343|0.00%|0.74342|0.00%|0.670|0.999|291621921|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/420f3dce52)|0.74236|0.75428|0.00176|0.24%|0.74406|0.08%|0.74366|0.03%|3.507|0.005|290411156|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/5dd5a4267f)|0.74156|0.75198|0.00175|0.24%|0.74341|-0.00%|0.74279|-0.08%|2.213|0.004|290409780|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5dd5a4267f)|0.71566|0.71943|0.00060|0.08%|0.71672|-3.59%|0.71660|-3.61%|1.266|0.000|270766390|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57879|0.58332|0.00074|0.13%|0.58119|0.00%|0.58123|0.00%|-0.520|0.999|1123347281|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/420f3dce52)|0.57886|0.59081|0.00125|0.22%|0.58135|0.03%|0.58120|-0.00%|4.336|0.798|1119535492|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/5dd5a4267f)|0.58045|0.58486|0.00076|0.13%|0.58199|0.14%|0.58188|0.11%|0.985|0.000|1119537679|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5dd5a4267f)|0.51341|0.51747|0.00071|0.14%|0.51588|-11.24%|0.51596|-11.23%|-0.904|0.000|865598958|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43030|0.43913|0.00188|0.43%|0.43436|0.00%|0.43421|0.00%|0.224|0.999|2020638200|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/420f3dce52)|0.42420|0.48151|0.00602|1.41%|0.42817|-1.42%|0.42688|-1.69%|7.266|0.000|2020586578|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/5dd5a4267f)|0.42352|0.44093|0.00318|0.74%|0.42795|-1.48%|0.42705|-1.65%|1.721|0.000|2020586685|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5dd5a4267f)|0.14418|0.15000|0.00124|0.85%|0.14686|-66.19%|0.14664|-66.23%|0.268|0.000|536605675|27.87 MB|
