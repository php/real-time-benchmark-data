### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-09-04 01:05:10 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33824337488 ([Artifacts](https://github.com/php/php-src/actions/runs/33824337488/artifacts/9920059175))|
| Changeset  |https://github.com/php/php-src/compare/ce7896d514..0bf872bebf|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39525|0.39747|0.00033|0.08%|0.39575|0.00%|0.39576|0.00%|2.959|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ce7896d514)|0.36935|0.37127|0.00042|0.11%|0.36977|-6.56%|0.36962|-6.61%|1.771|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/0bf872bebf)|0.36940|0.37064|0.00025|0.07%|0.36971|-6.58%|0.36967|-6.59%|2.187|8.614|0.000|25.83 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67507|0.67878|0.00084|0.12%|0.67658|0.00%|0.67647|0.00%|0.578|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ce7896d514)|0.66762|0.67080|0.00062|0.09%|0.66822|-1.24%|0.66802|-1.25%|2.233|8.614|0.000|25.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/0bf872bebf)|0.66160|0.66799|0.00113|0.17%|0.66243|-2.09%|0.66205|-2.13%|3.461|8.614|0.000|25.79 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58762|0.59289|0.00103|0.17%|0.58949|0.00%|0.58936|0.00%|0.949|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ce7896d514)|0.58601|0.59081|0.00093|0.16%|0.58705|-0.41%|0.58675|-0.44%|2.779|7.876|0.000|25.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/0bf872bebf)|0.58736|0.59402|0.00122|0.21%|0.58851|-0.17%|0.58802|-0.23%|2.410|5.105|0.000|26.14 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44349|0.44573|0.00048|0.11%|0.44459|0.00%|0.44461|0.00%|-0.118|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ce7896d514)|0.45004|0.45426|0.00064|0.14%|0.45106|1.46%|0.45101|1.44%|2.456|-8.614|0.000|25.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/0bf872bebf)|0.44984|0.45212|0.00053|0.12%|0.45081|1.40%|0.45083|1.40%|0.228|-8.614|0.000|26.14 MB|
