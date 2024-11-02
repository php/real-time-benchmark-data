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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-11-02 00:49:21 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43844|0.45272|0.00193|0.43965|0.00%|0.43936|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.43660|0.43918|0.00050|0.43738|-0.52%|0.43732|-0.46%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b10cd1beb)|0.43703|0.43871|0.00036|0.43777|-0.43%|0.43774|-0.37%|41.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b10cd1beb)|0.42674|0.42813|0.00034|0.42732|-2.80%|0.42733|-2.74%|50.85 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71985|0.72451|0.00086|0.72153|0.00%|0.72147|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.71361|0.71716|0.00072|0.71518|-0.88%|0.71510|-0.88%|37.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b10cd1beb)|0.71609|0.73291|0.00232|0.71777|-0.52%|0.71746|-0.56%|37.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b10cd1beb)|0.69319|0.69595|0.00061|0.69446|-3.75%|0.69435|-3.76%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57795|0.58365|0.00121|0.58234|0.00%|0.58254|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.57753|0.58089|0.00083|0.57947|-0.49%|0.57955|-0.51%|42.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b10cd1beb)|0.58302|0.58532|0.00048|0.58401|0.29%|0.58398|0.25%|43.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b10cd1beb)|0.52287|0.52516|0.00044|0.52396|-10.03%|0.52396|-10.05%|61.99 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21468|0.21856|0.00090|0.21649|0.00%|0.21625|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a5ef4bb3f)|0.21490|0.21867|0.00093|0.21665|0.08%|0.21655|0.14%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b10cd1beb)|0.21715|0.22332|0.00106|0.21833|0.85%|0.21801|0.82%|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b10cd1beb)|0.07279|0.07726|0.00092|0.07464|-65.52%|0.07456|-65.52%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34282|1.36549|0.00519|1.35309|0.00%|1.35209|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1a5ef4bb3f)|1.34109|1.36308|0.00531|1.35052|-0.19%|1.35061|-0.11%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/2b10cd1beb)|1.27018|1.28787|0.00373|1.27895|-5.48%|1.27895|-5.41%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2b10cd1beb)|0.53136|0.55780|0.00461|0.54646|-59.61%|0.54628|-59.60%|21.80 MB|
