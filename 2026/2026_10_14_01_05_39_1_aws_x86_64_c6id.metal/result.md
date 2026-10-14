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
| Time          |2026-10-14 01:05:39 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/38493782024 ([Artifacts](https://github.com/php/php-src/actions/runs/38493782024/artifacts/11863703780))|
| Changeset  |https://github.com/php/php-src/compare/8db886e419..c65321c70f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39911|0.40071|0.00025|0.06%|0.39948|0.00%|0.39946|0.00%|2.493|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8db886e419)|0.37711|0.37845|0.00028|0.07%|0.37762|-5.47%|0.37757|-5.48%|1.264|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/c65321c70f)|0.37794|0.38101|0.00049|0.13%|0.37846|-5.26%|0.37834|-5.29%|3.458|8.614|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c65321c70f)|0.35557|0.35665|0.00025|0.07%|0.35592|-10.90%|0.35587|-10.91%|1.238|8.614|0.000|26.18 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68012|0.68682|0.00108|0.16%|0.68171|0.00%|0.68164|0.00%|2.201|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8db886e419)|0.67918|0.68477|0.00092|0.13%|0.68001|-0.25%|0.67977|-0.27%|3.404|7.449|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/c65321c70f)|0.67381|0.67830|0.00063|0.09%|0.67449|-1.06%|0.67435|-1.07%|4.629|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c65321c70f)|0.64083|0.64295|0.00038|0.06%|0.64142|-5.91%|0.64135|-5.91%|1.576|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59109|0.59581|0.00100|0.17%|0.59255|0.00%|0.59231|0.00%|0.973|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8db886e419)|0.59183|0.59527|0.00077|0.13%|0.59282|0.05%|0.59264|0.05%|2.110|-2.106|0.035|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/c65321c70f)|0.59188|0.59621|0.00102|0.17%|0.59289|0.06%|0.59265|0.06%|1.652|-1.875|0.061|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c65321c70f)|0.51942|0.52229|0.00048|0.09%|0.52008|-12.23%|0.51997|-12.21%|2.050|8.614|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44391|0.44789|0.00068|0.15%|0.44482|0.00%|0.44477|0.00%|1.943|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8db886e419)|0.45227|0.45634|0.00064|0.14%|0.45377|2.01%|0.45381|2.03%|0.909|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/c65321c70f)|0.45161|0.45608|0.00077|0.17%|0.45375|2.01%|0.45381|2.03%|0.090|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c65321c70f)|0.14334|0.14460|0.00027|0.19%|0.14408|-67.61%|0.14407|-67.61%|-0.022|8.614|0.000|26.21 MB|
