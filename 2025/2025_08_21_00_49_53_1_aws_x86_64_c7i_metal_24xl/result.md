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
| GCC           |11.5.0|
| Time          |2025-08-21 00:49:53 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46458|0.47459|0.00321|0.68%|0.46932|0.00%|0.47138|0.00%|1.000|181826391|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1cff1815d0)|0.46116|0.47281|0.00309|0.66%|0.46540|-0.84%|0.46732|-0.86%|0.001|177217064|43.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/0bf295944d)|0.46018|0.46853|0.00315|0.68%|0.46474|-0.98%|0.46684|-0.96%|0.001|177211891|43.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0bf295944d)|0.44437|0.45296|0.00321|0.72%|0.44909|-4.31%|0.45125|-4.27%|0.001|149596698|53.79 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74198|0.74579|0.00078|0.10%|0.74332|0.00%|0.74315|0.00%|1.000|292385300|39.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1cff1815d0)|0.72286|0.74219|0.00220|0.30%|0.73253|-1.45%|0.73206|-1.49%|0.001|288323752|40.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/0bf295944d)|0.73366|0.74621|0.00260|0.35%|0.73622|-0.95%|0.73553|-1.03%|0.001|288310120|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0bf295944d)|0.70114|0.70597|0.00086|0.12%|0.70222|-5.53%|0.70207|-5.53%|0.001|267474939|48.06 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58263|0.58630|0.00071|0.12%|0.58377|0.00%|0.58364|0.00%|1.000|1133179561|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1cff1815d0)|0.57923|0.58221|0.00061|0.10%|0.58029|-0.60%|0.58021|-0.59%|0.001|1129317943|43.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/0bf295944d)|0.57919|0.58343|0.00074|0.13%|0.58074|-0.52%|0.58061|-0.52%|0.001|1129324570|43.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0bf295944d)|0.51527|0.51751|0.00050|0.10%|0.51624|-11.57%|0.51621|-11.55%|0.001|867867564|61.47 MB|

### bench.php - 100 consecutive runs, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42750|0.44002|0.00185|0.43%|0.43144|0.00%|0.43133|0.00%|1.000|2031002271|26.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1cff1815d0)|0.43476|0.58840|0.02672|6.02%|0.44354|2.80%|0.43735|1.40%|0.001|2031543289|26.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/0bf295944d)|0.43480|0.56234|0.03338|7.44%|0.44851|3.96%|0.43744|1.42%|0.001|2031543221|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0bf295944d)|0.14595|0.15152|0.00117|0.79%|0.14807|-65.68%|0.14796|-65.70%|0.001|537062327|27.90 MB|
