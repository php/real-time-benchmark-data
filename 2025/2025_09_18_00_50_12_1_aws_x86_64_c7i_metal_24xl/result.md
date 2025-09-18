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
| Time          |2025-09-18 00:50:12 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47570|0.47856|0.00055|0.12%|0.47664|0.00%|0.47656|0.00%|1.052|0.999|180947578|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ac68e7b07)|0.46770|0.47103|0.00061|0.13%|0.46875|-1.66%|0.46861|-1.67%|1.438|0.000|176304445|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/c89359164b)|0.46237|0.46984|0.00079|0.17%|0.46808|-1.80%|0.46797|-1.80%|-3.426|0.000|176345081|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c89359164b)|0.44711|0.45206|0.00056|0.13%|0.44810|-5.99%|0.44806|-5.98%|3.526|0.000|147815552|53.50 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74098|0.74582|0.00083|0.11%|0.74262|0.00%|0.74254|0.00%|0.878|0.999|291622844|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ac68e7b07)|0.73440|0.74474|0.00181|0.25%|0.73669|-0.80%|0.73623|-0.85%|1.927|0.000|287311544|40.74 MB|
|[PHP - master](https://github.com/php/php-src/commit/c89359164b)|0.73325|0.74558|0.00158|0.21%|0.73565|-0.94%|0.73528|-0.98%|3.621|0.000|287304478|40.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c89359164b)|0.70062|0.71206|0.00111|0.16%|0.70886|-4.55%|0.70876|-4.55%|-3.645|0.000|267645813|47.63 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57663|0.59218|0.00134|0.23%|0.58222|0.00%|0.58204|0.00%|3.719|0.999|1123348291|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ac68e7b07)|0.57819|0.58215|0.00073|0.13%|0.57965|-0.44%|0.57956|-0.42%|1.042|0.000|1119761541|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/c89359164b)|0.58256|0.58516|0.00058|0.10%|0.58366|0.25%|0.58355|0.26%|0.501|0.000|1119785195|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c89359164b)|0.51572|0.51928|0.00060|0.12%|0.51794|-11.04%|0.51792|-11.02%|-0.309|0.000|865944152|61.61 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42957|0.44470|0.00222|0.51%|0.43347|0.00%|0.43316|0.00%|1.480|0.999|2020638127|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ac68e7b07)|0.42561|0.55330|0.02608|6.00%|0.43488|0.33%|0.42906|-0.95%|4.177|0.000|2020645003|27.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/c89359164b)|0.42506|0.58782|0.03614|8.19%|0.44111|1.76%|0.42939|-0.87%|2.805|0.000|2020644968|27.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c89359164b)|0.14463|0.15207|0.00128|0.87%|0.14792|-65.87%|0.14779|-65.88%|0.548|0.000|536613035|27.91 MB|
