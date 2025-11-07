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
| Time          |2025-11-07 00:50:15 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47751|0.48206|0.00070|0.15%|0.47874|0.00%|0.47866|0.00%|1.490|0.999|180948448|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3c5163c25)|0.46848|0.47110|0.00055|0.12%|0.46952|-1.93%|0.46942|-1.93%|0.708|0.000|176373111|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/297179dbcc)|0.46226|0.47072|0.00090|0.19%|0.46870|-2.10%|0.46878|-2.06%|-3.621|0.000|176445103|44.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/297179dbcc)|0.45039|0.45584|0.00077|0.17%|0.45131|-5.73%|0.45117|-5.74%|3.666|0.000|147920342|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73536|0.75425|0.00205|0.28%|0.74443|0.00%|0.74419|0.00%|2.319|0.999|291621136|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3c5163c25)|0.73024|0.75157|0.00266|0.36%|0.74060|-0.52%|0.73994|-0.57%|1.561|0.000|290445235|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/297179dbcc)|0.73743|0.74727|0.00161|0.22%|0.73972|-0.63%|0.73940|-0.64%|1.864|0.000|290430744|40.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/297179dbcc)|0.71443|0.71790|0.00068|0.09%|0.71612|-3.80%|0.71600|-3.79%|0.279|0.000|270793505|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58167|0.59252|0.00161|0.28%|0.58370|0.00%|0.58315|0.00%|1.934|0.999|1123342397|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3c5163c25)|0.58089|0.58739|0.00152|0.26%|0.58288|-0.14%|0.58230|-0.15%|1.024|0.000|1119872128|44.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/297179dbcc)|0.58008|0.58719|0.00138|0.24%|0.58240|-0.22%|0.58202|-0.19%|0.714|0.000|1119607315|44.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/297179dbcc)|0.51720|0.52178|0.00117|0.23%|0.51909|-11.07%|0.51865|-11.06%|0.609|0.000|865659043|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42955|0.44421|0.00246|0.57%|0.43399|0.00%|0.43368|0.00%|1.032|0.999|2020638174|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3c5163c25)|0.42048|0.47858|0.00546|1.28%|0.42647|-1.73%|0.42572|-1.84%|8.951|0.000|2020586578|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/297179dbcc)|0.42294|0.43706|0.00285|0.67%|0.42596|-1.85%|0.42491|-2.02%|2.246|0.000|2020586637|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/297179dbcc)|0.14643|0.15111|0.00087|0.58%|0.14871|-65.73%|0.14862|-65.73%|0.417|0.000|536605550|27.74 MB|
