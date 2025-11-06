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
| Time          |2025-11-06 00:50:20 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47102|0.47822|0.00073|0.15%|0.47619|0.00%|0.47617|0.00%|-3.252|0.999|180951287|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1cf63a9380)|0.46189|0.47374|0.00105|0.22%|0.46912|-1.48%|0.46907|-1.49%|-2.290|0.000|176380273|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3c5163c25)|0.46570|0.46844|0.00064|0.14%|0.46685|-1.96%|0.46678|-1.97%|0.418|0.000|176450375|44.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3c5163c25)|0.44585|0.45040|0.00066|0.15%|0.44673|-6.19%|0.44659|-6.21%|2.832|0.000|147930423|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73492|0.75104|0.00197|0.27%|0.74085|0.00%|0.74056|0.00%|3.526|0.999|291624373|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1cf63a9380)|0.73935|0.75451|0.00215|0.29%|0.74144|0.08%|0.74094|0.05%|4.413|0.000|290448734|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3c5163c25)|0.73506|0.74713|0.00171|0.23%|0.73701|-0.52%|0.73656|-0.54%|2.947|0.000|290445438|40.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3c5163c25)|0.71055|0.71581|0.00081|0.11%|0.71206|-3.89%|0.71198|-3.86%|1.444|0.000|270807856|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57544|0.58564|0.00160|0.28%|0.57812|0.00%|0.57776|0.00%|2.229|0.999|1123340520|43.58 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1cf63a9380)|0.57375|0.58568|0.00173|0.30%|0.57678|-0.23%|0.57630|-0.25%|2.205|0.000|1119885822|44.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3c5163c25)|0.57528|0.58289|0.00144|0.25%|0.57772|-0.07%|0.57760|-0.03%|1.533|0.023|1119894139|44.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3c5163c25)|0.51231|0.51813|0.00104|0.20%|0.51471|-10.97%|0.51457|-10.94%|1.275|0.000|865939136|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42648|0.44521|0.00260|0.60%|0.43378|0.00%|0.43364|0.00%|1.299|0.999|2020638178|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1cf63a9380)|0.42393|0.44042|0.00277|0.65%|0.42807|-1.32%|0.42718|-1.49%|2.084|0.000|2020586580|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/d3c5163c25)|0.42359|0.47798|0.00554|1.30%|0.42724|-1.51%|0.42606|-1.75%|7.951|0.000|2020586555|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d3c5163c25)|0.14671|0.15143|0.00090|0.61%|0.14880|-65.70%|0.14870|-65.71%|0.241|0.000|536605549|27.74 MB|
