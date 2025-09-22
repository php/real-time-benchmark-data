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
| Time          |2025-09-22 00:50:19 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47508|0.48039|0.00075|0.16%|0.47829|0.00%|0.47823|0.00%|-0.234|0.999|180949461|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb49281739)|0.46924|0.47747|0.00100|0.21%|0.47041|-1.65%|0.47025|-1.67%|4.088|0.000|176273601|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/4bc060c0f3)|0.46989|0.47278|0.00054|0.11%|0.47096|-1.53%|0.47085|-1.54%|1.040|0.000|176348195|44.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4bc060c0f3)|0.44965|0.45385|0.00063|0.14%|0.45063|-5.78%|0.45059|-5.78%|2.604|0.000|147801909|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74216|0.75433|0.00131|0.18%|0.74378|0.00%|0.74345|0.00%|5.417|0.999|291626070|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb49281739)|0.73887|0.75166|0.00197|0.27%|0.74068|-0.42%|0.74028|-0.43%|4.219|0.000|287307120|40.74 MB|
|[PHP - master](https://github.com/php/php-src/commit/4bc060c0f3)|0.73728|0.74581|0.00135|0.18%|0.73920|-0.62%|0.73887|-0.62%|2.691|0.000|287317623|40.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4bc060c0f3)|0.70736|0.71359|0.00089|0.12%|0.71103|-4.40%|0.71100|-4.36%|-0.244|0.000|267645416|47.57 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58101|0.59347|0.00131|0.22%|0.58250|0.00%|0.58229|0.00%|6.128|0.999|1123338385|43.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb49281739)|0.58516|0.58965|0.00075|0.13%|0.58680|0.74%|0.58677|0.77%|0.682|0.000|1119765005|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/4bc060c0f3)|0.57725|0.58371|0.00086|0.15%|0.58089|-0.28%|0.58074|-0.27%|0.227|0.000|1119764908|44.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4bc060c0f3)|0.51717|0.52008|0.00057|0.11%|0.51851|-10.98%|0.51851|-10.95%|0.214|0.000|865938440|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43018|0.44164|0.00223|0.51%|0.43376|0.00%|0.43353|0.00%|1.106|0.999|2020638232|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb49281739)|0.42689|0.54796|0.02223|5.11%|0.43503|0.29%|0.43042|-0.72%|4.730|0.000|2020644950|27.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/4bc060c0f3)|0.42470|0.58692|0.02840|6.54%|0.43442|0.15%|0.42802|-1.27%|4.299|0.000|2020644931|26.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4bc060c0f3)|0.14556|0.15044|0.00112|0.76%|0.14748|-66.00%|0.14725|-66.04%|0.432|0.000|536613078|27.79 MB|
