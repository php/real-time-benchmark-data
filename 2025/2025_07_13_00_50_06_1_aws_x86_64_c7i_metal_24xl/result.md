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
| Time          |2025-07-13 00:50:06 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43478|0.44138|0.00109|0.44004|0.00%|0.44017|0.00%|42.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f11ea2ae13)|0.43585|0.43755|0.00038|0.43657|-0.79%|0.43646|-0.84%|42.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/a402edac1a)|0.43478|0.43965|0.00080|0.43836|-0.38%|0.43837|-0.41%|42.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a402edac1a)|0.42097|0.42289|0.00041|0.42180|-4.14%|0.42174|-4.19%|51.62 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71290|0.71543|0.00072|0.71419|0.00%|0.71426|0.00%|37.69 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f11ea2ae13)|0.71089|0.72258|0.00198|0.71285|-0.19%|0.71244|-0.25%|38.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/a402edac1a)|0.71137|0.72352|0.00271|0.71343|-0.11%|0.71259|-0.23%|38.43 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a402edac1a)|0.67850|0.68164|0.00074|0.67984|-4.81%|0.67961|-4.85%|45.23 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58165|0.58438|0.00061|0.58307|0.00%|0.58299|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f11ea2ae13)|0.58175|0.58301|0.00037|0.58246|-0.10%|0.58245|-0.09%|43.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/a402edac1a)|0.58260|0.58573|0.00061|0.58380|0.12%|0.58378|0.14%|43.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a402edac1a)|0.52201|0.52649|0.00129|0.52475|-10.00%|0.52528|-9.90%|61.66 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21336|0.21968|0.00139|0.21545|0.00%|0.21526|0.00%|26.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f11ea2ae13)|0.21519|0.21998|0.00108|0.21656|0.52%|0.21625|0.46%|26.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/a402edac1a)|0.21314|0.21598|0.00069|0.21474|-0.33%|0.21472|-0.25%|26.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a402edac1a)|0.07671|0.07863|0.00055|0.07763|-63.97%|0.07749|-64.00%|28.03 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42225|1.43814|0.00406|1.42969|0.00%|1.42938|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f11ea2ae13)|1.31307|1.32758|0.00361|1.32020|-7.66%|1.31968|-7.67%|21.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/a402edac1a)|1.31925|1.33753|0.00585|1.32630|-7.23%|1.32431|-7.35%|21.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a402edac1a)|0.54650|0.56061|0.00305|0.55505|-61.18%|0.55486|-61.18%|22.48 MB|
