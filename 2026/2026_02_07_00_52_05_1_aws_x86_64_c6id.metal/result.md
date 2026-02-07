### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-07 00:52:05 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21771116027 ([Artifacts](https://github.com/php/php-src/actions/runs/21771116027/artifacts/5414447981))|
| Changeset  |https://github.com/php/php-src/compare/10fb64fed7..52e9436629|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40112|0.40339|0.00039|0.10%|0.40287|0.00%|0.40292|0.00%|-3.455|0.000|1.000|26.59 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10fb64fed7)|0.39566|0.39912|0.00070|0.18%|0.39648|-1.59%|0.39622|-1.66%|2.236|8.614|0.000|25.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/52e9436629)|0.39516|0.39701|0.00043|0.11%|0.39566|-1.79%|0.39555|-1.83%|1.462|8.614|0.000|25.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/52e9436629)|0.36858|0.37097|0.00036|0.10%|0.36916|-8.37%|0.36911|-8.39%|2.753|8.614|0.000|25.58 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68324|0.68842|0.00124|0.18%|0.68446|0.00%|0.68396|0.00%|1.917|0.000|1.000|26.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10fb64fed7)|0.68182|0.68469|0.00062|0.09%|0.68303|-0.21%|0.68293|-0.15%|0.633|7.049|0.000|25.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/52e9436629)|0.68132|0.68431|0.00071|0.10%|0.68226|-0.32%|0.68195|-0.29%|1.323|8.059|0.000|25.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/52e9436629)|0.64963|0.65132|0.00038|0.06%|0.65022|-5.00%|0.65015|-4.94%|0.917|8.614|0.000|25.67 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59278|0.59865|0.00124|0.21%|0.59473|0.00%|0.59491|0.00%|0.481|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10fb64fed7)|0.59271|0.60280|0.00144|0.24%|0.59370|-0.17%|0.59343|-0.25%|5.562|4.839|0.000|25.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/52e9436629)|0.59274|0.60376|0.00171|0.29%|0.59390|-0.14%|0.59349|-0.24%|4.404|4.029|0.000|25.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/52e9436629)|0.52313|0.52611|0.00065|0.12%|0.52398|-11.90%|0.52384|-11.95%|2.050|8.614|0.000|25.76 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44137|0.44386|0.00060|0.14%|0.44259|0.00%|0.44265|0.00%|-0.150|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10fb64fed7)|0.44225|0.44628|0.00094|0.21%|0.44381|0.28%|0.44382|0.26%|0.565|-6.366|0.000|25.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/52e9436629)|0.44140|0.44594|0.00104|0.23%|0.44357|0.22%|0.44341|0.17%|0.460|-5.053|0.000|25.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/52e9436629)|0.14305|0.14438|0.00022|0.16%|0.14356|-67.56%|0.14355|-67.57%|0.951|8.614|0.000|25.76 MB|
