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
| Time          |2025-12-05 00:50:17 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47474|0.47735|0.00055|0.12%|0.47574|0.00%|0.47567|0.00%|0.680|0.999|180945883|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/114260bdc4)|0.46332|0.46956|0.00072|0.15%|0.46771|-1.69%|0.46772|-1.67%|-1.941|0.000|176334139|44.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/4cc5f02387)|0.46433|0.47570|0.00116|0.25%|0.47062|-1.08%|0.47051|-1.09%|-0.149|0.000|176404762|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4cc5f02387)|0.44952|0.45264|0.00053|0.12%|0.45058|-5.29%|0.45047|-5.30%|1.069|0.000|147898003|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73409|0.75350|0.00154|0.21%|0.74308|0.00%|0.74295|0.00%|1.220|0.999|291621105|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/114260bdc4)|0.73967|0.74801|0.00135|0.18%|0.74150|-0.21%|0.74142|-0.21%|2.309|0.000|290397886|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/4cc5f02387)|0.74268|0.75059|0.00146|0.20%|0.74496|0.25%|0.74451|0.21%|1.523|0.000|290399033|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4cc5f02387)|0.71524|0.71866|0.00074|0.10%|0.71654|-3.57%|0.71645|-3.57%|0.564|0.000|270761010|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57504|0.58265|0.00206|0.36%|0.57878|0.00%|0.57786|0.00%|0.170|0.999|1123344479|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/114260bdc4)|0.57455|0.58754|0.00241|0.42%|0.57762|-0.20%|0.57655|-0.23%|0.868|0.000|1119622103|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/4cc5f02387)|0.57473|0.58228|0.00216|0.37%|0.57850|-0.05%|0.57778|-0.01%|0.253|0.114|1119630356|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4cc5f02387)|0.51308|0.51800|0.00137|0.27%|0.51516|-10.99%|0.51469|-10.93%|0.253|0.000|865684232|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42475|0.43918|0.00398|0.92%|0.43224|0.00%|0.43339|0.00%|-0.373|0.999|2020638187|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/114260bdc4)|0.42067|0.43698|0.00292|0.69%|0.42629|-1.38%|0.42589|-1.73%|1.389|0.000|2020586629|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/4cc5f02387)|0.42120|0.43998|0.00309|0.72%|0.42654|-1.32%|0.42614|-1.67%|1.519|0.000|2020586601|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4cc5f02387)|0.13979|0.15133|0.00348|2.38%|0.14634|-66.14%|0.14782|-65.89%|-0.669|0.000|536605685|27.74 MB|
