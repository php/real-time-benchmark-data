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
| GCC           |11.5.0|
| Time          |2025-08-28 00:49:49 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46960|0.47360|0.00068|0.14%|0.47058|0.00%|0.47048|0.00%|1.529|0.999|181823916|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e844e68af8)|0.45920|0.47097|0.00098|0.21%|0.46635|-0.90%|0.46634|-0.88%|-2.838|0.000|177196431|43.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/5d5ef5050a)|0.46555|0.46758|0.00041|0.09%|0.46647|-0.87%|0.46645|-0.86%|0.218|0.000|177193221|43.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5d5ef5050a)|0.44704|0.44924|0.00041|0.09%|0.44788|-4.82%|0.44785|-4.81%|0.882|0.000|149600579|53.89 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73945|0.74588|0.00101|0.14%|0.74141|0.00%|0.74145|0.00%|1.277|0.999|292385314|39.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e844e68af8)|0.72417|0.74297|0.00185|0.25%|0.73478|-0.89%|0.73447|-0.94%|-0.444|0.000|288319104|40.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/5d5ef5050a)|0.72412|0.74414|0.00237|0.32%|0.73517|-0.84%|0.73471|-0.91%|0.816|0.000|288319140|40.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5d5ef5050a)|0.70113|0.70694|0.00107|0.15%|0.70284|-5.20%|0.70267|-5.23%|1.464|0.000|267484550|48.08 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57995|0.59057|0.00116|0.20%|0.58258|0.00%|0.58261|0.00%|2.943|0.999|1133182843|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e844e68af8)|0.57566|0.58319|0.00100|0.17%|0.57955|-0.52%|0.57966|-0.51%|-0.439|0.000|1129171493|43.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/5d5ef5050a)|0.57666|0.58199|0.00094|0.16%|0.57957|-0.52%|0.57952|-0.53%|-0.462|0.000|1129171026|43.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5d5ef5050a)|0.51317|0.51732|0.00079|0.15%|0.51534|-11.54%|0.51550|-11.52%|-0.880|0.000|867780027|61.52 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42537|0.43696|0.00181|0.42%|0.43169|0.00%|0.43175|0.00%|-0.043|0.999|2031002265|26.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e844e68af8)|0.43391|0.56183|0.02809|6.30%|0.44626|3.38%|0.43857|1.58%|3.441|0.000|2031379103|26.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/5d5ef5050a)|0.43525|0.55709|0.03182|7.10%|0.44831|3.85%|0.43825|1.51%|2.907|0.000|2031378901|26.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5d5ef5050a)|0.14589|0.15194|0.00126|0.85%|0.14858|-65.58%|0.14851|-65.60%|0.172|0.000|536898189|27.89 MB|
