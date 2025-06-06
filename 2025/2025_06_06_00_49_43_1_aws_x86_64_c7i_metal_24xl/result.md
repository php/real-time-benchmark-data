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
| OS            |Amazon Linux 2023.7.20250527|
| GCC           |11.5.0|
| Time          |2025-06-06 00:49:43 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43917|0.44828|0.00154|0.44028|0.00%|0.43999|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f91462019)|0.43857|0.44059|0.00048|0.43969|-0.13%|0.43964|-0.08%|42.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/2751064692)|0.44005|0.44183|0.00044|0.44082|0.12%|0.44080|0.18%|42.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2751064692)|0.42585|0.42707|0.00037|0.42637|-3.16%|0.42638|-3.09%|51.18 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71399|0.71572|0.00055|0.71480|0.00%|0.71474|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f91462019)|0.70857|0.71365|0.00113|0.71044|-0.61%|0.71016|-0.64%|37.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/2751064692)|0.70861|0.71285|0.00102|0.71015|-0.65%|0.70991|-0.68%|37.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2751064692)|0.67769|0.68069|0.00069|0.67899|-5.01%|0.67900|-5.00%|44.94 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58085|0.58339|0.00060|0.58174|0.00%|0.58172|0.00%|43.09 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f91462019)|0.57918|0.58138|0.00052|0.58045|-0.22%|0.58038|-0.23%|43.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/2751064692)|0.58195|0.58354|0.00037|0.58253|0.14%|0.58250|0.13%|43.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2751064692)|0.52388|0.52728|0.00056|0.52648|-9.50%|0.52658|-9.48%|61.11 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21521|0.22072|0.00130|0.21708|0.00%|0.21689|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f91462019)|0.21166|0.21621|0.00105|0.21310|-1.83%|0.21265|-1.96%|26.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/2751064692)|0.21158|0.21795|0.00120|0.21321|-1.78%|0.21300|-1.79%|26.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2751064692)|0.07435|0.07865|0.00091|0.07689|-64.58%|0.07696|-64.52%|27.70 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33971|1.35500|0.00451|1.34753|0.00%|1.34787|0.00%|20.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7f91462019)|1.29862|1.31608|0.00421|1.30520|-3.14%|1.30466|-3.21%|20.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/2751064692)|1.29203|1.30775|0.00440|1.29796|-3.68%|1.29748|-3.74%|20.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2751064692)|0.56014|0.58781|0.00581|0.57089|-57.63%|0.57156|-57.60%|22.11 MB|
