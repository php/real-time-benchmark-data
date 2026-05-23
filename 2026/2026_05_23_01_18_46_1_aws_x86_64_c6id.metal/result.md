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
| Time          |2026-05-23 01:18:46 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26319582855 ([Artifacts](https://github.com/php/php-src/actions/runs/26319582855/artifacts/7173332939))|
| Changeset  |https://github.com/php/php-src/compare/c56f5ad729..e22ba55be1|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39355|0.39436|0.00017|0.04%|0.39382|0.00%|0.39382|0.00%|0.740|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c56f5ad729)|0.38469|0.38721|0.00053|0.14%|0.38526|-2.17%|0.38509|-2.22%|2.447|8.614|0.000|25.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/e22ba55be1)|0.38437|0.38786|0.00065|0.17%|0.38490|-2.26%|0.38474|-2.30%|3.765|8.614|0.000|25.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e22ba55be1)|0.35698|0.35909|0.00047|0.13%|0.35754|-9.21%|0.35741|-9.25%|1.581|8.614|0.000|25.21 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67195|0.67922|0.00113|0.17%|0.67309|0.00%|0.67275|0.00%|3.799|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c56f5ad729)|0.66873|0.67235|0.00054|0.08%|0.66940|-0.55%|0.66932|-0.51%|3.561|8.586|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/e22ba55be1)|0.66866|0.67132|0.00051|0.08%|0.66931|-0.56%|0.66923|-0.52%|2.402|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e22ba55be1)|0.63565|0.64092|0.00084|0.13%|0.63628|-5.47%|0.63611|-5.45%|4.213|8.614|0.000|25.75 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58738|0.59152|0.00101|0.17%|0.58899|0.00%|0.58869|0.00%|0.649|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c56f5ad729)|0.58395|0.58686|0.00071|0.12%|0.58477|-0.72%|0.58461|-0.69%|1.660|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/e22ba55be1)|0.58368|0.59134|0.00130|0.22%|0.58450|-0.76%|0.58418|-0.77%|4.162|8.049|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e22ba55be1)|0.51317|0.52487|0.00165|0.32%|0.51426|-12.69%|0.51393|-12.70%|5.666|8.614|0.000|25.78 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44100|0.45079|0.00126|0.29%|0.44294|0.00%|0.44281|0.00%|4.988|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c56f5ad729)|0.44897|0.45331|0.00061|0.14%|0.45050|1.71%|0.45045|1.72%|1.679|-8.352|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/e22ba55be1)|0.44935|0.45138|0.00051|0.11%|0.45022|1.64%|0.45019|1.67%|0.284|-8.324|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e22ba55be1)|0.14327|0.14594|0.00050|0.35%|0.14394|-67.50%|0.14381|-67.52%|2.616|8.614|0.000|25.78 MB|
