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
| Time          |2025-09-29 00:50:04 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46939|0.47908|0.00092|0.19%|0.47687|0.00%|0.47686|0.00%|-5.352|0.999|180944868|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee2da6d9e9)|0.46330|0.47914|0.00144|0.30%|0.47072|-1.29%|0.47050|-1.33%|1.286|0.000|176329353|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/898235127b)|0.46938|0.47395|0.00079|0.17%|0.47059|-1.32%|0.47049|-1.34%|2.200|0.000|176400563|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/898235127b)|0.44827|0.45251|0.00067|0.15%|0.44928|-5.78%|0.44916|-5.81%|2.647|0.000|147882424|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74060|0.74576|0.00088|0.12%|0.74213|0.00%|0.74192|0.00%|1.052|0.999|291622950|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee2da6d9e9)|0.73843|0.75120|0.00150|0.20%|0.74028|-0.25%|0.73995|-0.27%|4.089|0.000|287357840|40.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/898235127b)|0.73782|0.75002|0.00214|0.29%|0.74001|-0.29%|0.73935|-0.35%|3.108|0.000|287354470|40.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/898235127b)|0.70909|0.71209|0.00063|0.09%|0.71040|-4.28%|0.71033|-4.26%|0.548|0.000|267691202|47.58 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58148|0.58961|0.00100|0.17%|0.58723|0.00%|0.58721|0.00%|-1.577|0.999|1123346598|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee2da6d9e9)|0.58488|0.58926|0.00082|0.14%|0.58678|-0.08%|0.58680|-0.07%|0.568|0.000|1120252039|44.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/898235127b)|0.58459|0.58952|0.00079|0.13%|0.58621|-0.17%|0.58608|-0.19%|1.052|0.000|1120260467|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/898235127b)|0.52131|0.52443|0.00065|0.12%|0.52298|-10.94%|0.52306|-10.92%|-0.332|0.000|866320667|61.56 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42949|0.44103|0.00215|0.50%|0.43419|0.00%|0.43409|0.00%|0.289|0.999|2020638204|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee2da6d9e9)|0.42747|0.53703|0.01629|3.75%|0.43455|0.08%|0.43153|-0.59%|5.495|0.000|2020595044|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/898235127b)|0.42560|0.52188|0.00945|2.20%|0.43041|-0.87%|0.42924|-1.12%|9.346|0.000|2020594963|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/898235127b)|0.14724|0.15188|0.00103|0.69%|0.14929|-65.62%|0.14930|-65.61%|0.255|0.000|536613111|27.74 MB|
