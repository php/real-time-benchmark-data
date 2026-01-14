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
| Time          |2026-01-14 00:50:30 UTC|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46097|0.46671|0.00093|0.20%|0.46168|0.00%|0.46141|0.00%|3.295|0.999|185272326|27.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4098da58a)|0.46118|0.46328|0.00040|0.09%|0.46182|0.03%|0.46174|0.07%|1.412|0.000|180345197|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/858d34fd32)|0.46020|0.46653|0.00066|0.14%|0.46098|-0.15%|0.46088|-0.11%|6.230|0.000|180343208|26.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/858d34fd32)|0.43856|0.44297|0.00067|0.15%|0.43933|-4.84%|0.43916|-4.82%|3.400|0.000|152487615|26.94 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74879|0.76115|0.00168|0.22%|0.75058|0.00%|0.75018|0.00%|4.881|0.999|296678503|27.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4098da58a)|0.77222|0.79147|0.00371|0.48%|0.77852|3.72%|0.78009|3.99%|0.418|0.000|295194104|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/858d34fd32)|0.77117|0.78968|0.00153|0.20%|0.77924|3.82%|0.77908|3.85%|1.947|0.000|295205310|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/858d34fd32)|0.75106|1.00703|0.08920|10.99%|0.81189|8.17%|0.75342|0.43%|1.351|0.000|277789494|26.98 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.65949|0.67447|0.00189|0.29%|0.66104|0.00%|0.66062|0.00%|4.528|0.999|1409590545|27.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4098da58a)|0.66470|0.66722|0.00053|0.08%|0.66589|0.73%|0.66584|0.79%|0.301|0.000|1415718480|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/858d34fd32)|0.66183|0.66570|0.00064|0.10%|0.66309|0.31%|0.66301|0.36%|1.144|0.000|1415706013|26.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/858d34fd32)|0.59167|0.59354|0.00042|0.07%|0.59237|-10.39%|0.59234|-10.34%|0.529|0.000|1155094096|27.00 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42519|0.43092|0.00119|0.28%|0.42760|0.00%|0.42749|0.00%|0.350|0.999|2020733479|7.97 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4098da58a)|0.43096|0.43996|0.00172|0.40%|0.43567|1.89%|0.43551|1.88%|0.257|0.000|2020687121|7.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/858d34fd32)|0.43302|0.43866|0.00126|0.29%|0.43564|1.88%|0.43549|1.87%|0.080|0.000|2020687236|7.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/858d34fd32)|0.14160|0.14618|0.00086|0.60%|0.14364|-66.41%|0.14361|-66.41%|0.256|0.000|539477057|7.97 MB|
