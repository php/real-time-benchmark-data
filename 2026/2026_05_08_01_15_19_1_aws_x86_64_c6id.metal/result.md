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
| Time          |2026-05-08 01:15:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25531020807 ([Artifacts](https://github.com/php/php-src/actions/runs/25531020807/artifacts/6870410836))|
| Changeset  |https://github.com/php/php-src/compare/0173ef4b84..8d0777e88b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39286|0.39476|0.00027|0.07%|0.39313|0.00%|0.39310|0.00%|4.454|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0173ef4b84)|0.38548|0.38732|0.00041|0.11%|0.38595|-1.83%|0.38585|-1.84%|1.451|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d0777e88b)|0.38542|0.38704|0.00035|0.09%|0.38585|-1.85%|0.38579|-1.86%|1.901|8.614|0.000|25.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d0777e88b)|0.35692|0.35931|0.00042|0.12%|0.35773|-9.01%|0.35767|-9.01%|1.888|8.614|0.000|25.51 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67137|0.67475|0.00059|0.09%|0.67195|0.00%|0.67175|0.00%|2.635|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0173ef4b84)|0.66459|0.66700|0.00057|0.09%|0.66526|-1.00%|0.66507|-0.99%|1.337|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d0777e88b)|0.66452|0.66690|0.00043|0.06%|0.66509|-1.02%|0.66500|-1.01%|2.134|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d0777e88b)|0.63067|0.63799|0.00139|0.22%|0.63168|-5.99%|0.63137|-6.01%|3.853|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58674|0.59151|0.00122|0.21%|0.58862|0.00%|0.58836|0.00%|0.719|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0173ef4b84)|0.58322|0.58560|0.00053|0.09%|0.58387|-0.81%|0.58369|-0.79%|1.120|8.614|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d0777e88b)|0.58333|0.58702|0.00076|0.13%|0.58420|-0.75%|0.58397|-0.75%|2.109|8.579|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d0777e88b)|0.51450|0.51739|0.00058|0.11%|0.51520|-12.47%|0.51503|-12.46%|1.874|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44145|0.44417|0.00064|0.14%|0.44277|0.00%|0.44283|0.00%|0.183|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0173ef4b84)|0.44603|0.44914|0.00052|0.12%|0.44701|0.96%|0.44699|0.94%|1.334|-8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/8d0777e88b)|0.44589|0.44819|0.00048|0.11%|0.44689|0.93%|0.44694|0.93%|0.119|-8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8d0777e88b)|0.14363|0.14529|0.00035|0.24%|0.14406|-67.46%|0.14400|-67.48%|2.381|8.614|0.000|25.41 MB|
