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
| Time          |2025-11-05 00:50:17 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47564|0.47898|0.00057|0.12%|0.47688|0.00%|0.47683|0.00%|0.977|0.999|180948733|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/67e5d6cc2d)|0.46790|0.47284|0.00082|0.18%|0.46908|-1.64%|0.46891|-1.66%|1.624|0.000|176382309|44.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/1cf63a9380)|0.46822|0.47171|0.00061|0.13%|0.46941|-1.57%|0.46932|-1.57%|1.027|0.000|176445617|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1cf63a9380)|0.44826|0.45128|0.00045|0.10%|0.44909|-5.83%|0.44906|-5.82%|1.395|0.000|147928244|53.38 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74070|0.75344|0.00172|0.23%|0.74278|0.00%|0.74261|0.00%|4.346|0.999|291621225|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/67e5d6cc2d)|0.73970|0.74841|0.00158|0.21%|0.74281|0.00%|0.74250|-0.01%|1.337|0.823|290444939|40.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/1cf63a9380)|0.73990|0.75282|0.00203|0.27%|0.74262|-0.02%|0.74211|-0.07%|2.586|0.037|290445828|40.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1cf63a9380)|0.71767|0.72207|0.00089|0.12%|0.71941|-3.15%|0.71917|-3.16%|0.606|0.000|270808070|47.85 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57974|0.58473|0.00113|0.19%|0.58171|0.00%|0.58144|0.00%|0.610|0.999|1123344266|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/67e5d6cc2d)|0.57844|0.58295|0.00105|0.18%|0.58019|-0.26%|0.58002|-0.24%|0.481|0.000|1120016258|44.02 MB|
|[PHP - master](https://github.com/php/php-src/commit/1cf63a9380)|0.57789|0.58276|0.00116|0.20%|0.57999|-0.30%|0.57980|-0.28%|0.374|0.000|1119881362|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1cf63a9380)|0.51458|0.51994|0.00096|0.19%|0.51759|-11.02%|0.51748|-11.00%|0.092|0.000|865931202|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42472|0.44601|0.00272|0.63%|0.43361|0.00%|0.43333|0.00%|0.981|0.999|2020638169|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/67e5d6cc2d)|0.42511|0.48552|0.00653|1.52%|0.42920|-1.02%|0.42768|-1.31%|6.772|0.000|2020586645|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/1cf63a9380)|0.42399|0.43566|0.00264|0.62%|0.42687|-1.55%|0.42590|-1.71%|1.763|0.000|2020586588|26.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1cf63a9380)|0.14701|0.15290|0.00095|0.64%|0.14892|-65.66%|0.14881|-65.66%|0.941|0.000|536605597|27.73 MB|
