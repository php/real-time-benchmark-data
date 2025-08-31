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
| Time          |2025-08-31 00:50:03 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47387|0.47902|0.00071|0.15%|0.47533|0.00%|0.47523|0.00%|1.535|0.999|181233317|43.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/914f9ad49b)|0.46930|0.47142|0.00045|0.09%|0.47027|-1.06%|0.47021|-1.06%|0.069|0.000|176641712|44.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a086e4e73)|0.46887|0.47133|0.00049|0.10%|0.46975|-1.17%|0.46976|-1.15%|0.555|0.000|176633187|44.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a086e4e73)|0.45279|0.45511|0.00046|0.10%|0.45374|-4.54%|0.45370|-4.53%|0.642|0.000|149304537|53.92 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74298|0.74687|0.00085|0.11%|0.74487|0.00%|0.74486|0.00%|0.078|0.999|291548285|39.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/914f9ad49b)|0.73623|0.74790|0.00232|0.31%|0.73890|-0.80%|0.73826|-0.89%|2.511|0.000|287307787|40.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a086e4e73)|0.73724|0.74930|0.00227|0.31%|0.73946|-0.73%|0.73880|-0.81%|2.269|0.000|287307652|40.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a086e4e73)|0.70896|0.71446|0.00106|0.15%|0.71069|-4.59%|0.71056|-4.61%|1.318|0.000|267615070|47.53 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57741|0.58248|0.00069|0.12%|0.58052|0.00%|0.58041|0.00%|-0.262|0.999|1122998779|43.43 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/914f9ad49b)|0.57939|0.58374|0.00064|0.11%|0.58187|0.23%|0.58180|0.24%|0.137|0.000|1119164838|43.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a086e4e73)|0.58029|0.58442|0.00065|0.11%|0.58171|0.21%|0.58169|0.22%|0.924|0.000|1119165539|43.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a086e4e73)|0.51734|0.52119|0.00063|0.12%|0.51835|-10.71%|0.51825|-10.71%|1.647|0.000|865525960|61.43 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42837|0.44294|0.00209|0.48%|0.43149|0.00%|0.43119|0.00%|2.271|0.999|2020733083|26.37 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/914f9ad49b)|0.42414|0.58631|0.03450|7.87%|0.43833|1.58%|0.42771|-0.81%|3.011|0.000|2020744350|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/2a086e4e73)|0.42308|0.55243|0.03192|7.33%|0.43529|0.88%|0.42587|-1.23%|3.122|0.000|2020744448|26.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2a086e4e73)|0.14560|0.15293|0.00135|0.91%|0.14810|-65.68%|0.14799|-65.68%|0.935|0.000|536712525|27.98 MB|
