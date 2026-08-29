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
| Time          |2026-08-29 00:57:51 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33225053603 ([Artifacts](https://github.com/php/php-src/actions/runs/33225053603/artifacts/9707017452))|
| Changeset  |https://github.com/php/php-src/compare/f16b1d5d25..ec93b0b941|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39518|0.39596|0.00017|0.04%|0.39550|0.00%|0.39549|0.00%|0.470|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f16b1d5d25)|0.37057|0.37218|0.00031|0.08%|0.37095|-6.21%|0.37092|-6.21%|1.827|8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/ec93b0b941)|0.37072|0.37299|0.00048|0.13%|0.37125|-6.13%|0.37108|-6.17%|2.053|8.614|0.000|25.88 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67456|0.67827|0.00072|0.11%|0.67579|0.00%|0.67567|0.00%|1.124|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f16b1d5d25)|0.66478|0.67130|0.00092|0.14%|0.66545|-1.53%|0.66523|-1.55%|5.454|8.614|0.000|25.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/ec93b0b941)|0.66480|0.66720|0.00039|0.06%|0.66543|-1.53%|0.66533|-1.53%|2.169|8.614|0.000|25.83 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58688|0.59054|0.00087|0.15%|0.58850|0.00%|0.58823|0.00%|0.495|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f16b1d5d25)|0.58739|0.59325|0.00118|0.20%|0.58875|0.04%|0.58847|0.04%|2.718|-1.189|0.234|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/ec93b0b941)|0.58704|0.59227|0.00094|0.16%|0.58801|-0.08%|0.58777|-0.08%|3.517|3.481|0.000|26.31 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44345|0.45255|0.00121|0.27%|0.44484|0.00%|0.44474|0.00%|5.501|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f16b1d5d25)|0.45051|0.45289|0.00054|0.12%|0.45166|1.53%|0.45157|1.54%|0.217|-8.297|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/ec93b0b941)|0.45017|0.45330|0.00074|0.16%|0.45171|1.54%|0.45170|1.57%|0.115|-8.324|0.000|26.31 MB|
