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
| Time          |2025-12-28 00:50:47 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47635|0.48040|0.00066|0.14%|0.47831|0.00%|0.47822|0.00%|0.357|0.999|180942855|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/77d306ef38)|0.47053|0.47400|0.00066|0.14%|0.47175|-1.37%|0.47170|-1.36%|0.750|0.000|176329175|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecbdd2b580)|0.47131|0.47424|0.00058|0.12%|0.47266|-1.18%|0.47257|-1.18%|0.741|0.000|176404612|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecbdd2b580)|0.45167|0.45452|0.00049|0.11%|0.45268|-5.36%|0.45259|-5.36%|0.983|0.000|147891499|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74626|0.74958|0.00073|0.10%|0.74776|0.00%|0.74773|0.00%|0.306|0.999|291621940|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/77d306ef38)|0.74544|0.75721|0.00180|0.24%|0.74782|0.01%|0.74731|-0.06%|3.016|0.043|290411301|40.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecbdd2b580)|0.74635|0.75550|0.00163|0.22%|0.74853|0.10%|0.74813|0.05%|1.848|0.001|290409592|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecbdd2b580)|0.72134|0.72556|0.00082|0.11%|0.72313|-3.29%|0.72313|-3.29%|0.248|0.000|270766361|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57631|0.58357|0.00204|0.35%|0.57891|0.00%|0.57815|0.00%|0.759|0.999|1123347618|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/77d306ef38)|0.57767|0.58492|0.00194|0.33%|0.58030|0.24%|0.57932|0.20%|0.858|0.000|1119536042|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecbdd2b580)|0.57685|0.58277|0.00186|0.32%|0.57873|-0.03%|0.57783|-0.06%|0.886|0.707|1119538377|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecbdd2b580)|0.51417|0.52092|0.00158|0.31%|0.51615|-10.84%|0.51547|-10.84%|0.889|0.000|865600630|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42483|0.43944|0.00328|0.76%|0.43329|0.00%|0.43398|0.00%|-0.878|0.999|2020638200|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/77d306ef38)|0.43374|0.44978|0.00281|0.64%|0.44027|1.61%|0.43999|1.39%|0.658|0.000|2020586683|27.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/ecbdd2b580)|0.43358|0.44286|0.00206|0.47%|0.43848|1.20%|0.43864|1.07%|-0.219|0.000|2020586626|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ecbdd2b580)|0.13743|0.15082|0.00327|2.25%|0.14553|-66.41%|0.14656|-66.23%|-1.120|0.000|536605634|27.87 MB|
