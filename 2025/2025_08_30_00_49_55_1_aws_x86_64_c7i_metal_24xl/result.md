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
| Time          |2025-08-30 00:49:55 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47484|0.47746|0.00051|0.11%|0.47592|0.00%|0.47590|0.00%|0.444|0.999|181231463|43.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/84b78c047e)|0.46939|0.47220|0.00050|0.11%|0.47034|-1.17%|0.47031|-1.18%|0.564|0.000|176641448|44.02 MB|
|[PHP - master](https://github.com/php/php-src/commit/914f9ad49b)|0.46893|0.47228|0.00052|0.11%|0.47088|-1.06%|0.47086|-1.06%|-0.087|0.000|176633947|44.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/914f9ad49b)|0.44822|0.45658|0.00083|0.18%|0.45510|-4.37%|0.45514|-4.36%|-5.726|0.000|149309906|53.94 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74068|0.75123|0.00113|0.15%|0.74670|0.00%|0.74666|0.00%|-0.648|0.999|291551370|39.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/84b78c047e)|0.73399|0.74548|0.00199|0.27%|0.73631|-1.39%|0.73586|-1.45%|2.306|0.000|287307912|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/914f9ad49b)|0.73793|0.75094|0.00209|0.28%|0.74076|-0.80%|0.74028|-0.85%|2.527|0.000|287312970|40.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/914f9ad49b)|0.71111|0.71899|0.00111|0.16%|0.71268|-4.56%|0.71243|-4.58%|2.561|0.000|267611095|47.54 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57851|0.64683|0.00656|1.13%|0.58233|0.00%|0.58169|0.00%|9.771|0.999|1122999461|43.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/84b78c047e)|0.58213|0.59506|0.00161|0.27%|0.58412|0.31%|0.58396|0.39%|5.383|0.000|1119167737|43.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/914f9ad49b)|0.58152|0.63871|0.00559|0.96%|0.58373|0.24%|0.58317|0.26%|9.824|0.000|1119167315|43.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/914f9ad49b)|0.51740|0.58564|0.00660|1.27%|0.52063|-10.60%|0.51996|-10.61%|9.864|0.000|865527331|61.44 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42868|0.43716|0.00142|0.33%|0.43122|0.00%|0.43111|0.00%|0.949|0.999|2020733048|26.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/84b78c047e)|0.42236|0.58467|0.02357|5.49%|0.42968|-0.36%|0.42560|-1.28%|5.718|0.000|2020744429|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/914f9ad49b)|0.42270|0.55302|0.03758|8.57%|0.43835|1.65%|0.42533|-1.34%|2.536|0.000|2020744433|27.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/914f9ad49b)|0.14519|0.15225|0.00132|0.89%|0.14814|-65.65%|0.14800|-65.67%|0.670|0.000|536712517|28.06 MB|
