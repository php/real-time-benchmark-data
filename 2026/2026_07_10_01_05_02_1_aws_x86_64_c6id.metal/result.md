### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-07-10 01:05:02 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29061520924 ([Artifacts](https://github.com/php/php-src/actions/runs/29061520924/artifacts/8216319560))|
| Changeset  |https://github.com/php/php-src/compare/9dc29aafa5..c3f1015e56|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39632|0.39831|0.00034|0.09%|0.39670|0.00%|0.39662|0.00%|2.687|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9dc29aafa5)|0.38632|0.38838|0.00035|0.09%|0.38693|-2.46%|0.38684|-2.46%|1.528|8.614|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/c3f1015e56)|0.38728|0.38979|0.00038|0.10%|0.38775|-2.26%|0.38768|-2.25%|3.336|8.614|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c3f1015e56)|0.36136|0.36410|0.00059|0.16%|0.36198|-8.75%|0.36180|-8.78%|2.139|8.614|0.000|25.83 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67453|0.67752|0.00056|0.08%|0.67514|0.00%|0.67492|0.00%|1.990|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9dc29aafa5)|0.66585|0.66748|0.00044|0.07%|0.66641|-1.29%|0.66626|-1.28%|1.180|8.614|0.000|26.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/c3f1015e56)|0.67336|0.67542|0.00044|0.07%|0.67399|-0.17%|0.67391|-0.15%|1.273|7.835|0.000|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c3f1015e56)|0.63921|0.64257|0.00059|0.09%|0.64000|-5.20%|0.63988|-5.19%|2.592|8.614|0.000|26.17 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58941|0.59442|0.00121|0.20%|0.59166|0.00%|0.59157|0.00%|0.285|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9dc29aafa5)|0.58747|0.59273|0.00110|0.19%|0.58847|-0.54%|0.58823|-0.57%|2.692|7.856|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/c3f1015e56)|0.58707|0.59036|0.00060|0.10%|0.58769|-0.67%|0.58758|-0.67%|3.647|8.504|0.000|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c3f1015e56)|0.51805|0.52165|0.00079|0.15%|0.51875|-12.32%|0.51860|-12.34%|2.726|8.614|0.000|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44316|0.44558|0.00058|0.13%|0.44445|0.00%|0.44442|0.00%|0.144|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9dc29aafa5)|0.44962|0.45243|0.00060|0.13%|0.45088|1.45%|0.45090|1.46%|0.144|-8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/c3f1015e56)|0.44930|0.45285|0.00062|0.14%|0.45071|1.41%|0.45069|1.41%|0.764|-8.614|0.000|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c3f1015e56)|0.14414|0.14497|0.00019|0.13%|0.14454|-67.48%|0.14455|-67.48%|0.212|8.614|0.000|26.25 MB|
