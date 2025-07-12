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
| OS            |Amazon Linux 2023.8.20250707|
| GCC           |11.5.0|
| Time          |2025-07-12 00:50:00 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44069|0.45516|0.00250|0.44180|0.00%|0.44135|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f6380e4a38)|0.43820|0.43976|0.00038|0.43889|-0.66%|0.43886|-0.56%|42.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/f11ea2ae13)|0.43722|0.44013|0.00055|0.43818|-0.82%|0.43812|-0.73%|42.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f11ea2ae13)|0.42259|0.42425|0.00034|0.42321|-4.21%|0.42317|-4.12%|51.62 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71337|0.71609|0.00065|0.71466|0.00%|0.71448|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f6380e4a38)|0.71270|0.71586|0.00079|0.71422|-0.06%|0.71408|-0.06%|38.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/f11ea2ae13)|0.71149|0.71484|0.00080|0.71306|-0.22%|0.71304|-0.20%|38.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f11ea2ae13)|0.68000|0.68259|0.00065|0.68102|-4.71%|0.68081|-4.71%|45.23 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58281|0.58587|0.00066|0.58412|0.00%|0.58410|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f6380e4a38)|0.58361|0.58582|0.00057|0.58477|0.11%|0.58456|0.08%|43.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/f11ea2ae13)|0.58274|0.58461|0.00050|0.58349|-0.11%|0.58337|-0.12%|43.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f11ea2ae13)|0.52477|0.52638|0.00040|0.52554|-10.03%|0.52555|-10.02%|61.66 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21327|0.21861|0.00125|0.21556|0.00%|0.21540|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f6380e4a38)|0.21471|0.21956|0.00122|0.21650|0.44%|0.21629|0.41%|26.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/f11ea2ae13)|0.21414|0.21736|0.00085|0.21529|-0.12%|0.21525|-0.07%|26.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f11ea2ae13)|0.07703|0.07932|0.00061|0.07802|-63.81%|0.07792|-63.83%|28.03 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42006|1.43686|0.00495|1.42693|0.00%|1.42612|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f6380e4a38)|1.31570|1.32975|0.00428|1.32272|-7.30%|1.32311|-7.22%|21.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/f11ea2ae13)|1.31340|1.32789|0.00378|1.32110|-7.42%|1.32090|-7.38%|21.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f11ea2ae13)|0.54628|0.56168|0.00352|0.55476|-61.12%|0.55516|-61.07%|22.48 MB|
