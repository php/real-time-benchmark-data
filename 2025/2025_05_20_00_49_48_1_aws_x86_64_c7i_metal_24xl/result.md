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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-05-20 00:49:48 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43889|0.45384|0.00254|0.44048|0.00%|0.44011|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/00f0175ba9)|0.44027|0.44350|0.00068|0.44138|0.21%|0.44126|0.26%|42.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/63657df6e1)|0.43955|0.44264|0.00073|0.44050|0.00%|0.44038|0.06%|42.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63657df6e1)|0.42304|0.42472|0.00039|0.42390|-3.76%|0.42394|-3.67%|50.92 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71579|0.71952|0.00106|0.71711|0.00%|0.71682|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/00f0175ba9)|0.71008|0.71560|0.00141|0.71207|-0.70%|0.71173|-0.71%|37.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/63657df6e1)|0.71022|0.71323|0.00078|0.71155|-0.77%|0.71168|-0.72%|37.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63657df6e1)|0.67804|0.68218|0.00112|0.68001|-5.17%|0.67970|-5.18%|44.67 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58138|0.59139|0.00168|0.58275|0.00%|0.58239|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/00f0175ba9)|0.57826|0.58390|0.00103|0.57962|-0.54%|0.57940|-0.51%|43.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/63657df6e1)|0.58180|0.58492|0.00064|0.58290|0.03%|0.58286|0.08%|43.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63657df6e1)|0.52616|0.52831|0.00041|0.52717|-9.54%|0.52720|-9.48%|60.83 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21584|0.21896|0.00073|0.21712|0.00%|0.21707|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/00f0175ba9)|0.21336|0.21942|0.00148|0.21479|-1.07%|0.21439|-1.23%|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/63657df6e1)|0.21235|0.21637|0.00102|0.21426|-1.32%|0.21433|-1.26%|26.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63657df6e1)|0.07559|0.07830|0.00062|0.07675|-64.65%|0.07660|-64.71%|27.48 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34564|1.36791|0.00522|1.35622|0.00%|1.35508|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/00f0175ba9)|1.26929|1.28819|0.00586|1.27844|-5.74%|1.27694|-5.77%|20.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/63657df6e1)|1.29738|1.32365|0.00602|1.30882|-3.50%|1.30874|-3.42%|20.66 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/63657df6e1)|0.56393|0.58806|0.00601|0.57600|-57.53%|0.57656|-57.45%|21.90 MB|
