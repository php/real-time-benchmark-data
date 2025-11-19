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
| Time          |2025-11-19 00:50:19 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47454|0.47753|0.00054|0.11%|0.47566|0.00%|0.47555|0.00%|0.686|0.999|180943900|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d750d30a62)|0.46713|0.47184|0.00106|0.23%|0.46858|-1.49%|0.46820|-1.55%|1.661|0.000|176333430|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/9762c446f0)|0.46643|0.47214|0.00071|0.15%|0.46753|-1.71%|0.46743|-1.71%|3.145|0.000|176406029|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9762c446f0)|0.44827|0.45036|0.00048|0.11%|0.44908|-5.59%|0.44897|-5.59%|0.700|0.000|147884866|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74192|0.74530|0.00075|0.10%|0.74315|0.00%|0.74302|0.00%|0.640|0.999|291621929|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d750d30a62)|0.73961|0.75044|0.00140|0.19%|0.74145|-0.23%|0.74126|-0.24%|3.044|0.000|290398583|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/9762c446f0)|0.74078|0.75200|0.00195|0.26%|0.74281|-0.05%|0.74233|-0.09%|2.718|0.000|290399697|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9762c446f0)|0.71159|0.71732|0.00094|0.13%|0.71316|-4.04%|0.71293|-4.05%|1.394|0.000|270758365|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57984|0.59115|0.00156|0.27%|0.58133|0.00%|0.58101|0.00%|4.938|0.999|1123344467|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d750d30a62)|0.57872|0.58274|0.00074|0.13%|0.58061|-0.12%|0.58050|-0.09%|0.559|0.000|1119620949|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/9762c446f0)|0.57795|0.58967|0.00125|0.22%|0.57991|-0.24%|0.57970|-0.23%|5.079|0.000|1119630528|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9762c446f0)|0.51279|0.51799|0.00064|0.12%|0.51582|-11.27%|0.51577|-11.23%|-0.686|0.000|865682454|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42914|0.44979|0.00256|0.59%|0.43468|0.00%|0.43467|0.00%|2.130|0.999|2020638166|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d750d30a62)|0.42457|0.47857|0.00600|1.40%|0.42839|-1.45%|0.42692|-1.78%|6.300|0.000|2020586699|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/9762c446f0)|0.42430|0.43622|0.00225|0.53%|0.42738|-1.68%|0.42693|-1.78%|2.005|0.000|2020586669|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9762c446f0)|0.14636|0.15079|0.00100|0.67%|0.14847|-65.84%|0.14850|-65.83%|0.067|0.000|536605621|27.74 MB|
