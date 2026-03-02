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
| Time          |2026-03-02 00:55:08 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22557057026 ([Artifacts](https://github.com/php/php-src/actions/runs/22557057026/artifacts/5714167790))|
| Changeset  |https://github.com/php/php-src/compare/2fd3433ed0..2fd3433ed0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39660|0.39799|0.00022|0.06%|0.39692|0.00%|0.39689|0.00%|2.367|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2fd3433ed0)|0.39155|0.39367|0.00036|0.09%|0.39205|-1.23%|0.39197|-1.24%|2.622|8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/2fd3433ed0)|0.39176|0.39333|0.00040|0.10%|0.39223|-1.18%|0.39212|-1.20%|1.132|8.614|0.000|25.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2fd3433ed0)|0.36384|0.36626|0.00037|0.10%|0.36439|-8.20%|0.36430|-8.21%|2.878|8.614|0.000|25.32 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66995|0.67310|0.00070|0.10%|0.67073|0.00%|0.67050|0.00%|1.706|0.000|1.000|26.72 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2fd3433ed0)|0.66705|0.67393|0.00100|0.15%|0.66770|-0.45%|0.66751|-0.45%|5.310|8.269|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/2fd3433ed0)|0.66703|0.67103|0.00082|0.12%|0.66774|-0.45%|0.66744|-0.46%|2.618|8.200|0.000|25.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2fd3433ed0)|0.63718|0.65184|0.00206|0.32%|0.63807|-4.87%|0.63759|-4.91%|6.347|8.614|0.000|25.35 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59429|0.59871|0.00103|0.17%|0.59606|0.00%|0.59595|0.00%|0.407|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2fd3433ed0)|0.59258|0.59573|0.00058|0.10%|0.59327|-0.47%|0.59321|-0.46%|2.475|8.400|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/2fd3433ed0)|0.59266|0.59595|0.00064|0.11%|0.59336|-0.45%|0.59322|-0.46%|2.963|8.228|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2fd3433ed0)|0.52357|0.53430|0.00147|0.28%|0.52442|-12.02%|0.52413|-12.05%|6.477|8.614|0.000|25.32 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44139|0.44417|0.00059|0.13%|0.44280|0.00%|0.44286|0.00%|-0.192|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2fd3433ed0)|0.44428|0.44655|0.00056|0.13%|0.44561|0.64%|0.44568|0.64%|-0.403|-8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/2fd3433ed0)|0.44474|0.44866|0.00073|0.16%|0.44587|0.69%|0.44584|0.67%|1.721|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2fd3433ed0)|0.14351|0.14554|0.00031|0.22%|0.14396|-67.49%|0.14393|-67.50%|2.835|8.614|0.000|25.32 MB|
