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
| Time          |2025-07-18 00:50:08 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44066|0.45487|0.00248|0.44167|0.00%|0.44114|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e0c011fb8)|0.43813|0.44119|0.00087|0.43916|-0.57%|0.43885|-0.52%|42.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/aadd724362)|0.43884|0.44083|0.00043|0.43961|-0.47%|0.43962|-0.34%|42.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aadd724362)|0.42283|0.42455|0.00041|0.42351|-4.11%|0.42339|-4.02%|51.51 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71395|0.71712|0.00072|0.71517|0.00%|0.71504|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e0c011fb8)|0.70929|0.71358|0.00091|0.71055|-0.65%|0.71058|-0.62%|38.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/aadd724362)|0.71025|0.71310|0.00070|0.71112|-0.57%|0.71089|-0.58%|38.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aadd724362)|0.67866|0.68253|0.00093|0.67990|-4.93%|0.67978|-4.93%|45.12 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58318|0.64993|0.02592|0.63243|0.00%|0.64582|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e0c011fb8)|0.58181|0.59890|0.00292|0.58339|-7.75%|0.58289|-9.74%|43.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/aadd724362)|0.58500|0.58710|0.00053|0.58578|-7.38%|0.58567|-9.31%|43.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aadd724362)|0.52488|0.52689|0.00047|0.52566|-16.88%|0.52556|-18.62%|62.17 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21321|0.21811|0.00107|0.21561|0.00%|0.21566|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e0c011fb8)|0.21265|0.21757|0.00116|0.21417|-0.66%|0.21388|-0.82%|26.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/aadd724362)|0.25334|0.27422|0.00519|0.26217|21.60%|0.26118|21.11%|26.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aadd724362)|0.07646|0.07925|0.00066|0.07775|-63.94%|0.07757|-64.03%|27.90 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42143|1.44284|0.00518|1.42781|0.00%|1.42623|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2e0c011fb8)|1.29530|1.31485|0.00525|1.30498|-8.60%|1.30594|-8.43%|20.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/aadd724362)|1.29299|1.30950|0.00403|1.29902|-9.02%|1.29883|-8.93%|20.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aadd724362)|0.55276|0.58139|0.00783|0.57216|-59.93%|0.57439|-59.73%|22.35 MB|
