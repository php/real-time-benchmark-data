### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-08-31 01:11:58 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33346832924 ([Artifacts](https://github.com/php/php-src/actions/runs/33346832924/artifacts/9742751084))|
| Changeset  |https://github.com/php/php-src/compare/278d290410..f142b81588|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39910|0.40102|0.00033|0.08%|0.39952|0.00%|0.39947|0.00%|2.701|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/278d290410)|0.37496|0.37672|0.00033|0.09%|0.37546|-6.02%|0.37539|-6.03%|1.701|8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/f142b81588)|0.37632|0.37986|0.00061|0.16%|0.37689|-5.67%|0.37672|-5.69%|2.963|8.614|0.000|25.88 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68062|0.68456|0.00075|0.11%|0.68239|0.00%|0.68220|0.00%|0.767|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/278d290410)|0.67082|0.67284|0.00043|0.06%|0.67149|-1.60%|0.67141|-1.58%|1.383|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/f142b81588)|0.67174|0.67702|0.00102|0.15%|0.67256|-1.44%|0.67216|-1.47%|2.758|8.614|0.000|25.90 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59077|0.59424|0.00079|0.13%|0.59203|0.00%|0.59182|0.00%|0.868|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/278d290410)|0.59107|0.59626|0.00079|0.13%|0.59211|0.01%|0.59193|0.02%|3.231|-0.886|0.376|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/f142b81588)|0.59030|0.60118|0.00191|0.32%|0.59181|-0.04%|0.59130|-0.09%|3.235|3.447|0.001|25.94 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44359|0.44584|0.00054|0.12%|0.44473|0.00%|0.44467|0.00%|0.125|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/278d290410)|0.45047|0.45421|0.00068|0.15%|0.45199|1.63%|0.45189|1.62%|0.759|-8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/f142b81588)|0.44978|0.45206|0.00056|0.12%|0.45109|1.43%|0.45117|1.46%|-0.134|-8.614|0.000|25.94 MB|
