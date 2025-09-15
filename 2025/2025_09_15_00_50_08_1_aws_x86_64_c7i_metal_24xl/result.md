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
| Time          |2025-09-15 00:50:08 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47541|0.48239|0.00099|0.21%|0.47658|0.00%|0.47637|0.00%|3.505|0.999|180945472|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e2c991767)|0.46941|0.47243|0.00050|0.11%|0.47058|-1.26%|0.47057|-1.22%|0.956|0.000|176309525|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6300a3065)|0.46129|0.46983|0.00083|0.18%|0.46783|-1.84%|0.46782|-1.80%|-4.617|0.000|176381740|44.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6300a3065)|0.44742|0.44935|0.00036|0.08%|0.44841|-5.91%|0.44839|-5.87%|0.294|0.000|147814040|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73965|0.74303|0.00079|0.11%|0.74098|0.00%|0.74084|0.00%|0.393|0.999|291622860|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e2c991767)|0.73588|0.74735|0.00185|0.25%|0.73849|-0.34%|0.73800|-0.38%|2.161|0.000|287345326|40.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6300a3065)|0.73570|0.74049|0.00093|0.13%|0.73726|-0.50%|0.73716|-0.50%|1.220|0.000|287312226|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6300a3065)|0.70601|0.70946|0.00072|0.10%|0.70753|-4.51%|0.70741|-4.51%|0.485|0.000|267664788|47.64 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58072|0.64667|0.00897|1.53%|0.58409|0.00%|0.58269|0.00%|6.796|0.999|1123402684|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e2c991767)|0.58392|0.64952|0.00870|1.48%|0.58671|0.45%|0.58535|0.46%|6.823|0.000|1121276220|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6300a3065)|0.58042|0.64632|0.00911|1.56%|0.58281|-0.22%|0.58140|-0.22%|6.913|0.000|1119830081|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6300a3065)|0.51824|0.58852|0.00971|1.86%|0.52132|-10.75%|0.51958|-10.83%|6.342|0.000|865047318|61.82 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43013|0.44463|0.00226|0.52%|0.43330|0.00%|0.43291|0.00%|1.692|0.999|2020638204|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0e2c991767)|0.42558|0.58374|0.03581|8.12%|0.44114|1.81%|0.42953|-0.78%|2.776|0.000|2020644999|27.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/d6300a3065)|0.42387|0.55800|0.03646|8.28%|0.44037|1.63%|0.42830|-1.07%|2.705|0.000|2020644937|27.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d6300a3065)|0.14506|0.15007|0.00113|0.76%|0.14770|-65.91%|0.14759|-65.91%|0.337|0.000|536613087|27.92 MB|
