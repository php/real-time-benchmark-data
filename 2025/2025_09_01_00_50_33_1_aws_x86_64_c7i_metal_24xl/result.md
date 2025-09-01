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
| Time          |2025-09-01 00:50:33 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47302|0.47781|0.00073|0.15%|0.47459|0.00%|0.47443|0.00%|1.241|0.999|181229803|43.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a086e4e73)|0.46776|0.47066|0.00054|0.12%|0.46873|-1.23%|0.46869|-1.21%|0.817|0.000|176637011|44.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca4a841921)|0.46831|0.47049|0.00048|0.10%|0.46912|-1.15%|0.46910|-1.12%|0.329|0.000|176634342|44.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca4a841921)|0.45421|0.45767|0.00050|0.11%|0.45507|-4.11%|0.45498|-4.10%|1.548|0.000|149308238|53.92 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74256|0.74874|0.00113|0.15%|0.74418|0.00%|0.74402|0.00%|1.185|0.999|291550458|39.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a086e4e73)|0.72755|0.75241|0.00263|0.36%|0.73845|-0.77%|0.73792|-0.82%|1.643|0.000|287306714|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca4a841921)|0.73253|0.74957|0.00251|0.34%|0.73534|-1.19%|0.73488|-1.23%|3.233|0.000|287291293|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca4a841921)|0.70448|0.71282|0.00134|0.19%|0.70629|-5.09%|0.70594|-5.12%|1.957|0.000|267594835|47.53 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57986|0.58390|0.00074|0.13%|0.58098|0.00%|0.58083|0.00%|1.385|0.999|1123004574|43.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a086e4e73)|0.57830|0.58385|0.00072|0.12%|0.58206|0.19%|0.58202|0.20%|-1.034|0.000|1119164566|43.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca4a841921)|0.58096|0.58439|0.00065|0.11%|0.58229|0.23%|0.58220|0.24%|0.442|0.000|1119158513|43.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca4a841921)|0.51845|0.52052|0.00049|0.09%|0.51931|-10.62%|0.51926|-10.60%|0.275|0.000|865516626|61.43 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42884|0.43558|0.00138|0.32%|0.43124|0.00%|0.43100|0.00%|0.672|0.999|2020733084|26.37 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a086e4e73)|0.42255|0.54833|0.01891|4.41%|0.42892|-0.54%|0.42545|-1.29%|5.628|0.000|2020744432|26.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca4a841921)|0.42314|0.58476|0.03514|8.05%|0.43644|1.21%|0.42550|-1.28%|2.992|0.000|2020744471|27.04 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca4a841921)|0.14589|0.15188|0.00118|0.80%|0.14830|-65.61%|0.14814|-65.63%|0.541|0.000|536712462|28.05 MB|
