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
| Time          |2025-12-10 00:50:24 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47346|0.47812|0.00066|0.14%|0.47617|0.00%|0.47604|0.00%|0.060|0.999|180942692|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9c81b52316)|0.46474|0.47327|0.00089|0.19%|0.47125|-1.03%|0.47125|-1.01%|-3.641|0.000|176335036|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/c380f7e382)|0.46886|0.47178|0.00054|0.11%|0.47013|-1.27%|0.47007|-1.25%|0.422|0.000|176405162|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c380f7e382)|0.44573|0.45525|0.00085|0.19%|0.45198|-5.08%|0.45195|-5.06%|-3.180|0.000|147903420|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74401|0.74751|0.00073|0.10%|0.74508|0.00%|0.74500|0.00%|0.782|0.999|291622011|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9c81b52316)|0.74483|0.75434|0.00167|0.22%|0.74705|0.26%|0.74651|0.20%|2.050|0.000|290398989|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/c380f7e382)|0.74248|0.75339|0.00209|0.28%|0.74456|-0.07%|0.74406|-0.13%|2.786|0.000|290399590|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c380f7e382)|0.71577|0.72017|0.00082|0.11%|0.71739|-3.72%|0.71731|-3.72%|1.106|0.000|270761842|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57973|0.58269|0.00059|0.10%|0.58115|0.00%|0.58117|0.00%|0.187|0.999|1123346529|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9c81b52316)|0.57952|0.59103|0.00158|0.27%|0.58123|0.01%|0.58100|-0.03%|4.682|0.093|1119623625|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/c380f7e382)|0.58007|0.58598|0.00086|0.15%|0.58189|0.13%|0.58176|0.10%|1.549|0.000|1119633130|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c380f7e382)|0.51445|0.51908|0.00059|0.11%|0.51776|-10.91%|0.51776|-10.91%|-1.464|0.000|865685150|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43062|0.43953|0.00194|0.45%|0.43451|0.00%|0.43456|0.00%|0.281|0.999|2020638165|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9c81b52316)|0.42493|0.43774|0.00284|0.66%|0.42849|-1.39%|0.42760|-1.60%|1.781|0.000|2020586645|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/c380f7e382)|0.42376|0.47729|0.00580|1.36%|0.42738|-1.64%|0.42602|-1.97%|6.757|0.000|2020586627|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c380f7e382)|0.14112|0.15116|0.00131|0.88%|0.14866|-65.79%|0.14867|-65.79%|-1.702|0.000|536605602|27.75 MB|
