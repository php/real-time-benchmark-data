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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250211|
| GCC           |11.4.1|
| Time          |2025-02-21 00:49:30 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43801|0.45285|0.00254|0.43931|0.00%|0.43886|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bcf0ee185b)|0.43466|0.43709|0.00055|0.43547|-0.87%|0.43529|-0.81%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/0ec6413562)|0.43497|0.43766|0.00056|0.43594|-0.77%|0.43581|-0.69%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0ec6413562)|0.42304|0.42443|0.00035|0.42358|-3.58%|0.42351|-3.50%|50.78 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71228|0.71563|0.00084|0.71395|0.00%|0.71380|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bcf0ee185b)|0.70610|0.70971|0.00068|0.70713|-0.95%|0.70697|-0.96%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/0ec6413562)|0.70498|0.70942|0.00100|0.70632|-1.07%|0.70616|-1.07%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0ec6413562)|0.67154|0.68068|0.00147|0.67881|-4.92%|0.67891|-4.89%|44.54 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58066|0.58339|0.00072|0.58163|0.00%|0.58144|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bcf0ee185b)|0.57896|0.58214|0.00074|0.58016|-0.25%|0.58006|-0.24%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/0ec6413562)|0.57834|0.58058|0.00053|0.57943|-0.38%|0.57936|-0.36%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0ec6413562)|0.51904|0.52122|0.00051|0.52005|-10.59%|0.52004|-10.56%|61.90 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21523|0.21836|0.00078|0.21633|0.00%|0.21610|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bcf0ee185b)|0.21808|0.22216|0.00108|0.21974|1.58%|0.21955|1.60%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/0ec6413562)|0.21165|0.21449|0.00054|0.21243|-1.80%|0.21232|-1.75%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0ec6413562)|0.07501|0.07782|0.00068|0.07630|-64.73%|0.07633|-64.68%|27.36 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33256|1.35786|0.00598|1.34876|0.00%|1.34934|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bcf0ee185b)|1.28303|1.30085|0.00387|1.29064|-4.31%|1.28983|-4.41%|20.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/0ec6413562)|1.25643|1.27668|0.00487|1.26471|-6.23%|1.26421|-6.31%|20.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0ec6413562)|0.54570|0.57008|0.00633|0.55986|-58.49%|0.56116|-58.41%|21.78 MB|
