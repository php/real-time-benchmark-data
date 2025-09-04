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
| Time          |2025-09-04 00:49:47 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47136|0.47423|0.00044|0.09%|0.47245|0.00%|0.47245|0.00%|0.756|0.999|181236726|43.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d85662d6cc)|0.46028|0.46829|0.00078|0.17%|0.46670|-1.22%|0.46673|-1.21%|-5.676|0.000|176641059|44.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/9b960713c6)|0.46694|0.46905|0.00040|0.09%|0.46780|-0.99%|0.46770|-1.01%|0.983|0.000|176648173|44.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9b960713c6)|0.45139|0.45312|0.00037|0.08%|0.45214|-4.30%|0.45209|-4.31%|0.438|0.000|149320894|53.92 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73077|0.74703|0.00150|0.20%|0.74145|0.00%|0.74144|0.00%|-3.054|0.999|291542856|39.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d85662d6cc)|0.73104|0.73960|0.00158|0.22%|0.73302|-1.14%|0.73266|-1.18%|2.373|0.000|287261270|40.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/9b960713c6)|0.73309|0.74149|0.00129|0.18%|0.73515|-0.85%|0.73499|-0.87%|2.078|0.000|287262454|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9b960713c6)|0.70085|0.71616|0.00148|0.21%|0.70940|-4.32%|0.70920|-4.35%|-0.600|0.000|267614710|47.53 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57831|0.58269|0.00079|0.14%|0.58015|0.00%|0.58011|0.00%|0.296|0.999|1123006135|43.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d85662d6cc)|0.58024|0.58505|0.00069|0.12%|0.58198|0.31%|0.58205|0.33%|0.528|0.000|1119172219|43.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/9b960713c6)|0.58035|0.58396|0.00064|0.11%|0.58236|0.38%|0.58238|0.39%|-0.181|0.000|1119175038|43.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9b960713c6)|0.51638|0.52005|0.00065|0.13%|0.51787|-10.74%|0.51786|-10.73%|0.175|0.000|865536743|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42731|0.44248|0.00246|0.57%|0.43193|0.00%|0.43142|0.00%|2.235|0.999|2020733106|26.37 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d85662d6cc)|0.42430|0.56162|0.02536|5.84%|0.43380|0.43%|0.42791|-0.81%|4.212|0.000|2020744421|27.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/9b960713c6)|0.42361|0.58847|0.03797|8.64%|0.43951|1.76%|0.42650|-1.14%|2.621|0.000|2020744520|27.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9b960713c6)|0.14812|0.15342|0.00104|0.69%|0.14971|-65.34%|0.14952|-65.34%|0.766|0.000|536712598|28.05 MB|
