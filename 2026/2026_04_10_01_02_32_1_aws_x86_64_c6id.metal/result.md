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
| Time          |2026-04-10 01:02:32 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24221067620 ([Artifacts](https://github.com/php/php-src/actions/runs/24221067620/artifacts/6362882869))|
| Changeset  |https://github.com/php/php-src/compare/0f3e741b53..715645f5d7|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39438|0.39658|0.00058|0.15%|0.39512|0.00%|0.39491|0.00%|1.265|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f3e741b53)|0.38595|0.38968|0.00057|0.15%|0.38670|-2.13%|0.38656|-2.11%|3.415|8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/715645f5d7)|0.38667|0.39124|0.00072|0.19%|0.38732|-1.97%|0.38718|-1.96%|4.023|8.614|0.000|25.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/715645f5d7)|0.35859|0.36161|0.00052|0.15%|0.35917|-9.10%|0.35904|-9.08%|2.445|8.614|0.000|25.23 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66589|0.66845|0.00056|0.08%|0.66651|0.00%|0.66636|0.00%|1.409|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f3e741b53)|0.66825|0.67133|0.00049|0.07%|0.66881|0.35%|0.66872|0.35%|2.971|-8.559|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/715645f5d7)|0.66041|0.66291|0.00048|0.07%|0.66102|-0.82%|0.66092|-0.82%|1.547|8.614|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/715645f5d7)|0.63170|0.64090|0.00132|0.21%|0.63236|-5.12%|0.63210|-5.14%|5.853|8.614|0.000|25.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58768|0.59225|0.00096|0.16%|0.58971|0.00%|0.58965|0.00%|0.390|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f3e741b53)|0.58558|0.58867|0.00066|0.11%|0.58639|-0.56%|0.58621|-0.58%|2.349|8.490|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/715645f5d7)|0.58453|0.58845|0.00076|0.13%|0.58582|-0.66%|0.58554|-0.70%|2.034|8.552|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/715645f5d7)|0.51444|0.51748|0.00050|0.10%|0.51564|-12.56%|0.51555|-12.57%|1.611|8.614|0.000|25.27 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44191|0.44417|0.00062|0.14%|0.44278|0.00%|0.44276|0.00%|0.498|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0f3e741b53)|0.44469|0.44833|0.00062|0.14%|0.44597|0.72%|0.44600|0.73%|0.975|-8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/715645f5d7)|0.44452|0.44678|0.00054|0.12%|0.44565|0.65%|0.44565|0.65%|-0.013|-8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/715645f5d7)|0.14314|0.14436|0.00025|0.18%|0.14364|-67.56%|0.14359|-67.57%|0.708|8.614|0.000|25.27 MB|
