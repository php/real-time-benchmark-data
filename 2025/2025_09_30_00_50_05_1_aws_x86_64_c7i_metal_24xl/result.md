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
| Time          |2025-09-30 00:50:05 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47296|0.48230|0.00086|0.18%|0.47667|0.00%|0.47661|0.00%|2.277|0.999|180947807|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/898235127b)|0.46336|0.47644|0.00127|0.27%|0.47051|-1.29%|0.47036|-1.31%|0.223|0.000|176329146|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/96aa0e08a1)|0.47054|0.47427|0.00059|0.12%|0.47148|-1.09%|0.47137|-1.10%|1.585|0.000|176404417|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96aa0e08a1)|0.44760|0.45207|0.00061|0.14%|0.44842|-5.93%|0.44834|-5.93%|3.011|0.000|147877218|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73988|0.74393|0.00085|0.11%|0.74157|0.00%|0.74147|0.00%|0.326|0.999|291622841|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/898235127b)|0.73654|0.74185|0.00114|0.15%|0.73849|-0.42%|0.73825|-0.43%|0.937|0.000|287354428|40.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/96aa0e08a1)|0.73296|0.74195|0.00134|0.18%|0.73491|-0.90%|0.73463|-0.92%|2.368|0.000|287354353|40.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96aa0e08a1)|0.70623|0.70952|0.00067|0.09%|0.70764|-4.58%|0.70758|-4.57%|0.395|0.000|267690862|47.58 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57756|0.59806|0.00274|0.47%|0.57969|0.00%|0.57878|0.00%|3.916|0.999|1123345227|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/898235127b)|0.57656|0.58644|0.00235|0.41%|0.57887|-0.14%|0.57796|-0.14%|1.806|0.000|1120249448|44.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/96aa0e08a1)|0.57729|0.58705|0.00218|0.38%|0.57977|0.01%|0.57897|0.03%|1.886|0.286|1120256579|44.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96aa0e08a1)|0.51453|0.52297|0.00192|0.37%|0.51685|-10.84%|0.51620|-10.81%|1.954|0.000|866315639|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42708|0.43905|0.00217|0.50%|0.43335|0.00%|0.43304|0.00%|0.193|0.999|2020638119|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/898235127b)|0.42431|0.58647|0.03091|7.02%|0.44012|1.56%|0.42920|-0.89%|2.803|0.000|2020595064|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/96aa0e08a1)|0.42583|0.53143|0.01920|4.43%|0.43333|-0.00%|0.42885|-0.97%|4.647|0.000|2020595083|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96aa0e08a1)|0.14744|0.15260|0.00091|0.61%|0.14949|-65.50%|0.14931|-65.52%|0.617|0.000|536613197|27.73 MB|
