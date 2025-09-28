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
| Time          |2025-09-28 00:50:25 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46917|0.47589|0.00086|0.18%|0.47018|0.00%|0.46993|0.00%|3.359|0.999|180949964|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b930654b)|0.46219|0.46485|0.00068|0.15%|0.46326|-1.47%|0.46309|-1.45%|0.814|0.000|176331321|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee2da6d9e9)|0.46253|0.46806|0.00103|0.22%|0.46372|-1.37%|0.46344|-1.38%|2.149|0.000|176405808|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee2da6d9e9)|0.44238|0.44675|0.00060|0.14%|0.44355|-5.66%|0.44351|-5.62%|2.846|0.000|147885048|53.44 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73096|0.75194|0.00444|0.60%|0.73940|0.00%|0.74128|0.00%|-0.888|0.999|291626074|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b930654b)|0.72719|0.74036|0.00423|0.57%|0.73573|-0.50%|0.73748|-0.51%|-1.142|0.000|287357893|40.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee2da6d9e9)|0.72576|0.74259|0.00442|0.60%|0.73491|-0.61%|0.73659|-0.63%|-1.031|0.000|287354486|40.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee2da6d9e9)|0.69945|0.71145|0.00348|0.49%|0.70669|-4.42%|0.70825|-4.46%|-1.116|0.000|267690910|47.58 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58109|0.59163|0.00111|0.19%|0.58253|0.00%|0.58236|0.00%|5.840|0.999|1123342430|43.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b930654b)|0.57896|0.58379|0.00078|0.13%|0.58065|-0.32%|0.58053|-0.31%|1.068|0.000|1120245278|44.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee2da6d9e9)|0.57634|0.58335|0.00080|0.14%|0.58129|-0.21%|0.58132|-0.18%|-1.948|0.000|1120246049|44.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee2da6d9e9)|0.51743|0.51987|0.00053|0.10%|0.51858|-10.98%|0.51861|-10.95%|-0.071|0.000|866321416|61.55 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42606|0.43826|0.00207|0.48%|0.43305|0.00%|0.43287|0.00%|0.143|0.999|2020638172|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b930654b)|0.42796|0.60348|0.02655|6.07%|0.43771|1.08%|0.43124|-0.38%|4.330|0.000|2020595077|26.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/ee2da6d9e9)|0.42595|0.53188|0.02108|4.86%|0.43410|0.24%|0.42902|-0.89%|4.144|0.000|2020595072|26.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ee2da6d9e9)|0.14727|0.15257|0.00100|0.67%|0.14950|-65.48%|0.14940|-65.49%|0.526|0.000|536613067|27.73 MB|
