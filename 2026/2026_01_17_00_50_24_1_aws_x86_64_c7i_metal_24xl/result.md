### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-17 00:50:24 UTC|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46136|0.46479|0.00072|0.15%|0.46209|0.00%|0.46190|0.00%|2.890|0.999|27.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9b719cd4a3)|0.45727|0.45948|0.00044|0.10%|0.45788|-0.91%|0.45775|-0.90%|1.424|0.000|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/084e409694)|0.45738|0.46432|0.00090|0.20%|0.45800|-0.89%|0.45776|-0.90%|5.166|0.000|27.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/084e409694)|0.43878|0.44050|0.00035|0.08%|0.43931|-4.93%|0.43922|-4.91%|1.176|0.000|27.03 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.77399|0.79386|0.00278|0.36%|0.78190|0.00%|0.78171|0.00%|1.763|0.999|27.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9b719cd4a3)|0.77247|0.78333|0.00233|0.30%|0.77939|-0.32%|0.78049|-0.16%|-0.871|0.000|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/084e409694)|0.77761|0.79116|0.00153|0.20%|0.78066|-0.16%|0.78058|-0.14%|3.176|0.000|27.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/084e409694)|0.75075|0.99488|0.08623|10.51%|0.82018|4.90%|0.75334|-3.63%|0.647|0.031|27.05 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.66083|0.68145|0.00237|0.36%|0.66222|0.00%|0.66165|0.00%|6.000|0.999|27.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9b719cd4a3)|0.66301|0.68357|0.00305|0.46%|0.66437|0.33%|0.66382|0.33%|5.646|0.000|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/084e409694)|0.66148|0.68239|0.00206|0.31%|0.66257|0.05%|0.66234|0.10%|9.154|0.000|27.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/084e409694)|0.59317|0.59545|0.00043|0.07%|0.59419|-10.27%|0.59416|-10.20%|0.620|0.000|27.05 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42555|0.43125|0.00123|0.29%|0.42794|0.00%|0.42789|0.00%|0.350|0.999|7.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9b719cd4a3)|0.43097|0.44013|0.00180|0.41%|0.43600|1.88%|0.43596|1.88%|-0.198|0.000|7.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/084e409694)|0.44045|0.44900|0.00162|0.37%|0.44402|3.76%|0.44381|3.72%|0.341|0.000|7.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/084e409694)|0.13670|0.14380|0.00132|0.94%|0.14076|-67.11%|0.14073|-67.11%|0.129|0.000|7.95 MB|
