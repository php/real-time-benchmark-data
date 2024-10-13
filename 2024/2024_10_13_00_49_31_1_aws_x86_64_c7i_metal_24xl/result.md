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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20241001|
| GCC           |11.4.1|
| Time          |2024-10-13 00:49:31 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43756|0.43977|0.00051|0.43839|0.00%|0.43831|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89533482a4)|0.43522|0.44370|0.00140|0.43664|-0.40%|0.43633|-0.45%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/b2ff871e38)|0.43551|0.43795|0.00054|0.43658|-0.41%|0.43648|-0.42%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b2ff871e38)|0.42348|0.42576|0.00048|0.42434|-3.21%|0.42430|-3.20%|50.82 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71410|0.71696|0.00070|0.71557|0.00%|0.71555|0.00%|37.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89533482a4)|0.70940|0.71186|0.00053|0.71040|-0.72%|0.71034|-0.73%|37.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/b2ff871e38)|0.70955|0.71360|0.00078|0.71049|-0.71%|0.71028|-0.74%|37.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b2ff871e38)|0.68522|0.68831|0.00060|0.68679|-4.02%|0.68668|-4.03%|44.53 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57986|0.58202|0.00050|0.58094|0.00%|0.58092|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89533482a4)|0.57622|0.57889|0.00064|0.57718|-0.65%|0.57715|-0.65%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/b2ff871e38)|0.57494|0.57707|0.00050|0.57604|-0.84%|0.57594|-0.86%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b2ff871e38)|0.51862|0.52072|0.00046|0.51990|-10.51%|0.51989|-10.51%|60.86 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21454|0.21716|0.00071|0.21577|0.00%|0.21575|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89533482a4)|0.21385|0.21826|0.00118|0.21570|-0.03%|0.21554|-0.10%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/b2ff871e38)|0.21504|0.22048|0.00121|0.21642|0.30%|0.21595|0.09%|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b2ff871e38)|0.07422|0.07666|0.00054|0.07522|-65.14%|0.07522|-65.14%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34571|1.36010|0.00374|1.35346|0.00%|1.35350|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89533482a4)|1.40005|1.42910|0.00609|1.41331|4.42%|1.41309|4.40%|20.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/b2ff871e38)|1.34793|1.37985|0.00835|1.36218|0.64%|1.36295|0.70%|20.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b2ff871e38)|0.58373|0.59827|0.00392|0.59169|-56.28%|0.59186|-56.27%|21.78 MB|
