### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-03 00:56:00 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21612310182 ([Artifacts](https://github.com/php/php-src/actions/runs/21612310182/artifacts/5351305245))|
| Changeset  |https://github.com/php/php-src/compare/a01a8e72ac..cb51737f41|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45052|0.45273|0.00035|0.08%|0.45113|0.00%|0.45109|0.00%|1.407|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a01a8e72ac)|0.44571|0.45300|0.00083|0.19%|0.44636|-1.06%|0.44615|-1.10%|5.498|11.971|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb51737f41)|0.44568|0.45273|0.00117|0.26%|0.44651|-1.03%|0.44621|-1.08%|3.753|11.646|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb51737f41)|0.42604|0.43008|0.00050|0.12%|0.42653|-5.45%|0.42643|-5.47%|4.599|12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 250 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.73492|0.73889|0.00082|0.11%|0.73604|0.00%|0.73581|0.00%|1.577|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a01a8e72ac)|0.73284|0.74662|0.00146|0.20%|0.73439|-0.22%|0.73407|-0.24%|6.244|10.674|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb51737f41)|0.73299|0.73647|0.00067|0.09%|0.73412|-0.26%|0.73394|-0.25%|1.182|11.431|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb51737f41)|0.73612|0.74039|0.00081|0.11%|0.73757|0.21%|0.73739|0.21%|1.312|-9.974|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.64602|0.66667|0.00279|0.43%|0.64731|0.00%|0.64690|0.00%|6.694|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a01a8e72ac)|0.64944|0.66153|0.00142|0.22%|0.65054|0.50%|0.65029|0.53%|5.361|-11.727|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb51737f41)|0.64900|0.66876|0.00213|0.33%|0.65027|0.46%|0.64986|0.46%|7.001|-11.732|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb51737f41)|0.57980|0.58469|0.00097|0.17%|0.58069|-10.29%|0.58044|-10.27%|3.179|12.216|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42690|0.43363|0.00134|0.31%|0.42981|0.00%|0.42977|0.00%|0.396|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a01a8e72ac)|0.42227|0.43044|0.00152|0.36%|0.42555|-0.99%|0.42539|-1.02%|0.618|11.600|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/cb51737f41)|0.42299|0.42801|0.00116|0.27%|0.42533|-1.04%|0.42530|-1.04%|0.271|12.111|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cb51737f41)|0.13808|0.14396|0.00115|0.82%|0.14096|-67.20%|0.14085|-67.23%|0.323|12.216|0.000|27.01 MB|
