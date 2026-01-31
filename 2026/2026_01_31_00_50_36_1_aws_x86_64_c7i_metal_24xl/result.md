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
| Time          |2026-01-31 00:50:36 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21535776936 ([Artifacts](https://github.com/php/php-src/actions/runs/21535776936/artifacts/5326510138))|
| Changeset  |https://github.com/php/php-src/compare/df1a90eadc..927b9eecb6|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45094|0.45915|0.00116|0.26%|0.45197|0.00%|0.45168|0.00%|4.547|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df1a90eadc)|0.44681|0.45003|0.00071|0.16%|0.44802|-0.87%|0.44780|-0.86%|0.868|12.216|0.000|26.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/927b9eecb6)|0.44713|0.45446|0.00129|0.29%|0.44842|-0.78%|0.44803|-0.81%|2.427|11.527|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/927b9eecb6)|0.42698|0.43554|0.00103|0.24%|0.42827|-5.24%|0.42801|-5.24%|3.952|12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 250 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.73580|0.74046|0.00073|0.10%|0.73739|0.00%|0.73731|0.00%|1.247|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df1a90eadc)|0.73354|0.73886|0.00094|0.13%|0.73525|-0.29%|0.73517|-0.29%|0.993|11.166|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/927b9eecb6)|0.73344|0.74711|0.00151|0.21%|0.73524|-0.29%|0.73484|-0.34%|5.099|11.016|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/927b9eecb6)|0.73742|0.74327|0.00116|0.16%|0.73941|0.27%|0.73922|0.26%|1.057|-11.026|0.000|27.00 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.64624|0.66635|0.00198|0.31%|0.64734|0.00%|0.64711|0.00%|9.171|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df1a90eadc)|0.64997|0.67048|0.00263|0.40%|0.65140|0.63%|0.65073|0.56%|5.520|-11.974|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/927b9eecb6)|0.64853|0.66546|0.00194|0.30%|0.65006|0.42%|0.64962|0.39%|5.577|-11.971|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/927b9eecb6)|0.57940|0.59625|0.00190|0.33%|0.58061|-10.31%|0.58020|-10.34%|6.221|12.216|0.000|27.00 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42658|0.43387|0.00157|0.37%|0.42985|0.00%|0.42968|0.00%|0.497|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/df1a90eadc)|0.42454|0.43251|0.00155|0.36%|0.42736|-0.58%|0.42727|-0.56%|0.827|9.359|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/927b9eecb6)|0.42324|0.42979|0.00125|0.29%|0.42618|-0.85%|0.42617|-0.82%|0.472|11.467|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/927b9eecb6)|0.13802|0.14444|0.00138|0.98%|0.14097|-67.20%|0.14090|-67.21%|0.199|12.216|0.000|27.00 MB|
