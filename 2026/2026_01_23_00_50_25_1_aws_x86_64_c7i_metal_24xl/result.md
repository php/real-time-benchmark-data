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
| Time          |2026-01-23 00:50:25 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21270412474 ([Artifacts](#ARTIFACT_URL#))|
| Changeset  |https://github.com/php/php-src/compare/65b4073922..61845cc016|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45118|0.45861|0.00096|0.21%|0.45183|0.00%|0.45168|0.00%|6.410|0.999|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b4073922)|0.44616|0.45281|0.00075|0.17%|0.44683|-1.11%|0.44668|-1.11%|5.939|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/61845cc016)|0.44618|0.45301|0.00070|0.16%|0.44677|-1.12%|0.44666|-1.11%|7.446|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61845cc016)|0.42842|0.42971|0.00024|0.06%|0.42885|-5.09%|0.42882|-5.06%|0.943|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.77326|0.78697|0.00185|0.24%|0.77486|0.00%|0.77453|0.00%|5.653|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b4073922)|0.76977|0.78312|0.00220|0.29%|0.77157|-0.43%|0.77113|-0.44%|4.411|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/61845cc016)|0.76233|0.77370|0.00184|0.24%|0.77011|-0.61%|0.77039|-0.54%|-1.505|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61845cc016)|1.11845|1.19595|0.01444|1.23%|1.17690|51.88%|1.18115|52.50%|-1.821|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65874|0.67951|0.00203|0.31%|0.65980|0.00%|0.65960|0.00%|9.398|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b4073922)|0.66432|0.68454|0.00196|0.29%|0.66563|0.88%|0.66542|0.88%|9.203|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/61845cc016)|0.66494|0.68515|0.00266|0.40%|0.66658|1.03%|0.66623|1.01%|6.710|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61845cc016)|0.59242|0.59461|0.00040|0.07%|0.59331|-10.08%|0.59330|-10.05%|0.326|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42510|0.43144|0.00131|0.31%|0.42801|0.00%|0.42794|0.00%|0.501|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/65b4073922)|0.42375|0.43067|0.00151|0.35%|0.42654|-0.34%|0.42653|-0.33%|0.533|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/61845cc016)|0.42383|0.43196|0.00151|0.35%|0.42677|-0.29%|0.42658|-0.32%|0.677|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61845cc016)|0.13837|0.14609|0.00146|1.04%|0.14067|-67.13%|0.14044|-67.18%|0.884|0.000|27.01 MB|
