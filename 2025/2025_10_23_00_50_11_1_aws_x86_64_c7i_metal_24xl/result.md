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
| Time          |2025-10-23 00:50:11 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47534|0.47802|0.00054|0.11%|0.47647|0.00%|0.47645|0.00%|0.864|0.999|180946279|43.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/40a42cffd8)|0.46833|0.47406|0.00077|0.16%|0.46985|-1.39%|0.46971|-1.41%|1.962|0.000|176334769|44.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/f8656fae35)|0.46873|0.47255|0.00064|0.14%|0.47005|-1.35%|0.46997|-1.36%|0.906|0.000|176404796|44.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f8656fae35)|0.44365|0.45357|0.00087|0.19%|0.44998|-5.56%|0.44994|-5.56%|-3.109|0.000|147876458|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73251|0.75328|0.00165|0.22%|0.74164|0.00%|0.74157|0.00%|1.915|0.999|291621470|40.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/40a42cffd8)|0.73455|0.74576|0.00181|0.25%|0.73719|-0.60%|0.73667|-0.66%|2.378|0.000|287318844|40.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/f8656fae35)|0.73475|0.74598|0.00172|0.23%|0.73722|-0.60%|0.73695|-0.62%|2.803|0.000|287318819|40.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f8656fae35)|0.70050|0.71103|0.00106|0.15%|0.70895|-4.41%|0.70902|-4.39%|-5.116|0.000|267681741|47.79 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57969|0.58465|0.00093|0.16%|0.58203|0.00%|0.58214|0.00%|-0.185|0.999|1123344158|43.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/40a42cffd8)|0.57964|0.58489|0.00116|0.20%|0.58238|0.06%|0.58247|0.06%|-0.109|0.017|1120065398|44.08 MB|
|[PHP - master](https://github.com/php/php-src/commit/f8656fae35)|0.57997|0.58590|0.00118|0.20%|0.58239|0.06%|0.58248|0.06%|0.339|0.048|1120075182|44.08 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f8656fae35)|0.51595|0.52020|0.00094|0.18%|0.51811|-10.98%|0.51827|-10.97%|-0.207|0.000|866123806|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42598|0.43837|0.00198|0.46%|0.43356|0.00%|0.43371|0.00%|-0.497|0.999|2020638117|26.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/40a42cffd8)|0.42406|0.47782|0.00551|1.29%|0.42833|-1.21%|0.42715|-1.51%|7.539|0.000|2020586576|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/f8656fae35)|0.42315|0.48030|0.00589|1.38%|0.42723|-1.46%|0.42615|-1.74%|7.636|0.000|2020586562|26.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f8656fae35)|0.14388|0.15062|0.00130|0.88%|0.14691|-66.12%|0.14688|-66.13%|0.445|0.000|536605585|27.68 MB|
