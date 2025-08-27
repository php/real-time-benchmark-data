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
| Time          |2025-08-27 00:50:20 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46421|0.47508|0.00103|0.22%|0.47138|0.00%|0.47130|0.00%|-2.521|0.999|181827525|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/99068da2b1)|0.46684|0.46859|0.00037|0.08%|0.46779|-0.76%|0.46782|-0.74%|-0.066|0.000|177224657|43.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/e844e68af8)|0.46666|0.46925|0.00045|0.10%|0.46763|-0.80%|0.46764|-0.78%|0.645|0.000|177195722|43.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e844e68af8)|0.44823|0.45067|0.00035|0.08%|0.44919|-4.71%|0.44919|-4.69%|0.598|0.000|149595466|53.89 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74061|0.74494|0.00094|0.13%|0.74253|0.00%|0.74247|0.00%|0.379|0.999|292377400|39.96 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/99068da2b1)|0.73276|0.74457|0.00228|0.31%|0.73513|-1.00%|0.73457|-1.06%|2.259|0.000|288324175|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/e844e68af8)|0.73428|0.74508|0.00221|0.30%|0.73711|-0.73%|0.73645|-0.81%|2.154|0.000|288317995|40.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e844e68af8)|0.70276|0.70685|0.00081|0.12%|0.70412|-5.17%|0.70396|-5.19%|0.899|0.000|267489862|48.08 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58281|0.59290|0.00113|0.19%|0.58443|0.00%|0.58425|0.00%|4.476|0.999|1133180351|43.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/99068da2b1)|0.58203|0.58705|0.00078|0.13%|0.58326|-0.20%|0.58309|-0.20%|1.910|0.000|1129271214|43.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/e844e68af8)|0.57903|0.58264|0.00069|0.12%|0.58077|-0.63%|0.58066|-0.62%|0.409|0.000|1129176936|43.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e844e68af8)|0.51323|0.51879|0.00073|0.14%|0.51700|-11.54%|0.51704|-11.50%|-1.149|0.000|867782151|61.52 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42604|0.43682|0.00174|0.40%|0.43165|0.00%|0.43166|0.00%|-0.014|0.999|2031002304|26.49 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/99068da2b1)|0.42741|0.56075|0.01769|4.09%|0.43262|0.23%|0.42997|-0.39%|6.912|0.000|2031543227|26.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/e844e68af8)|0.43529|0.55997|0.02858|6.41%|0.44593|3.31%|0.43812|1.50%|3.420|0.000|2031378918|26.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e844e68af8)|0.14600|0.15225|0.00135|0.91%|0.14840|-65.62%|0.14828|-65.65%|0.630|0.000|536898170|27.89 MB|
