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
| Time          |2025-10-06 00:49:58 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46952|0.47896|0.00097|0.20%|0.47663|0.00%|0.47662|0.00%|-3.726|0.999|180948595|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c577c22c7)|0.46604|0.47306|0.00095|0.20%|0.46971|-1.45%|0.46956|-1.48%|0.764|0.000|176328084|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/c39c880824)|0.46794|0.47142|0.00078|0.17%|0.46929|-1.54%|0.46912|-1.57%|0.762|0.000|176401395|44.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c39c880824)|0.44871|0.45261|0.00066|0.15%|0.44990|-5.61%|0.44979|-5.63%|1.293|0.000|147884212|53.45 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74026|0.75328|0.00147|0.20%|0.74234|0.00%|0.74217|0.00%|4.256|0.999|291620717|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c577c22c7)|0.73512|0.74059|0.00103|0.14%|0.73754|-0.65%|0.73746|-0.64%|0.621|0.000|287354304|40.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/c39c880824)|0.73551|0.74772|0.00163|0.22%|0.73750|-0.65%|0.73714|-0.68%|3.064|0.000|287353982|40.57 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c39c880824)|0.70869|0.71428|0.00101|0.14%|0.71067|-4.27%|0.71051|-4.27%|0.777|0.000|267713604|47.85 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58051|0.59235|0.00125|0.22%|0.58236|0.00%|0.58219|0.00%|5.315|0.999|1123342248|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c577c22c7)|0.58281|0.58673|0.00076|0.13%|0.58431|0.33%|0.58422|0.35%|0.986|0.000|1120248120|44.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/c39c880824)|0.58295|0.58700|0.00087|0.15%|0.58432|0.34%|0.58414|0.34%|0.993|0.000|1120252474|44.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c39c880824)|0.51677|0.51900|0.00049|0.09%|0.51772|-11.10%|0.51767|-11.08%|0.316|0.000|866311006|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42509|0.44204|0.00244|0.56%|0.43366|0.00%|0.43329|0.00%|0.516|0.999|2020638147|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0c577c22c7)|0.43480|0.53668|0.01994|4.51%|0.44248|2.03%|0.43766|1.01%|4.153|0.000|2020595137|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/c39c880824)|0.43426|0.59519|0.02379|5.37%|0.44274|2.09%|0.43785|1.05%|5.028|0.000|2020594958|27.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c39c880824)|0.14418|0.15029|0.00126|0.86%|0.14731|-66.03%|0.14736|-65.99%|0.103|0.000|536613125|27.81 MB|
