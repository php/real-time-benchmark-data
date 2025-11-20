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
| Time          |2025-11-20 00:50:05 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47119|0.47735|0.00072|0.15%|0.47535|0.00%|0.47530|0.00%|-1.559|0.999|180942111|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9762c446f0)|0.46612|0.47254|0.00097|0.21%|0.46751|-1.65%|0.46730|-1.68%|2.370|0.000|176334024|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/d40ae97f52)|0.46275|0.47349|0.00107|0.23%|0.46930|-1.27%|0.46919|-1.29%|-0.887|0.000|176404992|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d40ae97f52)|0.44792|0.44995|0.00040|0.09%|0.44871|-5.60%|0.44870|-5.60%|0.376|0.000|147883467|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74207|0.74509|0.00069|0.09%|0.74338|0.00%|0.74339|0.00%|0.286|0.999|291621935|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9762c446f0)|0.74117|0.74781|0.00135|0.18%|0.74308|-0.04%|0.74269|-0.09%|1.679|0.000|290398580|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/d40ae97f52)|0.73886|0.74949|0.00208|0.28%|0.74138|-0.27%|0.74073|-0.36%|2.042|0.000|290399470|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d40ae97f52)|0.71311|0.71648|0.00067|0.09%|0.71469|-3.86%|0.71464|-3.87%|0.355|0.000|270762125|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57960|0.58323|0.00070|0.12%|0.58105|0.00%|0.58100|0.00%|0.568|0.999|1123345128|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9762c446f0)|0.57837|0.58192|0.00068|0.12%|0.57968|-0.24%|0.57956|-0.25%|1.217|0.000|1119620355|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/d40ae97f52)|0.57957|0.59105|0.00152|0.26%|0.58104|-0.00%|0.58082|-0.03%|5.168|0.051|1119631815|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d40ae97f52)|0.51498|0.51881|0.00058|0.11%|0.51639|-11.13%|0.51645|-11.11%|0.297|0.000|865682793|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43020|0.44787|0.00222|0.51%|0.43405|0.00%|0.43390|0.00%|2.462|0.999|2020638165|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9762c446f0)|0.42476|0.43788|0.00315|0.74%|0.42808|-1.37%|0.42692|-1.61%|1.676|0.000|2020586590|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/d40ae97f52)|0.42381|0.43886|0.00290|0.68%|0.42691|-1.65%|0.42619|-1.78%|2.529|0.000|2020586697|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d40ae97f52)|0.14642|0.15144|0.00111|0.75%|0.14884|-65.71%|0.14880|-65.71%|0.204|0.000|536605648|27.80 MB|
