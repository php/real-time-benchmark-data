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
| Time          |2025-12-11 00:50:25 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47020|0.48141|0.00097|0.20%|0.47572|0.00%|0.47563|0.00%|0.309|0.999|180944907|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c380f7e382)|0.46305|0.47225|0.00091|0.19%|0.46968|-1.27%|0.46970|-1.25%|-3.532|0.000|176406720|44.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/c27368c939)|0.46847|0.47193|0.00060|0.13%|0.46956|-1.29%|0.46948|-1.29%|1.007|0.000|176401047|44.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c27368c939)|0.45058|0.45289|0.00047|0.10%|0.45153|-5.08%|0.45143|-5.09%|0.830|0.000|147900928|53.41 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74199|0.75453|0.00172|0.23%|0.74371|0.00%|0.74343|0.00%|4.603|0.999|291625362|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c380f7e382)|0.74050|0.75450|0.00169|0.23%|0.74266|-0.14%|0.74233|-0.15%|3.815|0.000|290398980|40.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/c27368c939)|0.74246|0.75557|0.00201|0.27%|0.74483|0.15%|0.74426|0.11%|2.821|0.000|290399587|40.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c27368c939)|0.70926|0.71899|0.00106|0.15%|0.71604|-3.72%|0.71606|-3.68%|-2.143|0.000|270758493|47.88 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58029|0.64742|0.01746|2.98%|0.58648|0.00%|0.58130|0.00%|3.141|0.999|1123343861|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c380f7e382)|0.58101|0.64645|0.01638|2.79%|0.58744|0.16%|0.58249|0.20%|3.105|0.000|1119620181|44.11 MB|
|[PHP - master](https://github.com/php/php-src/commit/c27368c939)|0.58062|0.65602|0.01651|2.81%|0.58674|0.04%|0.58210|0.14%|3.429|0.000|1119628970|44.11 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c27368c939)|0.51699|0.58871|0.01698|3.25%|0.52310|-10.81%|0.51805|-10.88%|3.185|0.000|865682210|61.52 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43061|0.44777|0.00234|0.54%|0.43470|0.00%|0.43442|0.00%|1.695|0.999|2020638179|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c380f7e382)|0.42347|0.47949|0.00584|1.37%|0.42736|-1.69%|0.42622|-1.89%|7.482|0.000|2020586727|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/c27368c939)|0.42201|0.43735|0.00275|0.64%|0.42689|-1.80%|0.42614|-1.91%|1.707|0.000|2020586730|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c27368c939)|0.14657|0.15362|0.00114|0.77%|0.14880|-65.77%|0.14872|-65.77%|1.062|0.000|536605654|27.76 MB|
