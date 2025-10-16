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
| Time          |2025-10-16 00:50:10 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47246|0.48276|0.00103|0.22%|0.47706|0.00%|0.47684|0.00%|1.349|0.999|180946724|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e2da92b15c)|0.47053|0.47653|0.00089|0.19%|0.47178|-1.11%|0.47151|-1.12%|2.203|0.000|176334837|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/264d650117)|0.46530|0.47474|0.00094|0.20%|0.47185|-1.09%|0.47183|-1.05%|-2.859|0.000|176405793|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/264d650117)|0.45097|0.45472|0.00057|0.13%|0.45204|-5.24%|0.45201|-5.21%|1.393|0.000|147875739|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74049|0.75199|0.00161|0.22%|0.74199|0.00%|0.74180|0.00%|4.720|0.999|291621511|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e2da92b15c)|0.73773|0.74810|0.00135|0.18%|0.73942|-0.35%|0.73922|-0.35%|3.355|0.000|287322152|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/264d650117)|0.73639|0.74459|0.00126|0.17%|0.73965|-0.32%|0.73928|-0.34%|1.376|0.000|287318774|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/264d650117)|0.70886|0.71238|0.00071|0.10%|0.71076|-4.21%|0.71067|-4.20%|0.033|0.000|267681670|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57984|0.58524|0.00081|0.14%|0.58271|0.00%|0.58259|0.00%|0.178|0.999|1123344641|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e2da92b15c)|0.58377|0.58894|0.00083|0.14%|0.58575|0.52%|0.58574|0.54%|0.541|0.000|1120239867|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/264d650117)|0.58424|0.58802|0.00066|0.11%|0.58565|0.50%|0.58559|0.52%|0.819|0.000|1120247903|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/264d650117)|0.51752|0.52101|0.00063|0.12%|0.51935|-10.87%|0.51935|-10.85%|-0.033|0.000|866296942|61.49 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42974|0.44666|0.00229|0.53%|0.43339|0.00%|0.43321|0.00%|2.111|0.999|2020638198|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e2da92b15c)|0.43952|0.56263|0.02691|5.95%|0.45188|4.27%|0.44452|2.61%|3.439|0.000|2020595030|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/264d650117)|0.43584|0.59368|0.02864|6.41%|0.44701|3.14%|0.43973|1.51%|3.898|0.000|2020595074|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/264d650117)|0.14333|0.15144|0.00138|0.94%|0.14761|-65.94%|0.14750|-65.95%|0.267|0.000|536613191|27.68 MB|
