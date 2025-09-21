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
| Time          |2025-09-21 00:50:26 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46986|0.47786|0.00084|0.18%|0.47636|0.00%|0.47641|0.00%|-4.599|0.999|180945085|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b637dfc4e)|0.46641|0.47255|0.00080|0.17%|0.46732|-1.90%|0.46711|-1.95%|3.779|0.000|176267665|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb49281739)|0.46741|0.47031|0.00067|0.14%|0.46828|-1.70%|0.46810|-1.75%|1.277|0.000|176339671|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb49281739)|0.44269|0.45134|0.00078|0.17%|0.44901|-5.74%|0.44898|-5.76%|-5.105|0.000|147809471|53.50 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74044|0.75244|0.00190|0.26%|0.74203|0.00%|0.74170|0.00%|4.493|0.999|291622848|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b637dfc4e)|0.72546|0.74320|0.00213|0.29%|0.73320|-1.19%|0.73257|-1.23%|1.549|0.000|287303497|40.74 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb49281739)|0.73530|0.74137|0.00128|0.17%|0.73733|-0.63%|0.73695|-0.64%|1.144|0.000|287304349|40.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb49281739)|0.70762|0.71125|0.00073|0.10%|0.70924|-4.42%|0.70924|-4.38%|0.160|0.000|267645013|47.63 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57930|0.58382|0.00104|0.18%|0.58126|0.00%|0.58115|0.00%|0.377|0.999|1123343895|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b637dfc4e)|0.57908|0.59249|0.00151|0.26%|0.58158|0.06%|0.58141|0.04%|3.813|0.087|1119772852|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb49281739)|0.58101|0.58877|0.00121|0.21%|0.58558|0.74%|0.58560|0.77%|-0.195|0.000|1119781216|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb49281739)|0.51590|0.51986|0.00090|0.17%|0.51745|-10.98%|0.51745|-10.96%|0.219|0.000|865939487|61.61 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42888|0.44041|0.00204|0.47%|0.43386|0.00%|0.43370|0.00%|0.632|0.999|2020638221|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b637dfc4e)|0.42468|0.55354|0.03012|6.90%|0.43671|0.66%|0.42851|-1.20%|3.419|0.000|2020645010|27.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb49281739)|0.42653|0.58857|0.04193|9.41%|0.44548|2.68%|0.42986|-0.89%|2.323|0.000|2020644994|27.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb49281739)|0.14577|0.15342|0.00141|0.95%|0.14864|-65.74%|0.14869|-65.72%|0.377|0.000|536613039|27.91 MB|
