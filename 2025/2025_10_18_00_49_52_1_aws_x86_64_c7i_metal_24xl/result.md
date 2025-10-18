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
| Time          |2025-10-18 00:49:52 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47561|0.47886|0.00054|0.11%|0.47661|0.00%|0.47651|0.00%|1.280|0.999|180946590|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/009cf303f9)|0.46714|0.47017|0.00063|0.13%|0.46824|-1.76%|0.46810|-1.77%|0.980|0.000|176334433|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f3ae90d2)|0.46788|0.47141|0.00062|0.13%|0.46930|-1.54%|0.46922|-1.53%|0.546|0.000|176403591|44.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f3ae90d2)|0.45002|0.45439|0.00065|0.14%|0.45117|-5.34%|0.45106|-5.34%|1.639|0.000|147877772|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74061|0.75379|0.00144|0.19%|0.74250|0.00%|0.74235|0.00%|5.057|0.999|291621492|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/009cf303f9)|0.73358|0.74632|0.00244|0.33%|0.73653|-0.80%|0.73592|-0.87%|2.358|0.000|287318896|40.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f3ae90d2)|0.73572|0.74703|0.00202|0.27%|0.73857|-0.53%|0.73811|-0.57%|2.055|0.000|287318847|40.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f3ae90d2)|0.70037|0.71295|0.00120|0.17%|0.70827|-4.61%|0.70823|-4.60%|-2.178|0.000|267681680|47.80 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57902|0.58465|0.00080|0.14%|0.58249|0.00%|0.58239|0.00%|-0.351|0.999|1123347010|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/009cf303f9)|0.58460|0.58781|0.00069|0.12%|0.58605|0.61%|0.58589|0.60%|0.828|0.000|1120242971|44.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f3ae90d2)|0.58356|0.58778|0.00080|0.14%|0.58519|0.46%|0.58509|0.46%|0.641|0.000|1120078384|44.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f3ae90d2)|0.51784|0.52126|0.00060|0.12%|0.51915|-10.87%|0.51902|-10.88%|1.008|0.000|866126709|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42961|0.43900|0.00191|0.44%|0.43358|0.00%|0.43346|0.00%|0.256|0.999|2020638182|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/009cf303f9)|0.42665|0.53268|0.01462|3.38%|0.43199|-0.37%|0.42924|-0.97%|6.708|0.000|2020595090|26.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f3ae90d2)|0.42384|0.43713|0.00277|0.65%|0.42669|-1.59%|0.42575|-1.78%|2.002|0.000|2020586565|26.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f3ae90d2)|0.14397|0.15003|0.00136|0.93%|0.14680|-66.14%|0.14675|-66.15%|0.334|0.000|536605608|27.69 MB|
