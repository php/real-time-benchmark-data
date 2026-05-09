### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-09 01:13:13 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25587376524 ([Artifacts](https://github.com/php/php-src/actions/runs/25587376524/artifacts/6891930775))|
| Changeset  |https://github.com/php/php-src/compare/8d0777e88b..eedda2a03c|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39763|0.39972|0.00044|0.11%|0.39812|0.00%|0.39801|0.00%|2.452|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d0777e88b)|0.39055|0.39361|0.00047|0.12%|0.39099|-1.79%|0.39086|-1.80%|3.891|8.614|0.000|25.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/eedda2a03c)|0.38677|0.39254|0.00074|0.19%|0.39106|-1.77%|0.39106|-1.75%|-3.616|8.614|0.000|25.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eedda2a03c)|0.36255|0.36477|0.00036|0.10%|0.36385|-8.61%|0.36383|-8.59%|-0.160|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67784|0.68253|0.00082|0.12%|0.67872|0.00%|0.67855|0.00%|3.086|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d0777e88b)|0.67138|0.67266|0.00028|0.04%|0.67182|-1.02%|0.67175|-1.00%|1.303|8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/eedda2a03c)|0.65654|0.67134|0.00199|0.30%|0.67012|-1.27%|0.67032|-1.21%|-6.736|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eedda2a03c)|0.62406|0.67879|0.00733|1.14%|0.64052|-5.63%|0.63905|-5.82%|3.640|8.393|0.000|25.40 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59473|0.59914|0.00092|0.15%|0.59693|0.00%|0.59696|0.00%|0.173|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d0777e88b)|0.59211|0.59540|0.00070|0.12%|0.59289|-0.68%|0.59265|-0.72%|1.911|8.600|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/eedda2a03c)|0.58471|0.59905|0.00157|0.26%|0.59280|-0.69%|0.59262|-0.73%|-1.482|8.276|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eedda2a03c)|0.52350|0.52558|0.00038|0.07%|0.52412|-12.20%|0.52405|-12.21%|1.569|8.614|0.000|25.41 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44155|0.44386|0.00052|0.12%|0.44290|0.00%|0.44294|0.00%|-0.474|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8d0777e88b)|0.44616|0.45028|0.00068|0.15%|0.44711|0.95%|0.44708|0.93%|2.625|-8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/eedda2a03c)|0.44561|0.44807|0.00046|0.10%|0.44687|0.90%|0.44688|0.89%|0.138|-8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eedda2a03c)|0.14368|0.14615|0.00047|0.32%|0.14424|-67.43%|0.14417|-67.45%|2.933|8.614|0.000|25.41 MB|
