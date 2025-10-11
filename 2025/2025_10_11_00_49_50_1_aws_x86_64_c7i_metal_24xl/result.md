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
| Time          |2025-10-11 00:49:50 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47475|0.48104|0.00076|0.16%|0.47585|0.00%|0.47576|0.00%|3.606|0.999|180944204|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02e38fe22e)|0.46857|0.47345|0.00092|0.20%|0.46985|-1.26%|0.46965|-1.28%|2.264|0.000|176401985|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/106079a462)|0.46864|0.47192|0.00062|0.13%|0.46976|-1.28%|0.46960|-1.29%|1.126|0.000|176395465|44.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/106079a462)|0.45038|0.45247|0.00043|0.09%|0.45108|-5.20%|0.45103|-5.20%|0.907|0.000|147883489|53.45 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73171|0.75014|0.00146|0.20%|0.73978|0.00%|0.73981|0.00%|1.932|0.999|291624822|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02e38fe22e)|0.73340|0.74411|0.00183|0.25%|0.73518|-0.62%|0.73472|-0.69%|3.106|0.000|287318690|40.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/106079a462)|0.73852|0.74403|0.00099|0.13%|0.74027|0.07%|0.74001|0.03%|1.549|0.001|287318800|40.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/106079a462)|0.70542|0.71088|0.00108|0.15%|0.70724|-4.40%|0.70696|-4.44%|1.181|0.000|267678465|47.84 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58074|0.58455|0.00072|0.12%|0.58205|0.00%|0.58203|0.00%|0.906|0.999|1123346055|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02e38fe22e)|0.58125|0.58554|0.00087|0.15%|0.58271|0.11%|0.58256|0.09%|0.989|0.000|1120200707|44.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/106079a462)|0.58243|0.58671|0.00083|0.14%|0.58392|0.32%|0.58375|0.30%|0.942|0.000|1120208488|44.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/106079a462)|0.51442|0.52052|0.00070|0.14%|0.51926|-10.79%|0.51926|-10.79%|-3.160|0.000|866267361|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43040|0.43893|0.00203|0.47%|0.43388|0.00%|0.43366|0.00%|0.381|0.999|2020638205|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/02e38fe22e)|0.43638|0.54132|0.01330|3.01%|0.44248|1.98%|0.44054|1.58%|6.759|0.000|2020595041|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/106079a462)|0.43715|0.54283|0.02327|5.22%|0.44578|2.74%|0.43951|1.35%|3.747|0.000|2020595116|27.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/106079a462)|0.14481|0.15140|0.00129|0.88%|0.14776|-65.94%|0.14765|-65.95%|0.352|0.000|536613108|27.80 MB|
