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
| Kernel        |6.1.147-172.259.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250804|
| GCC           |11.5.0|
| Time          |2025-08-07 00:50:06 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46784|0.47759|0.00166|0.47217|0.00%|0.47177|0.00%|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1820dd9b61)|0.46762|0.46984|0.00045|0.46819|-0.84%|0.46812|-0.77%|43.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/c42e6d62d8)|0.46195|0.47012|0.00127|0.46834|-0.81%|0.46845|-0.70%|43.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c42e6d62d8)|0.45009|0.45163|0.00036|0.45076|-4.53%|0.45070|-4.47%|53.73 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73990|0.74556|0.00105|0.74198|0.00%|0.74175|0.00%|39.94 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1820dd9b61)|0.73250|0.73915|0.00188|0.73425|-1.04%|0.73367|-1.09%|40.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/c42e6d62d8)|0.73054|0.73612|0.00102|0.73182|-1.37%|0.73151|-1.38%|40.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c42e6d62d8)|0.69951|0.70569|0.00128|0.70116|-5.50%|0.70075|-5.53%|47.77 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58327|0.58684|0.00075|0.58434|0.00%|0.58415|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1820dd9b61)|0.58163|0.58387|0.00066|0.58262|-0.29%|0.58253|-0.28%|43.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/c42e6d62d8)|0.57989|0.58253|0.00054|0.58118|-0.54%|0.58111|-0.52%|43.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c42e6d62d8)|0.51792|0.51962|0.00047|0.51877|-11.22%|0.51864|-11.21%|61.36 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21381|0.21921|0.00146|0.21611|0.00%|0.21586|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1820dd9b61)|0.21263|0.21709|0.00090|0.21421|-0.88%|0.21420|-0.77%|26.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/c42e6d62d8)|0.21223|0.21504|0.00077|0.21360|-1.16%|0.21349|-1.10%|26.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c42e6d62d8)|0.07372|0.07598|0.00068|0.07482|-65.38%|0.07475|-65.37%|27.77 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.43540|1.45132|0.00423|1.44247|0.00%|1.44307|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1820dd9b61)|1.34078|1.35877|0.00389|1.35053|-6.37%|1.35102|-6.38%|20.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/c42e6d62d8)|1.33558|1.35267|0.00430|1.34548|-6.72%|1.34588|-6.74%|20.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c42e6d62d8)|0.55639|0.59136|0.00703|0.57624|-60.05%|0.57627|-60.07%|22.21 MB|
