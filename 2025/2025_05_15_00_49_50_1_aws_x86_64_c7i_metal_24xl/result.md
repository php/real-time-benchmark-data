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
| Time          |2025-05-15 00:49:50 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43870|0.45321|0.00253|0.43977|0.00%|0.43922|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|0.43893|0.44081|0.00048|0.43986|0.02%|0.43976|0.12%|42.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/89dc8d79a7)|0.43848|0.44096|0.00062|0.43947|-0.07%|0.43939|0.04%|42.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89dc8d79a7)|0.42528|0.42743|0.00044|0.42609|-3.11%|0.42617|-2.97%|50.92 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71402|0.71797|0.00089|0.71558|0.00%|0.71541|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|0.70881|0.72189|0.00231|0.71064|-0.69%|0.70990|-0.77%|37.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/89dc8d79a7)|0.70840|0.72069|0.00215|0.70987|-0.80%|0.70959|-0.81%|37.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89dc8d79a7)|0.68509|0.68721|0.00049|0.68596|-4.14%|0.68584|-4.13%|44.68 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58081|0.59202|0.00189|0.58225|0.00%|0.58193|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|0.58096|0.58330|0.00043|0.58186|-0.07%|0.58181|-0.02%|43.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/89dc8d79a7)|0.58124|0.58373|0.00058|0.58216|-0.02%|0.58218|0.04%|43.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89dc8d79a7)|0.52129|0.52294|0.00043|0.52216|-10.32%|0.52216|-10.27%|62.24 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21551|0.21776|0.00056|0.21623|0.00%|0.21616|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|0.21854|0.22214|0.00091|0.21995|1.72%|0.21985|1.70%|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/89dc8d79a7)|0.21687|0.22176|0.00109|0.21869|1.13%|0.21858|1.12%|26.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89dc8d79a7)|0.07557|0.07803|0.00075|0.07691|-64.43%|0.07693|-64.41%|27.48 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34407|1.36609|0.00565|1.35301|0.00%|1.35348|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4122daa494)|1.29370|1.30923|0.00384|1.30188|-3.78%|1.30225|-3.79%|20.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/89dc8d79a7)|1.29220|1.30951|0.00388|1.30149|-3.81%|1.30097|-3.88%|20.57 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/89dc8d79a7)|0.54876|0.56912|0.00434|0.55998|-58.61%|0.56029|-58.60%|21.89 MB|
