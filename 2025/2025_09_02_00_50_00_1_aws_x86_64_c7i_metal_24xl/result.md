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
| Time          |2025-09-02 00:50:00 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47005|0.47478|0.00064|0.14%|0.47276|0.00%|0.47271|0.00%|-0.089|0.999|181232360|43.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ca4a841921)|0.46119|0.46883|0.00076|0.16%|0.46756|-1.10%|0.46760|-1.08%|-6.011|0.000|176638167|44.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/0c6b83887e)|0.46644|0.47232|0.00066|0.14%|0.46724|-1.17%|0.46716|-1.18%|4.954|0.000|176636952|44.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0c6b83887e)|0.45013|0.45192|0.00037|0.08%|0.45105|-4.59%|0.45107|-4.58%|-0.217|0.000|149308945|53.93 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73660|0.74577|0.00113|0.15%|0.74109|0.00%|0.74087|0.00%|0.667|0.999|291550426|39.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ca4a841921)|0.72991|0.74052|0.00161|0.22%|0.73171|-1.27%|0.73138|-1.28%|3.558|0.000|287291263|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/0c6b83887e)|0.73246|0.74446|0.00211|0.29%|0.73455|-0.88%|0.73406|-0.92%|3.245|0.000|287306641|40.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0c6b83887e)|0.70541|0.71097|0.00102|0.14%|0.70690|-4.61%|0.70678|-4.60%|1.914|0.000|267610201|47.54 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57856|0.58308|0.00070|0.12%|0.58038|0.00%|0.58032|0.00%|0.679|0.999|1123001928|43.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ca4a841921)|0.57702|0.58394|0.00084|0.14%|0.58185|0.25%|0.58191|0.27%|-2.001|0.000|1119156458|43.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/0c6b83887e)|0.58035|0.58443|0.00069|0.12%|0.58232|0.33%|0.58235|0.35%|0.249|0.000|1119165734|43.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0c6b83887e)|0.51588|0.51935|0.00059|0.11%|0.51789|-10.77%|0.51787|-10.76%|-0.121|0.000|865526941|61.44 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42768|0.44288|0.00174|0.40%|0.43124|0.00%|0.43095|0.00%|3.140|0.999|2020733073|26.37 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ca4a841921)|0.42216|0.58594|0.03119|7.20%|0.43325|0.46%|0.42553|-1.26%|3.956|0.000|2020744368|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/0c6b83887e)|0.42311|0.54954|0.02989|6.89%|0.43385|0.60%|0.42548|-1.27%|3.388|0.000|2020744474|27.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0c6b83887e)|0.14766|0.15192|0.00096|0.64%|0.14957|-65.32%|0.14944|-65.32%|0.373|0.000|536712442|28.06 MB|
