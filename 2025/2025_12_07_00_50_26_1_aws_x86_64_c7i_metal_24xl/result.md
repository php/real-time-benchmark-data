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
| Time          |2025-12-07 00:50:26 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47470|0.47785|0.00060|0.13%|0.47590|0.00%|0.47592|0.00%|0.740|0.999|180944683|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/824c389128)|0.46974|0.47445|0.00080|0.17%|0.47101|-1.03%|0.47089|-1.06%|1.888|0.000|176336888|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fb4e573ff)|0.46509|0.47497|0.00105|0.22%|0.47077|-1.08%|0.47075|-1.09%|-1.604|0.000|176405760|44.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fb4e573ff)|0.45021|0.45528|0.00057|0.13%|0.45125|-5.18%|0.45122|-5.19%|3.698|0.000|147895931|53.41 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74213|0.74516|0.00067|0.09%|0.74334|0.00%|0.74329|0.00%|0.479|0.999|291621103|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/824c389128)|0.74324|0.75496|0.00193|0.26%|0.74553|0.30%|0.74505|0.24%|2.799|0.000|290397884|40.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fb4e573ff)|0.74360|0.75524|0.00188|0.25%|0.74555|0.30%|0.74504|0.23%|3.095|0.000|290398845|40.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fb4e573ff)|0.70827|0.72059|0.00152|0.21%|0.71657|-3.60%|0.71619|-3.65%|-0.889|0.000|270757669|47.87 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58033|0.58587|0.00083|0.14%|0.58164|0.00%|0.58147|0.00%|1.688|0.999|1123346611|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/824c389128)|0.58062|0.58396|0.00061|0.11%|0.58168|0.01%|0.58157|0.02%|0.865|0.291|1119622050|44.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fb4e573ff)|0.58045|0.59128|0.00120|0.21%|0.58183|0.03%|0.58164|0.03%|5.248|0.168|1119632106|44.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fb4e573ff)|0.51312|0.51943|0.00068|0.13%|0.51767|-11.00%|0.51763|-10.98%|-2.687|0.000|865684085|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43066|0.44041|0.00182|0.42%|0.43479|0.00%|0.43471|0.00%|0.450|0.999|2020638190|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/824c389128)|0.42376|0.44029|0.00309|0.72%|0.42790|-1.59%|0.42717|-1.73%|1.921|0.000|2020586702|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/1fb4e573ff)|0.42392|0.43917|0.00307|0.72%|0.42772|-1.63%|0.42687|-1.80%|1.774|0.000|2020586611|26.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1fb4e573ff)|0.14258|0.15113|0.00111|0.75%|0.14849|-65.85%|0.14842|-65.86%|-1.176|0.000|536605695|27.75 MB|
