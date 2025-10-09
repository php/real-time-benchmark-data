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
| Time          |2025-10-09 00:50:07 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47550|0.47839|0.00055|0.12%|0.47638|0.00%|0.47625|0.00%|1.362|0.999|180947073|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f905950ba5)|0.46683|0.47183|0.00069|0.15%|0.46944|-1.46%|0.46938|-1.44%|0.192|0.000|176327951|44.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/baa5319632)|0.46867|0.47227|0.00053|0.11%|0.46967|-1.41%|0.46963|-1.39%|1.622|0.000|176400835|44.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/baa5319632)|0.44958|0.45479|0.00063|0.14%|0.45044|-5.45%|0.45034|-5.44%|3.644|0.000|147879870|53.45 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73097|0.75142|0.00160|0.22%|0.74072|0.00%|0.74063|0.00%|0.780|0.999|291620724|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f905950ba5)|0.73406|0.74150|0.00146|0.20%|0.73620|-0.61%|0.73576|-0.66%|1.595|0.000|287355527|40.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/baa5319632)|0.73184|0.73740|0.00113|0.15%|0.73347|-0.98%|0.73324|-1.00%|1.269|0.000|287318308|40.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/baa5319632)|0.70566|0.71057|0.00092|0.13%|0.70706|-4.54%|0.70681|-4.57%|1.434|0.000|267677450|47.84 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58077|0.58635|0.00098|0.17%|0.58269|0.00%|0.58256|0.00%|1.336|0.999|1123342377|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f905950ba5)|0.58061|0.58622|0.00088|0.15%|0.58306|0.06%|0.58294|0.07%|1.146|0.000|1120245609|44.13 MB|
|[PHP - master](https://github.com/php/php-src/commit/baa5319632)|0.58106|0.58509|0.00078|0.13%|0.58255|-0.02%|0.58240|-0.03%|0.844|0.399|1120210173|44.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/baa5319632)|0.51763|0.52102|0.00060|0.12%|0.51885|-10.96%|0.51878|-10.95%|1.094|0.000|866265709|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42958|0.43986|0.00190|0.44%|0.43325|0.00%|0.43313|0.00%|0.586|0.999|2020638172|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f905950ba5)|0.43500|0.54183|0.02536|5.70%|0.44518|2.75%|0.43781|1.08%|3.177|0.000|2020595004|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/baa5319632)|0.43743|0.54106|0.02505|5.59%|0.44781|3.36%|0.44047|1.69%|3.133|0.000|2020595081|27.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/baa5319632)|0.14391|0.15010|0.00125|0.85%|0.14718|-66.03%|0.14715|-66.03%|0.094|0.000|536613129|27.80 MB|
