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
| Time          |2026-08-26 00:48:47 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/32916541877 ([Artifacts](https://github.com/php/php-src/actions/runs/32916541877/artifacts/9588987890))|
| Changeset  |https://github.com/php/php-src/compare/75ad0885c9..846773a4e9|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39613|0.39761|0.00027|0.07%|0.39652|0.00%|0.39649|0.00%|1.454|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75ad0885c9)|0.36993|0.37195|0.00034|0.09%|0.37037|-6.60%|0.37030|-6.61%|2.304|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/846773a4e9)|0.36914|0.37142|0.00063|0.17%|0.36975|-6.75%|0.36948|-6.81%|1.681|8.614|0.000|25.87 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67583|0.68161|0.00097|0.14%|0.67725|0.00%|0.67716|0.00%|1.997|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75ad0885c9)|0.66907|0.67108|0.00048|0.07%|0.66980|-1.10%|0.66970|-1.10%|0.844|8.614|0.000|25.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/846773a4e9)|0.66587|0.67116|0.00096|0.14%|0.66664|-1.57%|0.66637|-1.59%|3.096|8.614|0.000|25.89 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58798|0.59120|0.00086|0.15%|0.58961|0.00%|0.58957|0.00%|-0.118|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75ad0885c9)|0.58649|0.59061|0.00073|0.13%|0.58727|-0.40%|0.58707|-0.42%|3.194|8.080|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/846773a4e9)|0.58522|0.59072|0.00092|0.16%|0.58619|-0.58%|0.58597|-0.61%|3.037|8.221|0.000|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44329|0.44711|0.00069|0.15%|0.44487|0.00%|0.44478|0.00%|1.157|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75ad0885c9)|0.44999|0.45277|0.00052|0.12%|0.45128|1.44%|0.45128|1.46%|0.283|-8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/846773a4e9)|0.45021|0.45374|0.00060|0.13%|0.45164|1.52%|0.45166|1.55%|0.334|-8.614|0.000|26.25 MB|
