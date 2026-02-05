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
| Time          |2026-02-05 00:55:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21694420971 ([Artifacts](https://github.com/php/php-src/actions/runs/21694420971/artifacts/5383873195))|
| Changeset  |https://github.com/php/php-src/compare/27d28eef1e..06dac62747|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40066|0.40323|0.00039|0.10%|0.40214|0.00%|0.40208|0.00%|-0.488|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27d28eef1e)|0.39584|0.39925|0.00061|0.15%|0.39635|-1.44%|0.39621|-1.46%|3.083|8.614|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/06dac62747)|0.39293|0.39605|0.00061|0.15%|0.39351|-2.15%|0.39332|-2.18%|2.628|8.614|0.000|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06dac62747)|0.36732|0.36999|0.00048|0.13%|0.36805|-8.48%|0.36793|-8.49%|2.458|8.614|0.000|26.97 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68482|0.68932|0.00087|0.13%|0.68570|0.00%|0.68535|0.00%|2.218|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27d28eef1e)|0.68727|0.69276|0.00109|0.16%|0.68893|0.47%|0.68880|0.50%|1.305|-8.255|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/06dac62747)|0.68241|0.68625|0.00078|0.11%|0.68331|-0.35%|0.68301|-0.34%|1.646|8.255|0.000|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06dac62747)|0.64936|0.65125|0.00054|0.08%|0.64993|-5.22%|0.64967|-5.21%|1.004|8.614|0.000|26.97 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59647|0.60277|0.00124|0.21%|0.59842|0.00%|0.59830|0.00%|1.332|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27d28eef1e)|0.59657|0.60239|0.00127|0.21%|0.59782|-0.10%|0.59740|-0.15%|2.113|3.650|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/06dac62747)|0.59601|0.60017|0.00099|0.17%|0.59686|-0.26%|0.59663|-0.28%|2.529|6.690|0.000|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06dac62747)|0.52733|0.53028|0.00047|0.09%|0.52826|-11.72%|0.52821|-11.71%|1.983|8.614|0.000|26.97 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44133|1.67323|0.22721|46.51%|0.48846|0.00%|0.44261|0.00%|4.887|0.000|1.000|27.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27d28eef1e)|0.44101|2.05039|0.31721|62.48%|0.50769|3.94%|0.44361|0.22%|4.841|-4.829|0.000|26.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/06dac62747)|0.44146|2.04868|0.31757|62.59%|0.50738|3.87%|0.44325|0.14%|4.841|-2.727|0.006|26.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/06dac62747)|0.14315|0.61792|0.09383|57.68%|0.16267|-66.70%|0.14370|-67.53%|4.841|7.952|0.000|26.97 MB|
