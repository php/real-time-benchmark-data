### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-13 00:58:43 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21970433117 ([Artifacts](https://github.com/php/php-src/actions/runs/21970433117/artifacts/5493046827))|
| Changeset  |https://github.com/php/php-src/compare/7134e69ab2..7134e69ab2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40108|0.40265|0.00031|0.08%|0.40143|0.00%|0.40137|0.00%|2.149|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7134e69ab2)|0.39507|0.39765|0.00065|0.16%|0.39570|-1.43%|0.39543|-1.48%|1.309|8.614|0.000|25.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/7134e69ab2)|0.39459|0.39798|0.00057|0.14%|0.39533|-1.52%|0.39519|-1.54%|2.678|8.614|0.000|25.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7134e69ab2)|0.36760|0.37281|0.00085|0.23%|0.36834|-8.24%|0.36811|-8.29%|3.625|8.614|0.000|25.66 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68430|0.68823|0.00091|0.13%|0.68515|0.00%|0.68478|0.00%|1.922|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7134e69ab2)|0.68714|0.69048|0.00058|0.09%|0.68785|0.39%|0.68767|0.42%|2.939|-7.966|0.000|25.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/7134e69ab2)|0.68691|0.68857|0.00042|0.06%|0.68786|0.40%|0.68787|0.45%|-0.181|-8.069|0.000|25.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7134e69ab2)|0.65549|0.66114|0.00100|0.15%|0.65655|-4.17%|0.65629|-4.16%|3.395|8.614|0.000|25.73 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59722|0.60446|0.00132|0.22%|0.59922|0.00%|0.59892|0.00%|1.507|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7134e69ab2)|0.59707|0.60206|0.00103|0.17%|0.59784|-0.23%|0.59756|-0.23%|2.901|6.318|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/7134e69ab2)|0.59640|0.60755|0.00163|0.27%|0.59737|-0.31%|0.59707|-0.31%|5.373|7.552|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7134e69ab2)|0.52786|0.53727|0.00131|0.25%|0.52909|-11.70%|0.52888|-11.69%|5.354|8.614|0.000|25.83 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44127|0.44419|0.00065|0.15%|0.44263|0.00%|0.44259|0.00%|0.422|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7134e69ab2)|0.44356|0.44582|0.00058|0.13%|0.44463|0.45%|0.44462|0.46%|0.278|-8.400|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/7134e69ab2)|0.44326|0.44805|0.00075|0.17%|0.44482|0.49%|0.44470|0.48%|1.505|-8.462|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7134e69ab2)|0.14319|0.14442|0.00024|0.16%|0.14364|-67.55%|0.14361|-67.55%|0.772|8.614|0.000|25.83 MB|
