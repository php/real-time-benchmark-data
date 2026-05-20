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
| Time          |2026-05-20 01:31:23 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26135498990 ([Artifacts](https://github.com/php/php-src/actions/runs/26135498990/artifacts/7099919248))|
| Changeset  |https://github.com/php/php-src/compare/d6b7bd0f77..f51c8d548d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39286|0.39379|0.00019|0.05%|0.39319|0.00%|0.39319|0.00%|0.609|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6b7bd0f77)|0.38513|0.38803|0.00064|0.17%|0.38593|-1.85%|0.38571|-1.90%|1.794|8.614|0.000|25.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/f51c8d548d)|0.38384|0.38690|0.00054|0.14%|0.38439|-2.24%|0.38423|-2.28%|2.855|8.614|0.000|25.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f51c8d548d)|0.35608|0.35803|0.00042|0.12%|0.35681|-9.25%|0.35677|-9.26%|1.251|8.614|0.000|25.21 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67091|0.67325|0.00057|0.08%|0.67179|0.00%|0.67169|0.00%|0.826|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6b7bd0f77)|0.66779|0.66935|0.00032|0.05%|0.66833|-0.51%|0.66825|-0.51%|1.339|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/f51c8d548d)|0.66720|0.67037|0.00053|0.08%|0.66783|-0.59%|0.66775|-0.59%|2.770|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f51c8d548d)|0.63367|0.65083|0.00258|0.41%|0.63477|-5.51%|0.63421|-5.58%|5.488|8.614|0.000|25.75 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58614|0.59207|0.00131|0.22%|0.58864|0.00%|0.58860|0.00%|0.459|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6b7bd0f77)|0.58443|0.58921|0.00090|0.15%|0.58537|-0.56%|0.58513|-0.59%|2.159|8.193|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/f51c8d548d)|0.58305|0.58695|0.00083|0.14%|0.58387|-0.81%|0.58360|-0.85%|1.884|8.579|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f51c8d548d)|0.51241|0.51589|0.00077|0.15%|0.51344|-12.77%|0.51328|-12.80%|1.843|8.614|0.000|25.77 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44154|0.44628|0.00072|0.16%|0.44276|0.00%|0.44269|0.00%|2.362|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d6b7bd0f77)|0.44919|0.45345|0.00067|0.15%|0.45061|1.77%|0.45059|1.79%|1.352|-8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/f51c8d548d)|0.44924|0.45139|0.00052|0.11%|0.45022|1.68%|0.45018|1.69%|0.006|-8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f51c8d548d)|0.14336|0.14586|0.00040|0.28%|0.14382|-67.52%|0.14374|-67.53%|3.806|8.614|0.000|25.78 MB|
