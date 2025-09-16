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
| Time          |2025-09-16 00:50:08 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47521|0.47832|0.00058|0.12%|0.47636|0.00%|0.47626|0.00%|1.131|0.999|180945973|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6300a3065)|0.46684|0.47046|0.00057|0.12%|0.46774|-1.81%|0.46762|-1.81%|1.361|0.000|176304173|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/1644af21dd)|0.46782|0.47343|0.00090|0.19%|0.46920|-1.50%|0.46902|-1.52%|2.251|0.000|176380351|44.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1644af21dd)|0.44604|0.44953|0.00047|0.10%|0.44834|-5.88%|0.44835|-5.86%|-0.868|0.000|147811677|53.51 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73957|0.74325|0.00079|0.11%|0.74114|0.00%|0.74108|0.00%|0.531|0.999|291622844|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6300a3065)|0.73620|0.74438|0.00140|0.19%|0.73794|-0.43%|0.73756|-0.48%|1.840|0.000|287311930|40.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/1644af21dd)|0.73236|0.74376|0.00187|0.25%|0.73463|-0.88%|0.73417|-0.93%|2.447|0.000|287312334|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1644af21dd)|0.70576|0.70906|0.00067|0.10%|0.70703|-4.60%|0.70695|-4.61%|0.730|0.000|267664896|47.64 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57747|0.59235|0.00129|0.22%|0.58217|0.00%|0.58207|0.00%|4.591|0.999|1123345691|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6300a3065)|0.57967|0.58270|0.00059|0.10%|0.58111|-0.18%|0.58113|-0.16%|-0.082|0.000|1119767525|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/1644af21dd)|0.57865|0.58262|0.00068|0.12%|0.58034|-0.31%|0.58026|-0.31%|0.862|0.000|1119771999|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1644af21dd)|0.51316|0.51967|0.00072|0.14%|0.51738|-11.13%|0.51729|-11.13%|-1.428|0.000|865856800|61.62 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42928|0.43738|0.00172|0.40%|0.43308|0.00%|0.43311|0.00%|0.186|0.999|2020638211|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6300a3065)|0.42469|0.55830|0.02399|5.54%|0.43324|0.04%|0.42823|-1.13%|4.753|0.000|2020644948|27.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/1644af21dd)|0.42374|0.55790|0.02657|6.12%|0.43403|0.22%|0.42788|-1.21%|4.176|0.000|2020645052|27.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1644af21dd)|0.14575|0.15142|0.00133|0.90%|0.14779|-65.87%|0.14774|-65.89%|0.714|0.000|536613094|27.92 MB|
