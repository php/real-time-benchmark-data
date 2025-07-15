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
| Time          |2025-07-15 00:49:59 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44041|0.44810|0.00132|0.44147|0.00%|0.44123|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d9fc506df)|0.43852|0.44048|0.00056|0.43943|-0.46%|0.43934|-0.43%|42.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/142e378618)|0.43635|0.43971|0.00070|0.43722|-0.96%|0.43698|-0.96%|42.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/142e378618)|0.42513|0.42654|0.00032|0.42583|-3.54%|0.42582|-3.49%|51.58 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71363|0.71703|0.00076|0.71486|0.00%|0.71492|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d9fc506df)|0.71297|0.72453|0.00201|0.71471|-0.02%|0.71417|-0.10%|38.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/142e378618)|0.71216|0.71636|0.00106|0.71377|-0.15%|0.71344|-0.21%|38.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/142e378618)|0.68216|0.68554|0.00090|0.68358|-4.37%|0.68342|-4.41%|45.19 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58250|0.58602|0.00083|0.58460|0.00%|0.58464|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d9fc506df)|0.58361|0.58749|0.00091|0.58587|0.22%|0.58599|0.23%|43.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/142e378618)|0.58314|0.58621|0.00069|0.58477|0.03%|0.58484|0.03%|43.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/142e378618)|0.52455|0.52701|0.00062|0.52599|-10.03%|0.52602|-10.03%|62.24 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21404|0.21922|0.00119|0.21587|0.00%|0.21591|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d9fc506df)|0.21436|0.21757|0.00091|0.21605|0.08%|0.21605|0.06%|26.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/142e378618)|0.21754|0.22270|0.00107|0.21883|1.37%|0.21853|1.21%|26.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/142e378618)|0.07531|0.07967|0.00114|0.07728|-64.20%|0.07700|-64.34%|27.97 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42197|1.43967|0.00451|1.43060|0.00%|1.43123|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4d9fc506df)|1.31417|1.33895|0.00572|1.32725|-7.22%|1.32816|-7.20%|21.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/142e378618)|1.29762|1.31379|0.00377|1.30455|-8.81%|1.30476|-8.84%|21.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/142e378618)|0.54388|0.55608|0.00269|0.54852|-61.66%|0.54830|-61.69%|22.41 MB|
