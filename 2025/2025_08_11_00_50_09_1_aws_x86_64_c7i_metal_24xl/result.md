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
| Time          |2025-08-11 00:50:09 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46927|0.48131|0.00182|0.47253|0.00%|0.47214|0.00%|43.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e990b691c5)|0.46816|0.46958|0.00040|0.46885|-0.78%|0.46883|-0.70%|43.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/8f1a627e79)|0.46837|0.47422|0.00097|0.46953|-0.63%|0.46932|-0.60%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8f1a627e79)|0.45172|0.45311|0.00035|0.45247|-4.25%|0.45244|-4.17%|53.80 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73117|0.74898|0.00251|0.74188|0.00%|0.74174|0.00%|39.94 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e990b691c5)|0.73045|0.73838|0.00172|0.73233|-1.29%|0.73194|-1.32%|40.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/8f1a627e79)|0.72971|0.73767|0.00199|0.73175|-1.37%|0.73123|-1.42%|40.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8f1a627e79)|0.69440|0.70626|0.00178|0.70215|-5.36%|0.70214|-5.34%|47.78 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57857|0.58407|0.00194|0.58116|0.00%|0.58028|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e990b691c5)|0.58102|0.58360|0.00055|0.58207|0.16%|0.58202|0.30%|43.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/8f1a627e79)|0.58088|0.58279|0.00048|0.58177|0.11%|0.58173|0.25%|43.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8f1a627e79)|0.51710|0.51951|0.00065|0.51817|-10.84%|0.51822|-10.69%|61.37 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21484|0.21836|0.00095|0.21631|0.00%|0.21613|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e990b691c5)|0.21395|0.21788|0.00097|0.21535|-0.45%|0.21517|-0.45%|26.49 MB|
|[PHP - master](https://github.com/php/php-src/commit/8f1a627e79)|0.21265|0.21699|0.00109|0.21466|-0.77%|0.21468|-0.67%|26.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8f1a627e79)|0.07347|0.07548|0.00046|0.07446|-65.58%|0.07438|-65.58%|27.72 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42518|1.44002|0.00415|1.43341|0.00%|1.43349|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e990b691c5)|1.32527|1.34151|0.00373|1.33214|-7.06%|1.33161|-7.11%|20.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/8f1a627e79)|1.29940|1.31197|0.00294|1.30600|-8.89%|1.30622|-8.88%|20.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8f1a627e79)|0.54195|0.56112|0.00510|0.55243|-61.46%|0.55252|-61.46%|22.16 MB|
