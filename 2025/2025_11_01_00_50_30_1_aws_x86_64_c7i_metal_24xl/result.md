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
| Time          |2025-11-01 00:50:30 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47499|0.48285|0.00090|0.19%|0.47628|0.00%|0.47612|0.00%|4.131|0.999|180946239|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/425b97e0b6)|0.46855|0.47572|0.00100|0.21%|0.46970|-1.38%|0.46949|-1.39%|3.761|0.000|176328114|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d45069560)|0.46230|0.47239|0.00114|0.24%|0.46915|-1.50%|0.46903|-1.49%|-1.193|0.000|176402783|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d45069560)|0.44848|0.45215|0.00055|0.12%|0.44948|-5.63%|0.44940|-5.61%|2.192|0.000|147873973|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73886|0.75154|0.00138|0.19%|0.74074|0.00%|0.74053|0.00%|5.004|0.999|291621161|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/425b97e0b6)|0.73543|0.74652|0.00154|0.21%|0.73720|-0.48%|0.73674|-0.51%|2.754|0.000|287331601|40.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d45069560)|0.73517|0.74581|0.00168|0.23%|0.73716|-0.48%|0.73677|-0.51%|2.766|0.000|287331262|40.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d45069560)|0.69952|0.71001|0.00109|0.15%|0.70834|-4.37%|0.70833|-4.35%|-5.345|0.000|267694221|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58148|0.60017|0.00298|0.51%|0.58576|0.00%|0.58645|0.00%|1.478|0.999|1123341676|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/425b97e0b6)|0.58432|0.59395|0.00261|0.44%|0.58873|0.51%|0.58995|0.60%|-0.424|0.000|1120308128|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d45069560)|0.58332|0.59701|0.00262|0.45%|0.58803|0.39%|0.58925|0.48%|-0.142|0.000|1120318524|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d45069560)|0.51680|0.52511|0.00226|0.43%|0.52081|-11.09%|0.52194|-11.00%|-0.553|0.000|866366257|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42908|0.44507|0.00218|0.50%|0.43351|0.00%|0.43339|0.00%|1.592|0.999|2020638143|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/425b97e0b6)|0.42322|0.43946|0.00306|0.72%|0.42719|-1.46%|0.42632|-1.63%|2.208|0.000|2020586598|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/2d45069560)|0.42372|0.43668|0.00248|0.58%|0.42676|-1.56%|0.42598|-1.71%|2.233|0.000|2020586677|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2d45069560)|0.13827|0.15060|0.00153|1.04%|0.14660|-66.18%|0.14671|-66.15%|-1.242|0.000|536605623|27.67 MB|
