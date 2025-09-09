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
| Time          |2025-09-09 00:49:56 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47279|0.48001|0.00089|0.19%|0.47423|0.00%|0.47411|0.00%|3.088|0.999|180921926|43.21 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e8058e776)|0.46979|0.47508|0.00074|0.16%|0.47134|-0.61%|0.47122|-0.61%|1.953|0.000|176297809|44.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/156c847467)|0.46884|0.47336|0.00089|0.19%|0.47052|-0.78%|0.47027|-0.81%|1.213|0.000|176346654|44.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156c847467)|0.44582|0.45355|0.00089|0.20%|0.45216|-4.65%|0.45220|-4.62%|-4.796|0.000|147789033|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73270|0.75305|0.00170|0.23%|0.74245|0.00%|0.74227|0.00%|0.676|0.999|291584157|39.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e8058e776)|0.73839|0.74964|0.00132|0.18%|0.74024|-0.30%|0.74009|-0.29%|3.690|0.000|287311636|40.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/156c847467)|0.73526|0.74647|0.00170|0.23%|0.73727|-0.70%|0.73689|-0.72%|3.143|0.000|287296840|40.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156c847467)|0.70885|0.71324|0.00084|0.12%|0.71036|-4.32%|0.71029|-4.31%|0.740|0.000|267654281|47.60 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57971|0.58336|0.00078|0.13%|0.58156|0.00%|0.58149|0.00%|0.139|0.999|1123009351|43.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e8058e776)|0.57884|0.59420|0.00131|0.22%|0.58488|0.57%|0.58491|0.59%|2.692|0.000|1120920365|43.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/156c847467)|0.58420|0.58792|0.00078|0.13%|0.58568|0.71%|0.58565|0.71%|0.531|0.000|1120870543|43.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156c847467)|0.51978|0.52294|0.00066|0.13%|0.52154|-10.32%|0.52151|-10.31%|0.127|0.000|867148736|61.51 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42885|0.43646|0.00150|0.35%|0.43119|0.00%|0.43098|0.00%|1.105|0.999|2020733078|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4e8058e776)|0.42575|0.58820|0.03545|8.06%|0.43966|1.97%|0.42930|-0.39%|3.239|0.000|2020744418|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/156c847467)|0.42988|0.55389|0.03171|7.17%|0.44242|2.60%|0.43281|0.42%|3.111|0.000|2020744428|27.02 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156c847467)|0.14770|0.15207|0.00090|0.60%|0.14963|-65.30%|0.14953|-65.31%|0.451|0.000|536712505|28.05 MB|
