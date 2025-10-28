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
| Time          |2025-10-28 00:50:12 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47572|0.47843|0.00058|0.12%|0.47683|0.00%|0.47670|0.00%|0.805|0.999|180950094|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64b30cee76)|0.46195|0.47014|0.00085|0.18%|0.46763|-1.93%|0.46755|-1.92%|-2.366|0.000|176318242|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/be1993bc10)|0.46151|0.47140|0.00099|0.21%|0.46705|-2.05%|0.46692|-2.05%|-0.608|0.000|176386566|44.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be1993bc10)|0.44850|0.45216|0.00058|0.13%|0.44933|-5.77%|0.44922|-5.76%|1.814|0.000|147858876|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74039|0.74370|0.00070|0.09%|0.74187|0.00%|0.74179|0.00%|0.241|0.999|291624654|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64b30cee76)|0.73351|0.74533|0.00188|0.25%|0.73588|-0.81%|0.73530|-0.87%|2.135|0.000|287328016|40.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/be1993bc10)|0.73371|0.74652|0.00266|0.36%|0.73643|-0.73%|0.73526|-0.88%|1.627|0.000|287324457|40.68 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be1993bc10)|0.70748|0.71240|0.00081|0.11%|0.70933|-4.39%|0.70923|-4.39%|0.680|0.000|267687128|47.79 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58071|0.59262|0.00135|0.23%|0.58240|0.00%|0.58209|0.00%|4.605|0.999|1123340342|43.58 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64b30cee76)|0.58259|0.58630|0.00076|0.13%|0.58391|0.26%|0.58366|0.27%|1.071|0.000|1120088322|44.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/be1993bc10)|0.58141|0.58438|0.00066|0.11%|0.58287|0.08%|0.58286|0.13%|0.059|0.000|1120087747|44.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be1993bc10)|0.51724|0.51952|0.00054|0.10%|0.51832|-11.00%|0.51827|-10.96%|0.420|0.000|866138864|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42940|0.44381|0.00222|0.51%|0.43359|0.00%|0.43351|0.00%|1.020|0.999|2020638220|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/64b30cee76)|0.42383|0.47872|0.00575|1.34%|0.42806|-1.27%|0.42695|-1.51%|7.192|0.000|2020586632|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/be1993bc10)|0.42246|0.43867|0.00337|0.79%|0.42765|-1.37%|0.42635|-1.65%|1.558|0.000|2020586597|26.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be1993bc10)|0.14377|0.15002|0.00127|0.87%|0.14663|-66.18%|0.14652|-66.20%|0.392|0.000|536605555|27.68 MB|
