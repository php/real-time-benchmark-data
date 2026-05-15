### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-15 01:17:54 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25894904515 ([Artifacts](https://github.com/php/php-src/actions/runs/25894904515/artifacts/7008770500))|
| Changeset  |https://github.com/php/php-src/compare/c0af26858a..0078a27630|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39632|0.39880|0.00075|0.19%|0.39721|0.00%|0.39687|0.00%|0.952|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0af26858a)|0.38963|0.39134|0.00029|0.07%|0.39000|-1.82%|0.38994|-1.75%|2.477|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/0078a27630)|0.38948|0.39141|0.00039|0.10%|0.39000|-1.81%|0.38989|-1.76%|2.136|8.614|0.000|25.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0078a27630)|0.36178|0.36462|0.00056|0.15%|0.36252|-8.73%|0.36233|-8.70%|1.770|8.614|0.000|25.44 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67616|0.67858|0.00046|0.07%|0.67693|0.00%|0.67682|0.00%|1.379|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0af26858a)|0.66952|0.67171|0.00042|0.06%|0.67006|-1.01%|0.66992|-1.02%|1.743|8.614|0.000|25.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/0078a27630)|0.66949|0.67328|0.00056|0.08%|0.66999|-1.03%|0.66987|-1.03%|4.322|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0078a27630)|0.63585|0.63742|0.00030|0.05%|0.63629|-6.00%|0.63626|-5.99%|1.808|8.614|0.000|25.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59003|0.59513|0.00120|0.20%|0.59195|0.00%|0.59175|0.00%|0.521|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0af26858a)|0.58592|0.58849|0.00053|0.09%|0.58664|-0.90%|0.58655|-0.88%|1.380|8.614|0.000|25.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/0078a27630)|0.58591|0.58939|0.00078|0.13%|0.58675|-0.88%|0.58650|-0.89%|1.973|8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0078a27630)|0.51660|0.52096|0.00092|0.18%|0.51748|-12.58%|0.51719|-12.60%|2.333|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44162|0.44579|0.00075|0.17%|0.44296|0.00%|0.44299|0.00%|1.560|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0af26858a)|0.44524|0.44919|0.00066|0.15%|0.44620|0.73%|0.44613|0.71%|2.089|-8.504|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/0078a27630)|0.44444|0.44740|0.00057|0.13%|0.44583|0.65%|0.44587|0.65%|-0.015|-8.386|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0078a27630)|0.14336|0.14553|0.00056|0.39%|0.14390|-67.51%|0.14376|-67.55%|2.187|8.614|0.000|25.40 MB|
