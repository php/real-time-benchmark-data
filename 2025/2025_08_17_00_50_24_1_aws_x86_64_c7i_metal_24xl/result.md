### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250808|
| GCC           |11.5.0|
| Time          |2025-08-17 00:50:24 UTC|

### Laravel 12.2.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47100|0.47479|0.00075|0.16%|0.47244|0.00%|0.47236|0.00%|1.000|46.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ca21d2e07)|0.46601|0.46895|0.00068|0.15%|0.46752|-1.04%|0.46759|-1.01%|0.001|47.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/d92675b6c1)|0.46521|0.46832|0.00065|0.14%|0.46667|-1.22%|0.46675|-1.19%|0.001|47.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d92675b6c1)|0.44999|0.45370|0.00082|0.18%|0.45203|-4.32%|0.45207|-4.30%|0.001|58.05 MB|

### Symfony 2.7.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74212|0.74833|0.00124|0.17%|0.74375|0.00%|0.74351|0.00%|1.000|28.06 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ca21d2e07)|0.73136|0.73668|0.00100|0.14%|0.73343|-1.39%|0.73336|-1.37%|0.001|27.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/d92675b6c1)|0.73267|0.74537|0.00314|0.43%|0.73568|-1.08%|0.73482|-1.17%|0.001|27.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d92675b6c1)|0.70221|0.70498|0.00069|0.10%|0.70369|-5.39%|0.70360|-5.37%|0.001|29.26 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57971|0.58520|0.00088|0.15%|0.58351|0.00%|0.58357|0.00%|1.000|43.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ca21d2e07)|0.57896|0.58192|0.00072|0.12%|0.58084|-0.46%|0.58087|-0.46%|0.001|43.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/d92675b6c1)|0.57841|0.58141|0.00067|0.11%|0.58028|-0.55%|0.58034|-0.55%|0.001|43.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d92675b6c1)|0.51619|0.51922|0.00069|0.13%|0.51780|-11.26%|0.51777|-11.27%|0.001|61.48 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21573|0.22005|0.00126|0.58%|0.21678|0.00%|0.21622|0.00%|1.000|25.35 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ca21d2e07)|0.21510|0.26618|0.01270|5.76%|0.22048|1.71%|0.21728|0.49%|0.217|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/d92675b6c1)|0.21606|0.21829|0.00077|0.36%|0.21713|0.16%|0.21734|0.52%|0.328|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d92675b6c1)|0.08315|0.08458|0.00049|0.58%|0.08387|-61.31%|0.08379|-61.25%|0.001|26.54 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.37182|1.39503|0.00674|0.49%|1.38222|0.00%|1.38097|0.00%|1.000|20.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ca21d2e07)|1.29958|1.32145|0.00550|0.42%|1.31154|-5.11%|1.31190|-5.00%|0.001|20.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/d92675b6c1)|1.30143|1.32185|0.00490|0.37%|1.31064|-5.18%|1.30998|-5.14%|0.001|20.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d92675b6c1)|0.54815|0.56757|0.00485|0.87%|0.55413|-59.91%|0.55325|-59.94%|0.001|22.30 MB|
