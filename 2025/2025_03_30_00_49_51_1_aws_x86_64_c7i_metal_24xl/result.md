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
| Kernel        |6.1.130-139.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250317|
| GCC           |11.5.0|
| Time          |2025-03-30 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43818|0.44839|0.00177|0.43920|0.00%|0.43879|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/314219387e)|0.43522|0.43709|0.00044|0.43594|-0.74%|0.43584|-0.67%|41.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/0607c22f8e)|0.43483|0.43744|0.00066|0.43591|-0.75%|0.43578|-0.69%|41.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0607c22f8e)|0.42421|0.42673|0.00051|0.42502|-3.23%|0.42491|-3.16%|50.81 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70638|0.71631|0.00161|0.71394|0.00%|0.71415|0.00%|37.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/314219387e)|0.70643|0.70922|0.00067|0.70747|-0.91%|0.70745|-0.94%|37.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/0607c22f8e)|0.70594|0.71029|0.00081|0.70744|-0.91%|0.70728|-0.96%|37.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0607c22f8e)|0.67736|0.68073|0.00081|0.67906|-4.89%|0.67904|-4.92%|44.58 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58007|0.58229|0.00055|0.58116|0.00%|0.58120|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/314219387e)|0.57646|0.57990|0.00080|0.57847|-0.46%|0.57856|-0.45%|43.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/0607c22f8e)|0.57669|0.57975|0.00063|0.57795|-0.55%|0.57792|-0.56%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0607c22f8e)|0.51854|0.52218|0.00079|0.52113|-10.33%|0.52123|-10.32%|60.60 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21556|0.21908|0.00079|0.21699|0.00%|0.21676|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/314219387e)|0.21757|0.22091|0.00087|0.21911|0.98%|0.21934|1.19%|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/0607c22f8e)|0.21771|0.21981|0.00058|0.21878|0.82%|0.21872|0.90%|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0607c22f8e)|0.07469|0.07734|0.00066|0.07570|-65.12%|0.07567|-65.09%|27.39 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34149|1.37079|0.00591|1.35306|0.00%|1.35213|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/314219387e)|1.26347|1.28391|0.00526|1.27376|-5.86%|1.27348|-5.82%|20.60 MB|
|[PHP - master](https://github.com/php/php-src/commit/0607c22f8e)|1.26266|1.28364|0.00535|1.27161|-6.02%|1.27157|-5.96%|20.60 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0607c22f8e)|0.52374|0.53679|0.00316|0.53129|-60.73%|0.53032|-60.78%|21.81 MB|
