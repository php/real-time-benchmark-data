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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-19 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44123|0.45133|0.00177|0.44228|0.00%|0.44180|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.44085|0.44430|0.00081|0.44178|-0.11%|0.44165|-0.03%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/f129586459)|0.44008|0.44154|0.00040|0.44066|-0.37%|0.44054|-0.29%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f129586459)|0.42497|0.42647|0.00037|0.42563|-3.76%|0.42556|-3.68%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71528|0.72190|0.00127|0.71688|0.00%|0.71662|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.71232|0.71564|0.00084|0.71376|-0.44%|0.71357|-0.43%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/f129586459)|0.71013|0.71499|0.00104|0.71209|-0.67%|0.71193|-0.65%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f129586459)|0.67946|0.68235|0.00069|0.68096|-5.01%|0.68099|-4.97%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58107|0.58383|0.00058|0.58258|0.00%|0.58248|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.57939|0.58229|0.00080|0.58071|-0.32%|0.58067|-0.31%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/f129586459)|0.57890|0.58229|0.00077|0.58041|-0.37%|0.58037|-0.36%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f129586459)|0.52628|0.52821|0.00039|0.52685|-9.57%|0.52679|-9.56%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21504|0.22117|0.00170|0.21728|0.00%|0.21654|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee1bbcf0bb)|0.21639|0.22019|0.00100|0.21805|0.35%|0.21787|0.61%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/f129586459)|0.21573|0.21981|0.00104|0.21720|-0.03%|0.21694|0.18%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f129586459)|0.07518|0.07845|0.00071|0.07694|-64.59%|0.07698|-64.45%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34236|1.36927|0.00609|1.35316|0.00%|1.35302|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ee1bbcf0bb)|1.32310|1.34139|0.00416|1.32913|-1.78%|1.32809|-1.84%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/f129586459)|1.30790|1.32619|0.00408|1.31693|-2.68%|1.31668|-2.69%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f129586459)|0.55234|0.58042|0.00624|0.56739|-58.07%|0.56734|-58.07%|22.23 MB|
