### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-29 14:19:13 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21461298957 ([Artifacts](https://github.com/php/php-src/actions/runs/21461298957/artifacts/5305742571))|
| Changeset  |https://github.com/php/php-src/compare/cc50c9e928..4d5b651e90|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45033|0.45808|0.00121|0.27%|0.45116|0.00%|0.45094|0.00%|5.147|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cc50c9e928)|0.44571|0.45232|0.00136|0.30%|0.44657|-1.02%|0.44611|-1.07%|3.191|11.143|0.000|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d5b651e90)|0.44614|0.45257|0.00088|0.20%|0.44688|-0.95%|0.44663|-0.96%|3.852|11.979|0.000|26.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d5b651e90)|0.42694|0.43311|0.00084|0.20%|0.42780|-5.18%|0.42760|-5.18%|3.525|12.216|0.000|26.99 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 250 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.73419|0.73895|0.00082|0.11%|0.73608|0.00%|0.73592|0.00%|1.201|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cc50c9e928)|0.73317|0.74551|0.00168|0.23%|0.73456|-0.21%|0.73428|-0.22%|5.474|10.626|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d5b651e90)|0.73266|0.74536|0.00176|0.24%|0.73422|-0.25%|0.73386|-0.28%|5.234|10.835|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d5b651e90)|0.73659|0.74102|0.00094|0.13%|0.73817|0.28%|0.73794|0.27%|0.982|-10.976|0.000|27.00 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65916|0.67905|0.00197|0.30%|0.66037|0.00%|0.66004|0.00%|8.725|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cc50c9e928)|0.66327|0.68451|0.00294|0.44%|0.66547|0.77%|0.66483|0.73%|5.598|-11.976|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d5b651e90)|0.66252|0.67799|0.00179|0.27%|0.66414|0.57%|0.66372|0.56%|5.208|-11.971|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d5b651e90)|0.59219|0.59742|0.00108|0.18%|0.59323|-10.17%|0.59295|-10.16%|2.789|12.216|0.000|27.00 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42733|0.46417|0.00372|0.87%|0.43042|0.00%|0.42980|0.00%|7.660|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cc50c9e928)|0.42226|0.43111|0.00172|0.40%|0.42657|-0.90%|0.42664|-0.74%|0.026|10.909|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d5b651e90)|0.42472|0.43129|0.00144|0.34%|0.42745|-0.69%|0.42734|-0.57%|0.538|9.765|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d5b651e90)|0.13793|0.14476|0.00143|1.02%|0.14077|-67.29%|0.14058|-67.29%|0.511|12.216|0.000|27.00 MB|
