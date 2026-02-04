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
| Time          |2026-02-04 00:51:57 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21653858463 ([Artifacts](https://github.com/php/php-src/actions/runs/21653858463/artifacts/5367676760))|
| Changeset  |https://github.com/php/php-src/compare/cb51737f41..27d28eef1e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40003|0.40191|0.00036|0.09%|0.40050|0.00%|0.40038|0.00%|1.903|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb51737f41)|0.39442|0.39691|0.00047|0.12%|0.39499|-1.37%|0.39484|-1.38%|1.868|8.614|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/27d28eef1e)|0.39570|0.39837|0.00053|0.13%|0.39626|-1.06%|0.39610|-1.07%|2.489|8.614|0.000|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27d28eef1e)|0.36874|0.37132|0.00061|0.16%|0.36929|-7.79%|0.36908|-7.82%|2.282|8.614|0.000|26.97 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68400|0.68927|0.00088|0.13%|0.68491|0.00%|0.68473|0.00%|3.674|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb51737f41)|0.67941|0.68135|0.00042|0.06%|0.68006|-0.71%|0.67999|-0.69%|1.442|8.614|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/27d28eef1e)|0.68576|0.69455|0.00179|0.26%|0.68824|0.49%|0.68781|0.45%|1.671|-8.104|0.000|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27d28eef1e)|0.65279|0.66174|0.00134|0.21%|0.65504|-4.36%|0.65488|-4.36%|2.514|8.614|0.000|26.97 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59705|0.60109|0.00092|0.15%|0.59928|0.00%|0.59927|0.00%|-0.193|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb51737f41)|0.59801|0.60251|0.00112|0.19%|0.59911|-0.03%|0.59875|-0.09%|1.996|2.730|0.006|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/27d28eef1e)|0.59703|0.60162|0.00094|0.16%|0.59812|-0.19%|0.59788|-0.23%|2.486|6.167|0.000|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27d28eef1e)|0.52876|0.53197|0.00060|0.11%|0.52965|-11.62%|0.52959|-11.63%|2.254|8.614|0.000|26.97 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44147|0.44417|0.00062|0.14%|0.44254|0.00%|0.44251|0.00%|0.766|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cb51737f41)|0.44383|0.44652|0.00059|0.13%|0.44472|0.49%|0.44467|0.49%|0.850|-8.500|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/27d28eef1e)|0.44195|0.44519|0.00086|0.19%|0.44361|0.24%|0.44359|0.24%|0.096|-5.925|0.000|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/27d28eef1e)|0.14306|0.14397|0.00022|0.15%|0.14361|-67.55%|0.14361|-67.55%|-0.448|8.614|0.000|26.97 MB|
