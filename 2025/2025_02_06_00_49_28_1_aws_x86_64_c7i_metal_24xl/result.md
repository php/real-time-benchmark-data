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
| OS            |Amazon Linux 2023.6.20250203|
| GCC           |11.4.1|
| Time          |2025-02-06 00:49:28 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43900|0.44705|0.00132|0.44013|0.00%|0.43990|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dc7161cffe)|0.43827|0.44217|0.00074|0.43937|-0.17%|0.43916|-0.17%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/cdaa69e122)|0.43724|0.44808|0.00145|0.43832|-0.41%|0.43803|-0.43%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cdaa69e122)|0.42638|0.42796|0.00036|0.42709|-2.96%|0.42710|-2.91%|50.80 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71248|0.72813|0.00213|0.71444|0.00%|0.71403|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dc7161cffe)|0.70971|0.72529|0.00219|0.71111|-0.47%|0.71062|-0.48%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/cdaa69e122)|0.71226|0.71545|0.00068|0.71348|-0.13%|0.71331|-0.10%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cdaa69e122)|0.68489|0.68786|0.00070|0.68616|-3.96%|0.68611|-3.91%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57982|0.58499|0.00077|0.58220|0.00%|0.58222|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dc7161cffe)|0.57851|0.58824|0.00147|0.58021|-0.34%|0.57988|-0.40%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/cdaa69e122)|0.57614|0.57998|0.00087|0.57799|-0.72%|0.57792|-0.74%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cdaa69e122)|0.51672|0.52277|0.00091|0.52097|-10.52%|0.52107|-10.50%|61.93 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21453|0.21843|0.00091|0.21582|0.00%|0.21563|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dc7161cffe)|0.21669|0.22042|0.00079|0.21847|1.23%|0.21837|1.27%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/cdaa69e122)|0.21494|0.21908|0.00093|0.21664|0.38%|0.21638|0.35%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cdaa69e122)|0.07332|0.07738|0.00092|0.07507|-65.22%|0.07494|-65.25%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33702|1.35576|0.00475|1.34645|0.00%|1.34634|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dc7161cffe)|1.28946|1.31041|0.00500|1.29882|-3.54%|1.29849|-3.55%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/cdaa69e122)|1.36237|1.38334|0.00531|1.37382|2.03%|1.37391|2.05%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cdaa69e122)|0.54394|0.58072|0.00869|0.56440|-58.08%|0.56417|-58.10%|21.71 MB|
