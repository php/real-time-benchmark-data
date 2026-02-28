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
| Time          |2026-02-28 00:50:29 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22509637559 ([Artifacts](https://github.com/php/php-src/actions/runs/22509637559/artifacts/5700077933))|
| Changeset  |https://github.com/php/php-src/compare/f46bc8e3a7..c68ede953a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39436|0.39548|0.00024|0.06%|0.39477|0.00%|0.39472|0.00%|0.822|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f46bc8e3a7)|0.38969|0.39183|0.00044|0.11%|0.39024|-1.15%|0.39013|-1.16%|1.937|8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/c68ede953a)|0.38935|0.39198|0.00044|0.11%|0.38993|-1.23%|0.38982|-1.24%|3.172|8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c68ede953a)|0.36121|0.36322|0.00034|0.09%|0.36176|-8.36%|0.36168|-8.37%|2.053|8.614|0.000|25.38 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66594|0.66845|0.00048|0.07%|0.66656|0.00%|0.66644|0.00%|1.941|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f46bc8e3a7)|0.66065|0.66247|0.00038|0.06%|0.66119|-0.81%|0.66105|-0.81%|1.211|8.614|0.000|25.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/c68ede953a)|0.66351|0.66582|0.00043|0.07%|0.66401|-0.38%|0.66391|-0.38%|1.958|8.614|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c68ede953a)|0.63325|0.63634|0.00059|0.09%|0.63394|-4.89%|0.63381|-4.90%|2.863|8.614|0.000|25.37 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58793|0.59310|0.00106|0.18%|0.58991|0.00%|0.58986|0.00%|0.804|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f46bc8e3a7)|0.58618|0.59027|0.00089|0.15%|0.58705|-0.48%|0.58680|-0.52%|2.585|7.904|0.000|25.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/c68ede953a)|0.58644|0.58940|0.00059|0.10%|0.58718|-0.46%|0.58701|-0.48%|2.330|8.400|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c68ede953a)|0.51678|0.52708|0.00148|0.29%|0.51765|-12.25%|0.51733|-12.30%|5.594|8.614|0.000|25.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44112|0.44403|0.00067|0.15%|0.44276|0.00%|0.44285|0.00%|-0.386|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f46bc8e3a7)|0.44385|0.44657|0.00054|0.12%|0.44577|0.68%|0.44584|0.67%|-1.310|-8.603|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/c68ede953a)|0.44464|0.44769|0.00058|0.13%|0.44571|0.67%|0.44568|0.64%|0.693|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c68ede953a)|0.14325|0.14470|0.00027|0.19%|0.14381|-67.52%|0.14381|-67.53%|0.725|8.614|0.000|25.32 MB|
