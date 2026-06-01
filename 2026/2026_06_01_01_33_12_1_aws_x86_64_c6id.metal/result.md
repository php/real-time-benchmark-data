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
| Time          |2026-06-01 01:33:12 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26730557284 ([Artifacts](https://github.com/php/php-src/actions/runs/26730557284/artifacts/7322328867))|
| Changeset  |https://github.com/php/php-src/compare/7092ff5387..61e679dd89|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39811|0.39925|0.00024|0.06%|0.39861|0.00%|0.39859|0.00%|0.602|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7092ff5387)|0.39015|0.39158|0.00032|0.08%|0.39069|-1.99%|0.39062|-2.00%|1.044|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/61e679dd89)|0.39035|0.39235|0.00043|0.11%|0.39086|-1.94%|0.39076|-1.96%|1.697|8.614|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61e679dd89)|0.36372|0.36515|0.00030|0.08%|0.36435|-8.60%|0.36435|-8.59%|0.413|8.614|0.000|25.82 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67744|0.67973|0.00050|0.07%|0.67820|0.00%|0.67803|0.00%|0.914|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7092ff5387)|0.67743|0.67966|0.00043|0.06%|0.67822|0.00%|0.67813|0.01%|1.047|-0.583|0.560|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/61e679dd89)|0.67709|0.68009|0.00078|0.11%|0.67817|-0.00%|0.67792|-0.02%|0.900|1.182|0.237|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61e679dd89)|0.64322|0.64539|0.00042|0.07%|0.64392|-5.05%|0.64387|-5.04%|1.265|8.614|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59240|0.59608|0.00098|0.16%|0.59416|0.00%|0.59425|0.00%|0.036|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7092ff5387)|0.59048|0.59614|0.00152|0.26%|0.59216|-0.34%|0.59148|-0.47%|1.129|5.877|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/61e679dd89)|0.59050|0.59454|0.00067|0.11%|0.59131|-0.48%|0.59119|-0.51%|2.884|8.310|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61e679dd89)|0.52027|0.52396|0.00066|0.13%|0.52123|-12.27%|0.52111|-12.31%|2.241|8.614|0.000|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44394|0.44862|0.00095|0.21%|0.44496|0.00%|0.44476|0.00%|2.468|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7092ff5387)|0.44985|0.45232|0.00059|0.13%|0.45113|1.39%|0.45120|1.45%|-0.332|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/61e679dd89)|0.44985|0.45452|0.00071|0.16%|0.45124|1.41%|0.45119|1.44%|2.006|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61e679dd89)|0.14549|0.15438|0.00139|0.95%|0.14638|-67.10%|0.14600|-67.17%|4.514|8.614|0.000|26.25 MB|
