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
| Time          |2025-09-07 00:50:22 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47049|0.47762|0.00103|0.22%|0.47164|0.00%|0.47149|0.00%|3.819|0.999|180914259|43.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/366a5a2b37)|0.46792|0.47446|0.00083|0.18%|0.46886|-0.59%|0.46874|-0.58%|4.134|0.000|176227189|44.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/b90ab8119e)|0.46058|0.47198|0.00132|0.28%|0.46773|-0.83%|0.46770|-0.80%|-1.948|0.000|176302905|44.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b90ab8119e)|0.44659|0.44839|0.00039|0.09%|0.44743|-5.13%|0.44742|-5.10%|0.269|0.000|147770690|53.38 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73793|0.74362|0.00088|0.12%|0.73935|0.00%|0.73920|0.00%|1.473|0.999|291580933|39.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/366a5a2b37)|0.73413|0.74485|0.00207|0.28%|0.73613|-0.44%|0.73541|-0.51%|2.522|0.000|287300985|40.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/b90ab8119e)|0.73452|0.74530|0.00229|0.31%|0.73714|-0.30%|0.73633|-0.39%|1.873|0.000|287301152|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b90ab8119e)|0.71014|0.71501|0.00079|0.11%|0.71154|-3.76%|0.71144|-3.76%|1.381|0.000|267655925|47.58 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57900|0.58260|0.00063|0.11%|0.58020|0.00%|0.58011|0.00%|0.786|0.999|1123015380|43.46 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/366a5a2b37)|0.58229|0.58534|0.00065|0.11%|0.58348|0.56%|0.58339|0.56%|0.633|0.000|1120756681|43.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/b90ab8119e)|0.58194|0.58547|0.00072|0.12%|0.58316|0.51%|0.58303|0.50%|1.433|0.000|1120762289|43.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b90ab8119e)|0.51829|0.52059|0.00048|0.09%|0.51945|-10.47%|0.51940|-10.47%|0.140|0.000|867081990|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42838|0.44192|0.00184|0.43%|0.43136|0.00%|0.43100|0.00%|2.380|0.999|2020733072|26.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/366a5a2b37)|0.42448|0.55664|0.02099|4.87%|0.43088|-0.11%|0.42695|-0.94%|5.471|0.000|2020744450|27.02 MB|
|[PHP - master](https://github.com/php/php-src/commit/b90ab8119e)|0.42394|0.58774|0.03335|7.66%|0.43553|0.97%|0.42648|-1.05%|3.595|0.000|2020744539|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b90ab8119e)|0.14753|0.15348|0.00108|0.72%|0.14969|-65.30%|0.14951|-65.31%|0.595|0.000|536712623|28.04 MB|
