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
| Time          |2026-04-04 00:56:35 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23967796875 ([Artifacts](https://github.com/php/php-src/actions/runs/23967796875/artifacts/6267827824))|
| Changeset  |https://github.com/php/php-src/compare/660996662a..b7c855f4c2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39632|0.39866|0.00045|0.11%|0.39672|0.00%|0.39661|0.00%|2.932|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/660996662a)|0.38933|0.39073|0.00029|0.07%|0.38976|-1.75%|0.38970|-1.74%|1.787|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/b7c855f4c2)|0.38750|0.39456|0.00102|0.26%|0.38803|-2.19%|0.38782|-2.22%|5.715|8.614|0.000|25.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b7c855f4c2)|0.36106|0.36350|0.00049|0.14%|0.36177|-8.81%|0.36173|-8.79%|1.502|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66896|0.67075|0.00046|0.07%|0.66961|0.00%|0.66949|0.00%|0.940|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/660996662a)|0.66706|0.67342|0.00135|0.20%|0.66816|-0.22%|0.66776|-0.26%|2.509|6.842|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/b7c855f4c2)|0.66251|0.66414|0.00038|0.06%|0.66304|-0.98%|0.66298|-0.97%|1.005|8.614|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b7c855f4c2)|0.63456|0.63758|0.00062|0.10%|0.63519|-5.14%|0.63499|-5.15%|2.608|8.614|0.000|25.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58942|0.59459|0.00117|0.20%|0.59155|0.00%|0.59152|0.00%|0.148|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/660996662a)|0.58586|0.59328|0.00113|0.19%|0.58706|-0.76%|0.58678|-0.80%|3.638|8.283|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/b7c855f4c2)|0.58620|0.58942|0.00075|0.13%|0.58705|-0.76%|0.58679|-0.80%|2.070|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b7c855f4c2)|0.51716|0.52055|0.00062|0.12%|0.51795|-12.44%|0.51775|-12.47%|2.510|8.614|0.000|25.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44154|0.45041|0.00124|0.28%|0.44284|0.00%|0.44267|0.00%|4.738|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/660996662a)|0.44438|0.44853|0.00079|0.18%|0.44579|0.67%|0.44565|0.67%|1.415|-8.269|0.000|25.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/b7c855f4c2)|0.44478|0.44720|0.00055|0.12%|0.44599|0.71%|0.44597|0.74%|0.088|-8.269|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b7c855f4c2)|0.14323|0.14509|0.00031|0.22%|0.14375|-67.54%|0.14372|-67.53%|1.939|8.614|0.000|25.37 MB|
