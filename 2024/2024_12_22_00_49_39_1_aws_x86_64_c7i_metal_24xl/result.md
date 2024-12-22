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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2024-12-22 00:49:39 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43945|0.45373|0.00195|0.44045|0.00%|0.44011|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/afc1f0d99b)|0.43568|0.43749|0.00047|0.43636|-0.93%|0.43623|-0.88%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/26244c7dcd)|0.43608|0.43800|0.00044|0.43711|-0.76%|0.43710|-0.69%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/26244c7dcd)|0.42712|0.42870|0.00035|0.42777|-2.88%|0.42782|-2.79%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71362|0.71722|0.00080|0.71476|0.00%|0.71448|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/afc1f0d99b)|0.70962|0.72633|0.00222|0.71169|-0.43%|0.71138|-0.43%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/26244c7dcd)|0.71261|0.71581|0.00070|0.71414|-0.09%|0.71410|-0.05%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/26244c7dcd)|0.68388|0.68717|0.00062|0.68532|-4.12%|0.68531|-4.08%|44.47 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58099|0.58363|0.00056|0.58228|0.00%|0.58240|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/afc1f0d99b)|0.57788|0.58191|0.00068|0.57918|-0.53%|0.57912|-0.56%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/26244c7dcd)|0.57493|0.58068|0.00161|0.57898|-0.57%|0.57953|-0.49%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/26244c7dcd)|0.52102|0.52308|0.00044|0.52208|-10.34%|0.52212|-10.35%|61.87 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21520|0.22052|0.00133|0.21692|0.00%|0.21668|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/afc1f0d99b)|0.21470|0.21854|0.00084|0.21620|-0.33%|0.21620|-0.22%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/26244c7dcd)|0.21557|0.21953|0.00093|0.21717|0.12%|0.21695|0.13%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/26244c7dcd)|0.07412|0.07801|0.00096|0.07573|-65.09%|0.07562|-65.10%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34036|1.37096|0.00570|1.35275|0.00%|1.35231|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/afc1f0d99b)|1.30394|1.32539|0.00554|1.31295|-2.94%|1.31271|-2.93%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/26244c7dcd)|1.33327|1.36096|0.00555|1.34541|-0.54%|1.34444|-0.58%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/26244c7dcd)|0.53786|0.55607|0.00452|0.54671|-59.59%|0.54615|-59.61%|21.65 MB|
