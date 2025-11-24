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
| Time          |2025-11-24 00:50:15 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47456|0.47745|0.00054|0.11%|0.47567|0.00%|0.47555|0.00%|1.026|0.999|180943168|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56dd321ec7)|0.46774|0.47152|0.00066|0.14%|0.46870|-1.47%|0.46856|-1.47%|1.762|0.000|176337156|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca914ee389)|0.46442|0.46882|0.00065|0.14%|0.46716|-1.79%|0.46710|-1.78%|-0.243|0.000|176405604|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca914ee389)|0.44742|0.45159|0.00055|0.12%|0.44818|-5.78%|0.44810|-5.77%|2.658|0.000|147890996|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74303|0.74688|0.00079|0.11%|0.74452|0.00%|0.74441|0.00%|0.753|0.999|291622022|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56dd321ec7)|0.73830|0.74521|0.00098|0.13%|0.74241|-0.28%|0.74237|-0.27%|-0.304|0.000|290402179|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca914ee389)|0.73594|0.74500|0.00140|0.19%|0.73792|-0.89%|0.73765|-0.91%|2.040|0.000|290399587|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca914ee389)|0.71417|0.71859|0.00072|0.10%|0.71553|-3.89%|0.71545|-3.89%|1.256|0.000|270761852|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57991|0.64399|0.00630|1.08%|0.58195|0.00%|0.58125|0.00%|9.847|0.999|1123349943|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56dd321ec7)|0.57958|0.64126|0.00774|1.33%|0.58205|0.02%|0.58078|-0.08%|6.716|0.000|1119626705|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca914ee389)|0.57863|0.64060|0.00714|1.23%|0.58130|-0.11%|0.58012|-0.19%|7.236|0.000|1119635294|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca914ee389)|0.51635|0.58324|0.00660|1.27%|0.51804|-10.98%|0.51733|-11.00%|9.916|0.000|865685386|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42949|0.43991|0.00208|0.48%|0.43468|0.00%|0.43478|0.00%|0.177|0.999|2020638187|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/56dd321ec7)|0.42448|0.47952|0.00597|1.39%|0.42882|-1.35%|0.42723|-1.73%|6.469|0.000|2020586685|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/ca914ee389)|0.42348|0.48015|0.00581|1.36%|0.42704|-1.76%|0.42616|-1.98%|7.984|0.000|2020586668|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ca914ee389)|0.14619|0.15234|0.00114|0.77%|0.14885|-65.76%|0.14865|-65.81%|0.479|0.000|536605596|27.81 MB|
