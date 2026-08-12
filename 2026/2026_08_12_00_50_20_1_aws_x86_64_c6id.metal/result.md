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
| Time          |2026-08-12 00:50:20 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/31551542125 ([Artifacts](https://github.com/php/php-src/actions/runs/31551542125/artifacts/9125424118))|
| Changeset  |https://github.com/php/php-src/compare/0b7f50ad2e..a95a6192f5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39610|0.39774|0.00026|0.07%|0.39657|0.00%|0.39655|0.00%|1.967|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0b7f50ad2e)|0.38576|0.38808|0.00037|0.09%|0.38631|-2.59%|0.38624|-2.60%|2.582|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/a95a6192f5)|0.37118|0.37374|0.00049|0.13%|0.37167|-6.28%|0.37151|-6.31%|2.351|8.614|0.000|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a95a6192f5)|0.34970|0.35078|0.00021|0.06%|0.35012|-11.71%|0.35011|-11.71%|0.451|8.614|0.000|25.81 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67621|0.67854|0.00050|0.07%|0.67739|0.00%|0.67740|0.00%|-0.057|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0b7f50ad2e)|0.67223|0.67604|0.00072|0.11%|0.67295|-0.66%|0.67270|-0.69%|2.415|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/a95a6192f5)|0.66741|0.66952|0.00045|0.07%|0.66822|-1.35%|0.66805|-1.38%|0.952|8.614|0.000|25.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a95a6192f5)|0.63986|0.64387|0.00070|0.11%|0.64086|-5.39%|0.64075|-5.41%|2.345|8.614|0.000|25.88 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58921|0.59265|0.00078|0.13%|0.59057|0.00%|0.59055|0.00%|0.394|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0b7f50ad2e)|0.58796|0.59066|0.00059|0.10%|0.58901|-0.26%|0.58903|-0.26%|0.403|7.683|0.000|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/a95a6192f5)|0.58927|0.59667|0.00118|0.20%|0.59033|-0.04%|0.58998|-0.10%|3.801|2.658|0.008|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a95a6192f5)|0.51779|0.52028|0.00051|0.10%|0.51848|-12.21%|0.51836|-12.22%|1.160|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44336|0.44936|0.00086|0.19%|0.44480|0.00%|0.44465|0.00%|3.275|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0b7f50ad2e)|0.44886|0.45285|0.00070|0.16%|0.45063|1.31%|0.45048|1.31%|1.089|-8.607|0.000|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/a95a6192f5)|0.44987|0.45536|0.00092|0.20%|0.45137|1.48%|0.45140|1.52%|1.643|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a95a6192f5)|0.14404|0.14497|0.00017|0.12%|0.14456|-67.50%|0.14459|-67.48%|-0.859|8.614|0.000|26.24 MB|
