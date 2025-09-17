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
| Time          |2025-09-17 00:50:01 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47580|0.48428|0.00086|0.18%|0.47862|0.00%|0.47858|0.00%|2.589|0.999|180950190|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1644af21dd)|0.47026|0.47288|0.00051|0.11%|0.47143|-1.50%|0.47136|-1.51%|0.547|0.000|176312024|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ac68e7b07)|0.46893|0.47210|0.00060|0.13%|0.47057|-1.68%|0.47053|-1.68%|0.298|0.000|176386067|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ac68e7b07)|0.45028|0.45562|0.00069|0.15%|0.45145|-5.68%|0.45137|-5.69%|2.552|0.000|147821955|53.50 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74263|0.74704|0.00087|0.12%|0.74457|0.00%|0.74436|0.00%|0.712|0.999|291626093|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1644af21dd)|0.73605|0.74814|0.00132|0.18%|0.73840|-0.83%|0.73813|-0.84%|4.156|0.000|287316930|40.74 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ac68e7b07)|0.73607|0.74430|0.00143|0.19%|0.73784|-0.90%|0.73745|-0.93%|2.179|0.000|287312070|40.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ac68e7b07)|0.70532|0.71307|0.00098|0.14%|0.71080|-4.54%|0.71073|-4.52%|-1.366|0.000|267664401|47.63 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58125|0.58619|0.00083|0.14%|0.58289|0.00%|0.58278|0.00%|0.916|0.999|1123338212|43.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1644af21dd)|0.57932|0.58328|0.00076|0.13%|0.58083|-0.35%|0.58075|-0.35%|0.719|0.000|1119754732|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ac68e7b07)|0.57855|0.58214|0.00064|0.11%|0.58022|-0.46%|0.58019|-0.44%|0.411|0.000|1119752202|44.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ac68e7b07)|0.51404|0.51912|0.00068|0.13%|0.51694|-11.31%|0.51687|-11.31%|0.072|0.000|865840953|61.61 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43008|0.43894|0.00188|0.43%|0.43361|0.00%|0.43337|0.00%|0.447|0.999|2020638191|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1644af21dd)|0.42381|0.54659|0.02575|5.91%|0.43577|0.50%|0.42961|-0.87%|3.746|0.000|2020644991|27.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ac68e7b07)|0.42411|0.59145|0.03650|8.29%|0.44040|1.57%|0.42932|-0.93%|3.038|0.000|2020644969|27.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ac68e7b07)|0.14538|0.15051|0.00116|0.79%|0.14754|-65.97%|0.14741|-65.99%|0.529|0.000|536613035|27.91 MB|
