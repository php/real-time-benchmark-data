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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-02-27 00:49:28 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43919|0.44844|0.00153|0.44046|0.00%|0.44016|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6cd754121)|0.43653|0.44380|0.00144|0.43761|-0.65%|0.43709|-0.70%|41.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b2a70d45e)|0.43857|0.44059|0.00047|0.43948|-0.22%|0.43940|-0.17%|41.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b2a70d45e)|0.42529|0.42999|0.00082|0.42617|-3.24%|0.42602|-3.21%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71338|0.71626|0.00068|0.71462|0.00%|0.71461|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6cd754121)|0.69888|0.70900|0.00170|0.70738|-1.01%|0.70777|-0.96%|37.56 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b2a70d45e)|0.70923|0.71317|0.00096|0.71089|-0.52%|0.71054|-0.57%|37.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b2a70d45e)|0.68109|0.68493|0.00096|0.68284|-4.45%|0.68268|-4.47%|44.56 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58167|0.64880|0.02407|0.63615|0.00%|0.64736|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6cd754121)|0.57871|0.64626|0.03070|0.61369|-3.53%|0.63565|-1.81%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b2a70d45e)|0.57957|0.58171|0.00055|0.58059|-8.73%|0.58057|-10.32%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b2a70d45e)|0.52098|0.52261|0.00041|0.52173|-17.99%|0.52172|-19.41%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21592|0.21966|0.00100|0.21716|0.00%|0.21695|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6cd754121)|0.21666|0.22148|0.00107|0.21814|0.45%|0.21806|0.51%|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b2a70d45e)|0.21220|0.21609|0.00086|0.21340|-1.73%|0.21322|-1.72%|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b2a70d45e)|0.07548|0.07825|0.00076|0.07673|-64.66%|0.07660|-64.69%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33905|1.36097|0.00598|1.34911|0.00%|1.34981|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6cd754121)|1.38134|1.39627|0.00381|1.38938|2.98%|1.38919|2.92%|20.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b2a70d45e)|1.25836|1.27903|0.00477|1.26829|-5.99%|1.26713|-6.13%|20.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b2a70d45e)|0.53449|0.54771|0.00341|0.54217|-59.81%|0.54212|-59.84%|21.80 MB|
