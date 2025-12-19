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
| Time          |2025-12-19 00:50:20 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47471|0.48155|0.00081|0.17%|0.47600|0.00%|0.47586|0.00%|3.499|0.999|180942316|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95abeba749)|0.46556|0.47332|0.00099|0.21%|0.46932|-1.40%|0.46913|-1.41%|1.218|0.000|176332110|44.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/b6f786a7ca)|0.46784|0.47072|0.00060|0.13%|0.46907|-1.46%|0.46900|-1.44%|0.445|0.000|176405969|44.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b6f786a7ca)|0.44434|0.45291|0.00077|0.17%|0.44930|-5.61%|0.44925|-5.59%|-1.488|0.000|147895495|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74227|0.74678|0.00089|0.12%|0.74396|0.00%|0.74377|0.00%|0.630|0.999|291622010|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95abeba749)|0.74361|0.75515|0.00133|0.18%|0.74599|0.27%|0.74576|0.27%|3.609|0.000|290424356|40.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/b6f786a7ca)|0.73997|0.75177|0.00165|0.22%|0.74221|-0.23%|0.74168|-0.28%|2.571|0.000|290409708|40.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b6f786a7ca)|0.71559|0.71903|0.00078|0.11%|0.71722|-3.59%|0.71726|-3.56%|0.251|0.000|270766399|47.98 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58045|0.61581|0.00722|1.23%|0.58506|0.00%|0.58460|0.00%|3.643|0.999|1123345029|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95abeba749)|0.58167|0.61838|0.00741|1.26%|0.58638|0.23%|0.58564|0.18%|3.323|0.000|1119532601|44.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/b6f786a7ca)|0.57797|0.61471|0.00753|1.29%|0.58364|-0.24%|0.58288|-0.29%|3.181|0.000|1119535364|44.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b6f786a7ca)|0.51472|0.55257|0.00716|1.38%|0.51963|-11.18%|0.51930|-11.17%|3.421|0.000|865599917|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42935|0.44347|0.00207|0.48%|0.43450|0.00%|0.43451|0.00%|0.654|0.999|2020638155|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95abeba749)|0.42322|0.48080|0.00595|1.39%|0.42742|-1.63%|0.42622|-1.91%|7.541|0.000|2020586477|27.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/b6f786a7ca)|0.42262|0.43873|0.00300|0.70%|0.42766|-1.57%|0.42689|-1.75%|1.756|0.000|2020586672|27.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b6f786a7ca)|0.14445|0.15171|0.00142|0.97%|0.14718|-66.13%|0.14716|-66.13%|0.786|0.000|536605698|27.87 MB|
