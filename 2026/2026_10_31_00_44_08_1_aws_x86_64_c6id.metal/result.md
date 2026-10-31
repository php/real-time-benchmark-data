### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-10-31 00:44:08 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/41151735048 ([Artifacts](https://github.com/php/php-src/actions/runs/41151735048/artifacts/13024237310))|
| Changeset  |https://github.com/php/php-src/compare/ff24cc82ea..d4f79e2ee8|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39351|0.39572|0.00064|0.16%|0.39413|0.00%|0.39387|0.00%|1.461|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff24cc82ea)|0.37486|0.37640|0.00030|0.08%|0.37532|-4.77%|0.37526|-4.72%|1.450|8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f79e2ee8)|0.37644|0.37751|0.00024|0.06%|0.37685|-4.38%|0.37683|-4.33%|0.848|8.614|0.000|26.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f79e2ee8)|0.35086|0.35315|0.00040|0.11%|0.35156|-10.80%|0.35152|-10.75%|1.914|8.614|0.000|26.32 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67169|0.68066|0.00177|0.26%|0.67274|0.00%|0.67224|0.00%|3.426|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff24cc82ea)|0.67645|0.67878|0.00046|0.07%|0.67708|0.65%|0.67692|0.70%|1.557|-7.594|0.000|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f79e2ee8)|0.67397|0.67943|0.00091|0.13%|0.67499|0.33%|0.67488|0.39%|2.918|-7.531|0.000|26.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f79e2ee8)|0.64845|0.65149|0.00053|0.08%|0.64940|-3.47%|0.64925|-3.42%|1.616|8.614|0.000|26.39 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58710|0.59084|0.00077|0.13%|0.58871|0.00%|0.58862|0.00%|0.191|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff24cc82ea)|0.59213|0.59433|0.00050|0.08%|0.59274|0.68%|0.59264|0.68%|1.815|-8.614|0.000|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f79e2ee8)|0.59161|0.59452|0.00067|0.11%|0.59236|0.62%|0.59215|0.60%|1.588|-8.614|0.000|26.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f79e2ee8)|0.51736|0.52783|0.00158|0.30%|0.51843|-11.94%|0.51803|-11.99%|4.624|8.614|0.000|26.51 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44324|0.44605|0.00065|0.15%|0.44446|0.00%|0.44439|0.00%|0.508|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff24cc82ea)|0.45278|0.45592|0.00066|0.15%|0.45473|2.31%|0.45469|2.32%|-0.313|-8.614|0.000|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/d4f79e2ee8)|0.45296|0.45609|0.00066|0.14%|0.45434|2.22%|0.45431|2.23%|0.339|-8.614|0.000|26.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d4f79e2ee8)|0.14409|0.14674|0.00057|0.39%|0.14465|-67.46%|0.14450|-67.48%|2.603|8.614|0.000|26.51 MB|
