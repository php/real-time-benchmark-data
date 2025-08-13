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
| OS            |Amazon Linux 2023.8.20250808|
| GCC           |11.5.0|
| Time          |2025-08-13 00:50:03 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47106|0.47446|0.00083|0.47213|0.00%|0.47185|0.00%|46.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|0.46823|0.47009|0.00042|0.46914|-0.63%|0.46917|-0.57%|46.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/60047025db)|0.46548|0.46695|0.00038|0.46627|-1.24%|0.46623|-1.19%|46.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60047025db)|0.44973|0.45092|0.00029|0.45042|-4.60%|0.45045|-4.53%|57.98 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73991|0.74689|0.00182|0.74223|0.00%|0.74189|0.00%|28.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|0.72971|0.73948|0.00174|0.73102|-1.51%|0.73042|-1.55%|27.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/60047025db)|0.72829|0.73520|0.00143|0.73010|-1.63%|0.72971|-1.64%|27.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60047025db)|0.69898|0.70669|0.00138|0.70306|-5.28%|0.70290|-5.26%|29.19 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58389|0.58979|0.00104|0.58870|0.00%|0.58887|0.00%|43.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|0.58499|0.58837|0.00069|0.58666|-0.35%|0.58667|-0.37%|43.60 MB|
|[PHP - master](https://github.com/php/php-src/commit/60047025db)|0.58368|0.58613|0.00064|0.58456|-0.70%|0.58443|-0.76%|43.60 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60047025db)|0.52275|0.52461|0.00046|0.52388|-11.01%|0.52387|-11.04%|61.40 MB|

### bench.php - 20 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21545|0.21796|0.00079|0.21668|0.00%|0.21671|0.00%|25.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|0.21689|0.26733|0.01219|0.22182|2.37%|0.21873|0.93%|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/60047025db)|0.21861|0.27998|0.01836|0.22717|4.84%|0.22027|1.65%|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60047025db)|0.08238|0.08478|0.00059|0.08320|-61.60%|0.08308|-61.66%|26.47 MB|

### micro_bench.php - 20 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.36904|1.39050|0.00523|1.38135|0.00%|1.38335|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|1.33813|1.34967|0.00363|1.34302|-2.77%|1.34279|-2.93%|20.84 MB|
|[PHP - master](https://github.com/php/php-src/commit/60047025db)|1.29479|1.30669|0.00335|1.29967|-5.91%|1.29912|-6.09%|20.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60047025db)|0.56167|0.57762|0.00455|0.56899|-58.81%|0.56929|-58.85%|22.23 MB|
