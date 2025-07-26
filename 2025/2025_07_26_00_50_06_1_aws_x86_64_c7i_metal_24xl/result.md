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
| Kernel        |6.1.144-170.251.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250721|
| GCC           |11.5.0|
| Time          |2025-07-26 00:50:06 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43472|0.45002|0.00230|0.44062|0.00%|0.44052|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7777eaa8e1)|0.43671|0.44015|0.00079|0.43766|-0.67%|0.43745|-0.70%|42.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/747ecce51f)|0.43591|0.43834|0.00058|0.43677|-0.87%|0.43654|-0.90%|42.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/747ecce51f)|0.42285|0.42405|0.00028|0.42345|-3.90%|0.42343|-3.88%|51.45 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71621|0.71925|0.00069|0.71718|0.00%|0.71721|0.00%|37.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7777eaa8e1)|0.70944|0.71153|0.00063|0.71045|-0.94%|0.71058|-0.92%|38.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/747ecce51f)|0.70781|0.71128|0.00085|0.70896|-1.15%|0.70884|-1.17%|38.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/747ecce51f)|0.67547|0.67796|0.00061|0.67668|-5.65%|0.67667|-5.65%|45.07 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58245|0.58595|0.00078|0.58381|0.00%|0.58361|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7777eaa8e1)|0.58098|0.58389|0.00066|0.58197|-0.31%|0.58181|-0.31%|43.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/747ecce51f)|0.57950|0.58193|0.00059|0.58077|-0.52%|0.58082|-0.48%|43.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/747ecce51f)|0.52510|0.52709|0.00048|0.52611|-9.88%|0.52605|-9.86%|62.17 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21313|0.21825|0.00106|0.21541|0.00%|0.21531|0.00%|26.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7777eaa8e1)|0.21802|0.22278|0.00134|0.21995|2.11%|0.21973|2.05%|26.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/747ecce51f)|0.21736|0.22079|0.00083|0.21857|1.47%|0.21833|1.41%|26.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/747ecce51f)|0.07650|0.07873|0.00050|0.07750|-64.02%|0.07749|-64.01%|27.91 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42677|1.43977|0.00364|1.43313|0.00%|1.43244|0.00%|20.62 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7777eaa8e1)|1.28374|1.31052|0.00600|1.29647|-9.54%|1.29610|-9.52%|20.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/747ecce51f)|1.27880|1.30285|0.00656|1.28799|-10.13%|1.28677|-10.17%|20.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/747ecce51f)|0.56484|0.58607|0.00502|0.57811|-59.66%|0.57853|-59.61%|22.35 MB|
