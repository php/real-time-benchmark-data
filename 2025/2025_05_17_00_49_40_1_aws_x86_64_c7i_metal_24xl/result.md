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
| Time          |2025-05-17 00:49:40 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43894|0.44107|0.00048|0.44008|0.00%|0.44007|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3367f17f60)|0.44006|0.44242|0.00064|0.44098|0.20%|0.44091|0.19%|42.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/05618e7e0b)|0.43868|0.44155|0.00066|0.43977|-0.07%|0.43960|-0.11%|42.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/05618e7e0b)|0.42697|0.42874|0.00049|0.42772|-2.81%|0.42767|-2.82%|50.92 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71547|0.73111|0.00283|0.71697|0.00%|0.71633|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3367f17f60)|0.71024|0.72399|0.00287|0.71279|-0.58%|0.71183|-0.63%|37.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/05618e7e0b)|0.71057|0.72431|0.00293|0.71311|-0.54%|0.71244|-0.54%|37.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/05618e7e0b)|0.68521|0.68918|0.00079|0.68699|-4.18%|0.68691|-4.11%|44.69 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58129|0.58339|0.00057|0.58224|0.00%|0.58209|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3367f17f60)|0.57727|0.58345|0.00170|0.57896|-0.56%|0.57847|-0.62%|43.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/05618e7e0b)|0.58162|0.58379|0.00044|0.58244|0.04%|0.58242|0.06%|43.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/05618e7e0b)|0.52105|0.52294|0.00035|0.52198|-10.35%|0.52196|-10.33%|62.25 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21536|0.22066|0.00119|0.21720|0.00%|0.21705|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3367f17f60)|0.21825|0.22281|0.00119|0.22041|1.48%|0.22007|1.39%|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/05618e7e0b)|0.21491|0.21909|0.00099|0.21610|-0.51%|0.21583|-0.56%|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/05618e7e0b)|0.07556|0.07859|0.00085|0.07666|-64.71%|0.07634|-64.83%|27.48 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34161|1.36002|0.00423|1.34851|0.00%|1.34787|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3367f17f60)|1.29690|1.31070|0.00419|1.30295|-3.38%|1.30241|-3.37%|20.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/05618e7e0b)|1.32259|1.33494|0.00347|1.32793|-1.53%|1.32726|-1.53%|20.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/05618e7e0b)|0.52511|0.54125|0.00383|0.53246|-60.51%|0.53234|-60.50%|21.90 MB|
