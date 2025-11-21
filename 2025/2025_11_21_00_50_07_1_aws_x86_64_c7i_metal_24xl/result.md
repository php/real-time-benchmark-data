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
| Time          |2025-11-21 00:50:07 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47672|0.48371|0.00087|0.18%|0.47779|0.00%|0.47766|0.00%|3.449|0.999|180943566|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d40ae97f52)|0.46563|0.47481|0.00097|0.21%|0.47152|-1.31%|0.47140|-1.31%|-1.342|0.000|176336005|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca7f556002)|0.46419|0.47351|0.00093|0.20%|0.47071|-1.48%|0.47069|-1.46%|-3.043|0.000|176403986|44.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca7f556002)|0.44765|0.45222|0.00054|0.12%|0.45072|-5.66%|0.45071|-5.64%|-1.589|0.000|147890103|53.41 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74449|0.74803|0.00071|0.09%|0.74611|0.00%|0.74605|0.00%|0.140|0.999|291622010|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d40ae97f52)|0.74220|0.75198|0.00147|0.20%|0.74407|-0.27%|0.74377|-0.31%|2.960|0.000|290398581|40.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca7f556002)|0.74126|0.75287|0.00180|0.24%|0.74330|-0.38%|0.74276|-0.44%|2.879|0.000|290399437|40.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca7f556002)|0.71156|0.72340|0.00118|0.16%|0.71936|-3.58%|0.71934|-3.58%|-2.341|0.000|270761691|47.88 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58021|0.59110|0.00145|0.25%|0.58178|0.00%|0.58148|0.00%|5.121|0.999|1123344161|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d40ae97f52)|0.58037|0.58652|0.00093|0.16%|0.58174|-0.01%|0.58147|-0.00%|2.454|0.753|1119623808|44.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca7f556002)|0.57997|0.58500|0.00073|0.13%|0.58137|-0.07%|0.58136|-0.02%|1.355|0.008|1119631980|44.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca7f556002)|0.51358|0.51841|0.00061|0.12%|0.51695|-11.14%|0.51692|-11.10%|-1.347|0.000|865682773|61.52 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42506|0.44783|0.00296|0.68%|0.43445|0.00%|0.43420|0.00%|0.930|0.999|2020638119|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d40ae97f52)|0.42507|0.44138|0.00277|0.65%|0.42802|-1.48%|0.42739|-1.57%|2.888|0.000|2020586640|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca7f556002)|0.42253|0.43741|0.00255|0.60%|0.42666|-1.79%|0.42616|-1.85%|2.312|0.000|2020586667|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca7f556002)|0.14676|0.15104|0.00095|0.64%|0.14876|-65.76%|0.14872|-65.75%|0.101|0.000|536605632|27.82 MB|
