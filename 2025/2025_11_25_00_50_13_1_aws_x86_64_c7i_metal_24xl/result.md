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
| Time          |2025-11-25 00:50:13 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47411|0.48157|0.00079|0.17%|0.47603|0.00%|0.47592|0.00%|3.508|0.999|180945968|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ca914ee389)|0.46641|0.47002|0.00069|0.15%|0.46789|-1.71%|0.46778|-1.71%|1.168|0.000|176341067|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.46175|0.47121|0.00090|0.19%|0.46851|-1.58%|0.46852|-1.56%|-3.903|0.000|176409832|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.44890|0.45310|0.00058|0.13%|0.44991|-5.49%|0.44985|-5.48%|2.037|0.000|147893945|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74285|0.75554|0.00175|0.23%|0.74460|0.00%|0.74427|0.00%|5.036|0.999|291625154|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ca914ee389)|0.73794|0.75032|0.00175|0.24%|0.73990|-0.63%|0.73948|-0.64%|3.937|0.000|290402240|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.73958|0.75129|0.00184|0.25%|0.74154|-0.41%|0.74117|-0.42%|2.713|0.000|290399484|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.70869|0.71882|0.00105|0.15%|0.71688|-3.72%|0.71688|-3.68%|-4.747|0.000|270761598|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57942|0.58334|0.00070|0.12%|0.58061|0.00%|0.58048|0.00%|0.789|0.999|1123341238|43.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ca914ee389)|0.57812|0.58153|0.00079|0.14%|0.57954|-0.18%|0.57942|-0.18%|0.406|0.000|1119635695|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.57820|0.58230|0.00085|0.15%|0.57998|-0.11%|0.57991|-0.10%|0.708|0.000|1119643056|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.51311|0.51827|0.00075|0.14%|0.51664|-11.02%|0.51661|-11.00%|-1.484|0.000|865687402|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43042|0.44024|0.00187|0.43%|0.43488|0.00%|0.43477|0.00%|0.263|0.999|2020638145|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ca914ee389)|0.42240|0.47998|0.00580|1.36%|0.42795|-1.59%|0.42693|-1.80%|7.539|0.000|2020586611|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.42397|0.48043|0.00596|1.40%|0.42741|-1.72%|0.42629|-1.95%|7.408|0.000|2020586684|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.14645|0.15134|0.00098|0.66%|0.14865|-65.82%|0.14861|-65.82%|0.332|0.000|536605703|27.75 MB|
