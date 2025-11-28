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
| Time          |2025-11-28 00:50:03 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47700|0.48370|0.00080|0.17%|0.47834|0.00%|0.47817|0.00%|3.286|0.999|180942610|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ada7400690)|0.47008|0.47430|0.00075|0.16%|0.47119|-1.49%|0.47107|-1.48%|1.710|0.000|176333782|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/ada7400690)|0.46974|0.47409|0.00073|0.16%|0.47128|-1.48%|0.47116|-1.47%|1.209|0.000|176406556|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ada7400690)|0.44770|0.45407|0.00067|0.15%|0.45292|-5.31%|0.45295|-5.28%|-4.729|0.000|147884032|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73815|0.75703|0.00157|0.21%|0.74696|0.00%|0.74681|0.00%|0.982|0.999|291621926|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ada7400690)|0.74156|0.75207|0.00148|0.20%|0.74340|-0.48%|0.74313|-0.49%|2.871|0.000|290398701|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/ada7400690)|0.74135|0.74775|0.00123|0.17%|0.74322|-0.50%|0.74300|-0.51%|1.637|0.000|290399524|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ada7400690)|0.71775|0.72304|0.00086|0.12%|0.71948|-3.68%|0.71931|-3.68%|1.121|0.000|270762058|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57638|0.59203|0.00244|0.42%|0.58104|0.00%|0.58136|0.00%|1.056|0.999|1123348713|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ada7400690)|0.57590|0.58665|0.00189|0.33%|0.57993|-0.19%|0.58037|-0.17%|-0.500|0.000|1119623013|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/ada7400690)|0.57611|0.58924|0.00188|0.32%|0.57973|-0.23%|0.58027|-0.19%|0.513|0.000|1119633651|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ada7400690)|0.51400|0.51872|0.00123|0.24%|0.51698|-11.03%|0.51732|-11.02%|-1.069|0.000|865683930|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42512|0.43958|0.00343|0.79%|0.43362|0.00%|0.43443|0.00%|-0.609|0.999|2020638157|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ada7400690)|0.42157|0.47823|0.00592|1.39%|0.42709|-1.51%|0.42625|-1.88%|6.778|0.000|2020586669|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/ada7400690)|0.42166|0.47917|0.00617|1.44%|0.42733|-1.45%|0.42620|-1.89%|6.296|0.000|2020586598|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ada7400690)|0.14031|0.15122|0.00285|1.93%|0.14757|-65.97%|0.14845|-65.83%|-1.641|0.000|536605731|27.75 MB|
