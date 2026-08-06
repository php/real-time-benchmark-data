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
| Time          |2026-08-06 00:59:14 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/31061362798 ([Artifacts](https://github.com/php/php-src/actions/runs/31061362798/artifacts/8953128729))|
| Changeset  |https://github.com/php/php-src/compare/bbf82d7a84..ac37a9760b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40006|0.40255|0.00045|0.11%|0.40055|0.00%|0.40046|0.00%|3.381|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bbf82d7a84)|0.38897|0.39055|0.00030|0.08%|0.38939|-2.79%|0.38933|-2.78%|1.794|8.614|0.000|25.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac37a9760b)|0.39057|0.39251|0.00037|0.09%|0.39126|-2.32%|0.39121|-2.31%|1.748|8.614|0.000|25.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac37a9760b)|0.36632|0.36789|0.00038|0.10%|0.36690|-8.40%|0.36681|-8.40%|0.952|8.614|0.000|26.22 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67943|0.68228|0.00071|0.10%|0.68100|0.00%|0.68102|0.00%|-0.112|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bbf82d7a84)|0.67476|0.67861|0.00058|0.09%|0.67561|-0.79%|0.67546|-0.82%|2.930|8.614|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac37a9760b)|0.67794|0.68371|0.00083|0.12%|0.67889|-0.31%|0.67874|-0.34%|4.092|8.228|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac37a9760b)|0.64600|0.64932|0.00054|0.08%|0.64665|-5.04%|0.64659|-5.06%|2.726|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59260|0.59637|0.00089|0.15%|0.59414|0.00%|0.59402|0.00%|0.355|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bbf82d7a84)|0.58884|0.59763|0.00140|0.24%|0.58990|-0.71%|0.58953|-0.76%|3.852|8.269|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac37a9760b)|0.59039|0.59505|0.00076|0.13%|0.59159|-0.43%|0.59146|-0.43%|2.484|8.186|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac37a9760b)|0.52048|0.52425|0.00069|0.13%|0.52128|-12.26%|0.52109|-12.28%|1.888|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44361|0.44992|0.00103|0.23%|0.44492|0.00%|0.44473|0.00%|2.982|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bbf82d7a84)|0.44844|0.44999|0.00034|0.08%|0.44905|0.93%|0.44899|0.96%|0.608|-8.276|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac37a9760b)|0.44934|0.45234|0.00067|0.15%|0.45059|1.28%|0.45047|1.29%|0.552|-8.552|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac37a9760b)|0.14455|0.14650|0.00028|0.20%|0.14498|-67.41%|0.14497|-67.40%|3.115|8.614|0.000|26.28 MB|
