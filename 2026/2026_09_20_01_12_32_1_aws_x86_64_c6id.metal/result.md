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
| Time          |2026-09-20 01:12:32 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35480774756 ([Artifacts](https://github.com/php/php-src/actions/runs/35480774756/artifacts/10596290605))|
| Changeset  |https://github.com/php/php-src/compare/cc781b9c65..894f215ba3|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39897|0.40039|0.00022|0.06%|0.39935|0.00%|0.39933|0.00%|2.226|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cc781b9c65)|0.37458|0.37645|0.00042|0.11%|0.37509|-6.07%|0.37495|-6.11%|1.734|8.614|0.000|26.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/894f215ba3)|0.37601|0.37763|0.00048|0.13%|0.37653|-5.71%|0.37633|-5.76%|0.984|8.614|0.000|26.15 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68053|0.68486|0.00082|0.12%|0.68160|0.00%|0.68151|0.00%|1.574|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cc781b9c65)|0.67696|0.68176|0.00082|0.12%|0.67792|-0.54%|0.67779|-0.55%|2.433|8.379|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/894f215ba3)|0.67206|0.67424|0.00055|0.08%|0.67275|-1.30%|0.67259|-1.31%|1.283|8.614|0.000|26.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59130|0.59603|0.00099|0.17%|0.59328|0.00%|0.59324|0.00%|0.260|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cc781b9c65)|0.58892|0.59611|0.00109|0.18%|0.58999|-0.55%|0.58974|-0.59%|3.859|8.228|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/894f215ba3)|0.58851|0.59279|0.00085|0.14%|0.58941|-0.65%|0.58923|-0.68%|2.547|8.441|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44390|0.44825|0.00070|0.16%|0.44480|0.00%|0.44473|0.00%|2.541|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cc781b9c65)|0.45109|0.45523|0.00082|0.18%|0.45241|1.71%|0.45221|1.68%|1.329|-8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/894f215ba3)|0.45103|0.45383|0.00058|0.13%|0.45209|1.64%|0.45193|1.62%|0.768|-8.614|0.000|26.23 MB|
