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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2024-12-16 00:49:50 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43873|0.44030|0.00038|0.43950|0.00%|0.43944|0.00%|41.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/57e9429e73)|0.43659|0.43847|0.00042|0.43728|-0.50%|0.43719|-0.51%|41.68 MB|
|[PHP - master](https://github.com/php/php-src/commit/e02c226725)|0.43634|0.44325|0.00092|0.43750|-0.46%|0.43740|-0.46%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e02c226725)|0.42378|0.42599|0.00043|0.42468|-3.37%|0.42468|-3.36%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71300|0.71799|0.00087|0.71414|0.00%|0.71391|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/57e9429e73)|0.70914|0.71237|0.00072|0.71016|-0.56%|0.70997|-0.55%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/e02c226725)|0.71021|0.72580|0.00207|0.71187|-0.32%|0.71163|-0.32%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e02c226725)|0.68257|0.68508|0.00060|0.68357|-4.28%|0.68359|-4.25%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58098|0.58404|0.00072|0.58250|0.00%|0.58234|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/57e9429e73)|0.58084|0.58343|0.00056|0.58185|-0.11%|0.58182|-0.09%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/e02c226725)|0.57447|0.58116|0.00167|0.57861|-0.67%|0.57885|-0.60%|42.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e02c226725)|0.51923|0.52267|0.00058|0.52027|-10.68%|0.52017|-10.68%|61.62 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21480|0.21819|0.00092|0.21621|0.00%|0.21621|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/57e9429e73)|0.21314|0.21644|0.00082|0.21440|-0.84%|0.21426|-0.91%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/e02c226725)|0.21191|0.21551|0.00087|0.21368|-1.17%|0.21358|-1.22%|26.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e02c226725)|0.07420|0.07746|0.00083|0.07572|-64.98%|0.07575|-64.97%|27.22 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34363|1.36687|0.00507|1.35502|0.00%|1.35549|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/57e9429e73)|1.25223|1.26788|0.00377|1.26014|-7.00%|1.25979|-7.06%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/e02c226725)|1.25975|1.27937|0.00330|1.26797|-6.42%|1.26780|-6.47%|20.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e02c226725)|0.52499|0.54522|0.00418|0.53287|-60.67%|0.53306|-60.67%|21.64 MB|
