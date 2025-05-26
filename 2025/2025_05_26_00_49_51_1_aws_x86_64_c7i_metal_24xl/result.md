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
| Time          |2025-05-26 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43834|0.43999|0.00037|0.43918|0.00%|0.43916|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ab80e092fb)|0.43974|0.44381|0.00089|0.44089|0.39%|0.44060|0.33%|42.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/04522cd1c4)|0.43836|0.44062|0.00056|0.43896|-0.05%|0.43876|-0.09%|42.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04522cd1c4)|0.42504|0.42650|0.00037|0.42563|-3.09%|0.42551|-3.11%|51.35 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71451|0.72994|0.00264|0.71652|0.00%|0.71580|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ab80e092fb)|0.71138|0.72293|0.00201|0.71309|-0.48%|0.71266|-0.44%|37.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/04522cd1c4)|0.71055|0.72342|0.00289|0.71316|-0.47%|0.71239|-0.48%|38.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04522cd1c4)|0.67841|0.68109|0.00066|0.67964|-5.15%|0.67963|-5.05%|45.10 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58211|0.59197|0.00225|0.58365|0.00%|0.58302|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ab80e092fb)|0.58409|0.58562|0.00046|0.58454|0.15%|0.58434|0.23%|43.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/04522cd1c4)|0.58208|0.58359|0.00042|0.58288|-0.13%|0.58290|-0.02%|43.59 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04522cd1c4)|0.52533|0.52742|0.00050|0.52620|-9.84%|0.52606|-9.77%|61.07 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21543|0.21916|0.00087|0.21695|0.00%|0.21682|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ab80e092fb)|0.21763|0.22050|0.00073|0.21881|0.86%|0.21873|0.88%|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/04522cd1c4)|0.22002|0.22317|0.00091|0.22139|2.05%|0.22121|2.02%|26.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04522cd1c4)|0.07612|0.07901|0.00060|0.07754|-64.26%|0.07747|-64.27%|27.79 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34524|1.36629|0.00529|1.35613|0.00%|1.35639|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ab80e092fb)|1.31523|1.33602|0.00432|1.32171|-2.54%|1.32161|-2.56%|20.66 MB|
|[PHP - master](https://github.com/php/php-src/commit/04522cd1c4)|1.29150|1.32233|0.00714|1.30252|-3.95%|1.30182|-4.02%|20.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/04522cd1c4)|0.54535|0.56375|0.00486|0.55662|-58.96%|0.55684|-58.95%|22.21 MB|
