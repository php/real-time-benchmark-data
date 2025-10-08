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
| Time          |2025-10-08 00:49:53 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47610|0.47926|0.00063|0.13%|0.47743|0.00%|0.47741|0.00%|0.249|0.999|180947627|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c39c880824)|0.46884|0.47517|0.00088|0.19%|0.47050|-1.45%|0.47049|-1.45%|1.644|0.000|176400815|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/f905950ba5)|0.46957|0.47257|0.00069|0.15%|0.47059|-1.43%|0.47047|-1.45%|0.713|0.000|176397849|44.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f905950ba5)|0.45046|0.45395|0.00072|0.16%|0.45197|-5.33%|0.45193|-5.34%|0.199|0.000|147884987|53.45 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74088|0.75402|0.00238|0.32%|0.74339|0.00%|0.74294|0.00%|3.554|0.999|291624104|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c39c880824)|0.73682|0.74807|0.00171|0.23%|0.73966|-0.50%|0.73917|-0.51%|1.833|0.000|287354012|40.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/f905950ba5)|0.73589|0.74156|0.00124|0.17%|0.73820|-0.70%|0.73796|-0.67%|0.658|0.000|287355534|40.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f905950ba5)|0.70082|0.71381|0.00135|0.19%|0.71052|-4.42%|0.71046|-4.37%|-3.332|0.000|267715343|47.84 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57994|0.59114|0.00177|0.30%|0.58238|0.00%|0.58200|0.00%|1.984|0.999|1123345155|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c39c880824)|0.58262|0.59074|0.00172|0.29%|0.58480|0.42%|0.58437|0.41%|1.469|0.000|1120255408|44.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/f905950ba5)|0.58068|0.58857|0.00171|0.29%|0.58300|0.11%|0.58260|0.10%|1.148|0.001|1120255777|44.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f905950ba5)|0.51593|0.52236|0.00136|0.26%|0.51849|-10.97%|0.51832|-10.94%|1.228|0.000|866314170|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42902|0.44369|0.00202|0.47%|0.43344|0.00%|0.43338|0.00%|1.392|0.999|2020638162|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c39c880824)|0.43159|0.53726|0.01309|2.98%|0.43980|1.47%|0.43773|1.00%|6.816|0.000|2020595020|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/f905950ba5)|0.43478|0.53539|0.02082|4.70%|0.44336|2.29%|0.43819|1.11%|4.107|0.000|2020595038|27.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f905950ba5)|0.14479|0.15129|0.00130|0.88%|0.14784|-65.89%|0.14777|-65.90%|0.430|0.000|536613123|27.80 MB|
