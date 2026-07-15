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
| Time          |2026-07-15 00:57:39 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29380389965 ([Artifacts](https://github.com/php/php-src/actions/runs/29380389965/artifacts/8330256926))|
| Changeset  |https://github.com/php/php-src/compare/2c7c630e28..b6ebae1fbf|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39465|0.39634|0.00025|0.06%|0.39502|0.00%|0.39503|0.00%|2.780|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c7c630e28)|0.38548|0.38737|0.00039|0.10%|0.38611|-2.26%|0.38605|-2.27%|1.279|8.614|0.000|25.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/b6ebae1fbf)|0.38691|0.38826|0.00034|0.09%|0.38737|-1.94%|0.38730|-1.96%|1.080|8.614|0.000|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b6ebae1fbf)|0.36091|0.36265|0.00046|0.13%|0.36147|-8.49%|0.36132|-8.53%|1.297|8.614|0.000|25.73 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67273|0.67625|0.00085|0.13%|0.67348|0.00%|0.67308|0.00%|1.606|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c7c630e28)|0.66292|0.66654|0.00070|0.11%|0.66363|-1.46%|0.66344|-1.43%|2.583|8.614|0.000|25.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/b6ebae1fbf)|0.66675|0.66931|0.00057|0.09%|0.66736|-0.91%|0.66717|-0.88%|1.866|8.614|0.000|25.68 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b6ebae1fbf)|0.63492|0.63654|0.00034|0.05%|0.63574|-5.60%|0.63573|-5.55%|0.116|8.614|0.000|26.19 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58862|0.59256|0.00091|0.15%|0.59030|0.00%|0.59023|0.00%|0.332|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c7c630e28)|0.58251|0.58707|0.00089|0.15%|0.58336|-1.18%|0.58318|-1.19%|2.952|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/b6ebae1fbf)|0.58373|0.58723|0.00067|0.11%|0.58440|-1.00%|0.58422|-1.02%|2.971|8.614|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b6ebae1fbf)|0.51337|0.51708|0.00073|0.14%|0.51411|-12.91%|0.51396|-12.92%|3.002|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44354|0.44572|0.00049|0.11%|0.44444|0.00%|0.44440|0.00%|0.384|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2c7c630e28)|0.44918|0.45268|0.00064|0.14%|0.45067|1.40%|0.45056|1.38%|0.383|-8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/b6ebae1fbf)|0.44972|0.45243|0.00058|0.13%|0.45101|1.48%|0.45100|1.48%|0.237|-8.614|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b6ebae1fbf)|0.14392|0.14477|0.00018|0.12%|0.14441|-67.51%|0.14441|-67.50%|-0.144|8.614|0.000|26.28 MB|
