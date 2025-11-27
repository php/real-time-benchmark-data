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
| Time          |2025-11-27 00:50:06 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47476|0.47821|0.00060|0.13%|0.47596|0.00%|0.47586|0.00%|1.056|0.999|180944120|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.46786|0.47383|0.00090|0.19%|0.46893|-1.48%|0.46878|-1.49%|3.087|0.000|176335368|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/ada7400690)|0.46787|0.47477|0.00097|0.21%|0.46901|-1.46%|0.46887|-1.47%|3.099|0.000|176404698|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ada7400690)|0.44638|0.45212|0.00057|0.13%|0.44985|-5.49%|0.44981|-5.48%|-1.501|0.000|147883541|53.40 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74331|0.75520|0.00135|0.18%|0.74472|0.00%|0.74444|0.00%|4.875|0.999|291621949|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.73945|0.75049|0.00135|0.18%|0.74094|-0.51%|0.74069|-0.50%|4.205|0.000|290398661|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/ada7400690)|0.73873|0.74621|0.00137|0.18%|0.74123|-0.47%|0.74098|-0.46%|1.389|0.000|290399552|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ada7400690)|0.71583|0.71934|0.00070|0.10%|0.71722|-3.69%|0.71720|-3.66%|0.631|0.000|270762168|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57588|0.58357|0.00118|0.20%|0.58046|0.00%|0.58062|0.00%|-1.987|0.999|1123345621|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.57529|0.58966|0.00182|0.31%|0.57961|-0.15%|0.57948|-0.20%|2.821|0.000|1119623253|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/ada7400690)|0.57485|0.58115|0.00117|0.20%|0.57938|-0.19%|0.57950|-0.19%|-2.159|0.000|1119634190|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ada7400690)|0.51319|0.51841|0.00086|0.17%|0.51642|-11.03%|0.51656|-11.03%|-1.926|0.000|865681972|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42438|0.43926|0.00411|0.96%|0.43019|0.00%|0.42840|0.00%|0.627|0.999|2020638193|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ee8dfd6fc)|0.42152|0.43572|0.00294|0.69%|0.42551|-1.09%|0.42491|-0.82%|1.105|0.000|2020586697|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/ada7400690)|0.42074|0.43855|0.00345|0.81%|0.42563|-1.06%|0.42480|-0.84%|1.868|0.000|2020586618|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ada7400690)|0.13921|0.15094|0.00379|2.63%|0.14428|-66.46%|0.14223|-66.80%|0.368|0.000|536605686|27.75 MB|
