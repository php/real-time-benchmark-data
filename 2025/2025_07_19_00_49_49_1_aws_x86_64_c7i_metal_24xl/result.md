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
| Kernel        |6.1.141-165.249.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250715|
| GCC           |11.5.0|
| Time          |2025-07-19 00:49:49 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43782|0.45510|0.00270|0.44099|0.00%|0.44059|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aadd724362)|0.43810|0.43968|0.00042|0.43870|-0.52%|0.43864|-0.44%|42.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/189b933dd4)|0.43824|0.44106|0.00048|0.43939|-0.36%|0.43934|-0.29%|42.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/189b933dd4)|0.42300|0.42447|0.00032|0.42368|-3.93%|0.42372|-3.83%|51.52 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71239|0.71618|0.00087|0.71394|0.00%|0.71379|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aadd724362)|0.70919|0.72167|0.00242|0.71122|-0.38%|0.71069|-0.43%|38.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/189b933dd4)|0.71096|0.71670|0.00162|0.71331|-0.09%|0.71263|-0.16%|38.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/189b933dd4)|0.68079|0.68503|0.00088|0.68161|-4.53%|0.68138|-4.54%|45.13 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58256|0.58499|0.00067|0.58355|0.00%|0.58353|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aadd724362)|0.58303|0.58566|0.00066|0.58444|0.15%|0.58459|0.18%|43.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/189b933dd4)|0.58320|0.58595|0.00074|0.58424|0.12%|0.58397|0.07%|43.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/189b933dd4)|0.52433|0.52629|0.00049|0.52520|-10.00%|0.52522|-9.99%|62.17 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21326|0.21821|0.00135|0.21581|0.00%|0.21581|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aadd724362)|0.21443|0.21800|0.00090|0.21590|0.04%|0.21584|0.01%|26.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/189b933dd4)|0.21611|0.21934|0.00079|0.21758|0.82%|0.21756|0.81%|26.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/189b933dd4)|0.07679|0.07873|0.00049|0.07767|-64.01%|0.07743|-64.12%|27.91 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42512|1.44017|0.00415|1.43092|0.00%|1.43003|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/aadd724362)|1.28774|1.31142|0.00632|1.29989|-9.16%|1.29948|-9.13%|20.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/189b933dd4)|1.31591|1.33143|0.00342|1.32508|-7.40%|1.32503|-7.34%|20.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/189b933dd4)|0.55862|0.59100|0.00657|0.57620|-59.73%|0.57670|-59.67%|22.35 MB|
