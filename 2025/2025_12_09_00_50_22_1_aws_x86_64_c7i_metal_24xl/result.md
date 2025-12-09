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
| Time          |2025-12-09 00:50:22 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47498|0.47763|0.00056|0.12%|0.47580|0.00%|0.47570|0.00%|1.016|0.999|180944831|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d4f1300011)|0.46377|0.47279|0.00148|0.31%|0.47049|-1.12%|0.47061|-1.07%|-3.161|0.000|176335859|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/9c81b52316)|0.46969|0.47680|0.00087|0.18%|0.47071|-1.07%|0.47053|-1.09%|3.813|0.000|176409492|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9c81b52316)|0.45000|0.45271|0.00047|0.10%|0.45083|-5.25%|0.45077|-5.24%|1.012|0.000|147896722|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74216|0.74636|0.00087|0.12%|0.74402|0.00%|0.74388|0.00%|0.607|0.999|291621108|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d4f1300011)|0.74404|0.75649|0.00182|0.24%|0.74632|0.31%|0.74579|0.26%|2.446|0.000|290397916|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/9c81b52316)|0.74396|0.75002|0.00126|0.17%|0.74603|0.27%|0.74573|0.25%|1.172|0.000|290399109|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9c81b52316)|0.70871|0.71998|0.00112|0.16%|0.71722|-3.60%|0.71732|-3.57%|-4.195|0.000|270761010|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57556|0.58860|0.00241|0.42%|0.57932|0.00%|0.57877|0.00%|0.537|0.999|1123344639|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d4f1300011)|0.57613|0.58750|0.00232|0.40%|0.57910|-0.04%|0.57800|-0.13%|0.581|0.321|1119624032|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/9c81b52316)|0.57595|0.58374|0.00224|0.39%|0.57904|-0.05%|0.57812|-0.11%|0.258|0.310|1119631446|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9c81b52316)|0.51314|0.51831|0.00157|0.30%|0.51569|-10.98%|0.51506|-11.01%|0.092|0.000|865683653|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42382|0.44369|0.00380|0.88%|0.43241|0.00%|0.43306|0.00%|-0.149|0.999|2020638207|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d4f1300011)|0.42248|0.43903|0.00322|0.75%|0.42712|-1.22%|0.42631|-1.56%|1.513|0.000|2020586614|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/9c81b52316)|0.42121|0.47946|0.00597|1.40%|0.42709|-1.23%|0.42645|-1.53%|6.987|0.000|2020586696|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9c81b52316)|0.13965|0.15293|0.00355|2.43%|0.14639|-66.15%|0.14798|-65.83%|-0.655|0.000|536605636|27.74 MB|
