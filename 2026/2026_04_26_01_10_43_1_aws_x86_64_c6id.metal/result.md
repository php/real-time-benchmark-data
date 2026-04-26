### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-04-26 01:10:43 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24944935321 ([Artifacts](https://github.com/php/php-src/actions/runs/24944935321/artifacts/6644118798))|
| Changeset  |https://github.com/php/php-src/compare/3291dea478..9498bc3ee1|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39979|0.40196|0.00065|0.16%|0.40059|0.00%|0.40036|0.00%|1.088|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3291dea478)|0.39281|0.39436|0.00034|0.09%|0.39328|-1.82%|0.39318|-1.79%|1.399|8.614|0.000|25.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/9498bc3ee1)|0.39161|0.39345|0.00038|0.10%|0.39199|-2.15%|0.39187|-2.12%|2.269|8.614|0.000|25.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9498bc3ee1)|0.37011|0.37253|0.00042|0.11%|0.37061|-7.48%|0.37052|-7.45%|2.536|8.614|0.000|25.35 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67375|0.67698|0.00068|0.10%|0.67447|0.00%|0.67431|0.00%|1.910|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3291dea478)|0.67494|0.67929|0.00064|0.09%|0.67566|0.18%|0.67553|0.18%|4.136|-7.359|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/9498bc3ee1)|0.66963|0.67135|0.00035|0.05%|0.67023|-0.63%|0.67015|-0.62%|1.328|8.614|0.000|25.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9498bc3ee1)|0.63891|0.64221|0.00058|0.09%|0.63963|-5.16%|0.63948|-5.16%|2.308|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59254|0.59845|0.00103|0.17%|0.59535|0.00%|0.59515|0.00%|0.334|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3291dea478)|0.59014|0.59310|0.00067|0.11%|0.59118|-0.70%|0.59102|-0.69%|1.302|8.579|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/9498bc3ee1)|0.58940|0.59276|0.00078|0.13%|0.59024|-0.86%|0.59000|-0.87%|2.112|8.593|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9498bc3ee1)|0.52015|0.52369|0.00063|0.12%|0.52112|-12.47%|0.52103|-12.45%|2.674|8.614|0.000|25.67 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44196|0.45058|0.00155|0.35%|0.44322|0.00%|0.44287|0.00%|4.051|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3291dea478)|0.44546|0.44935|0.00067|0.15%|0.44675|0.80%|0.44668|0.86%|1.054|-7.924|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/9498bc3ee1)|0.44541|0.44779|0.00061|0.14%|0.44669|0.78%|0.44668|0.86%|-0.276|-7.924|0.000|25.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9498bc3ee1)|0.14333|0.14410|0.00016|0.11%|0.14366|-67.59%|0.14366|-67.56%|0.224|8.614|0.000|25.71 MB|
