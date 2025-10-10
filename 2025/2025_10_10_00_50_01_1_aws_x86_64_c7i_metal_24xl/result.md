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
| Time          |2025-10-10 00:50:01 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47062|0.47992|0.00094|0.20%|0.47719|0.00%|0.47720|0.00%|-3.115|0.999|180947174|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/baa5319632)|0.46954|0.47477|0.00073|0.16%|0.47077|-1.35%|0.47066|-1.37%|1.809|0.000|176328684|44.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/02e38fe22e)|0.47003|0.47348|0.00068|0.14%|0.47150|-1.19%|0.47143|-1.21%|0.676|0.000|176398073|44.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02e38fe22e)|0.44342|0.45218|0.00098|0.22%|0.45018|-5.66%|0.45017|-5.66%|-3.032|0.000|147886242|53.46 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74156|0.75301|0.00129|0.17%|0.74316|0.00%|0.74299|0.00%|4.674|0.999|291621500|40.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/baa5319632)|0.73390|0.74661|0.00225|0.31%|0.73641|-0.91%|0.73591|-0.95%|3.153|0.000|287322170|40.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/02e38fe22e)|0.73581|0.74840|0.00182|0.25%|0.73824|-0.66%|0.73785|-0.69%|3.137|0.000|287318683|40.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02e38fe22e)|0.70201|0.71273|0.00107|0.15%|0.70986|-4.48%|0.70998|-4.44%|-3.847|0.000|267681795|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58086|0.59254|0.00133|0.23%|0.58247|0.00%|0.58231|0.00%|4.723|0.999|1123345327|43.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/baa5319632)|0.58039|0.58428|0.00070|0.12%|0.58189|-0.10%|0.58178|-0.09%|1.062|0.000|1120200498|44.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/02e38fe22e)|0.58169|0.58508|0.00064|0.11%|0.58303|0.10%|0.58297|0.11%|0.733|0.000|1120208154|44.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02e38fe22e)|0.51705|0.52041|0.00056|0.11%|0.51844|-10.99%|0.51840|-10.97%|0.510|0.000|866267651|61.57 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42975|0.43921|0.00205|0.47%|0.43334|0.00%|0.43291|0.00%|0.706|0.999|2020638214|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/baa5319632)|0.43717|0.55540|0.02954|6.54%|0.45145|4.18%|0.44229|2.17%|2.900|0.000|2020594988|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/02e38fe22e)|0.43591|0.59133|0.02767|6.17%|0.44859|3.52%|0.44064|1.78%|3.437|0.000|2020595002|27.04 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/02e38fe22e)|0.14516|0.15100|0.00132|0.90%|0.14731|-66.01%|0.14712|-66.02%|0.714|0.000|536613052|27.82 MB|
