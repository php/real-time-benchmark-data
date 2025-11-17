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
| OS            |Amazon Linux 2023.9.20251110|
| GCC           |14.2.1|
| Time          |2025-11-17 00:50:14 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47458|0.48102|0.00073|0.15%|0.47570|0.00%|0.47555|0.00%|4.047|0.999|180943242|43.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0194b381d6)|0.46786|0.47382|0.00073|0.16%|0.46916|-1.37%|0.46904|-1.37%|2.842|0.000|176405180|44.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/3977650820)|0.46793|0.47363|0.00083|0.18%|0.46906|-1.40%|0.46887|-1.40%|2.498|0.000|176401407|44.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3977650820)|0.44389|0.45440|0.00087|0.19%|0.45018|-5.36%|0.45014|-5.34%|-2.578|0.000|147885738|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73765|0.75404|0.00218|0.29%|0.74376|0.00%|0.74339|0.00%|3.400|0.999|291625362|40.10 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0194b381d6)|0.74019|0.75312|0.00244|0.33%|0.74264|-0.15%|0.74182|-0.21%|2.621|0.000|290398580|40.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/3977650820)|0.74023|0.75136|0.00184|0.25%|0.74242|-0.18%|0.74183|-0.21%|2.073|0.000|290399816|40.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3977650820)|0.71303|0.72391|0.00165|0.23%|0.71490|-3.88%|0.71456|-3.88%|3.452|0.000|270758343|47.86 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57590|0.58356|0.00212|0.36%|0.57989|0.00%|0.58056|0.00%|-0.612|0.999|1123344228|43.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0194b381d6)|0.57484|0.59072|0.00259|0.45%|0.57921|-0.12%|0.57991|-0.11%|1.021|0.000|1119621439|44.10 MB|
|[PHP - master](https://github.com/php/php-src/commit/3977650820)|0.57448|0.58362|0.00208|0.36%|0.57886|-0.18%|0.57954|-0.18%|-0.597|0.000|1119631601|44.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3977650820)|0.51311|0.51858|0.00149|0.29%|0.51629|-10.97%|0.51698|-10.95%|-0.756|0.000|865681141|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43023|0.44370|0.00212|0.49%|0.43418|0.00%|0.43399|0.00%|1.233|0.999|2020638236|26.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0194b381d6)|0.42403|0.43956|0.00314|0.73%|0.42785|-1.46%|0.42687|-1.64%|1.805|0.000|2020586648|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/3977650820)|0.42428|0.43684|0.00219|0.51%|0.42772|-1.49%|0.42735|-1.53%|1.715|0.000|2020586622|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3977650820)|0.14689|0.15250|0.00090|0.60%|0.14854|-65.79%|0.14844|-65.80%|1.196|0.000|536605603|27.75 MB|
