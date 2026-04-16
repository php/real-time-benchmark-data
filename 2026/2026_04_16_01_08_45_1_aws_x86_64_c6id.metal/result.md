### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-04-16 01:08:45 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24486520098 ([Artifacts](https://github.com/php/php-src/actions/runs/24486520098/artifacts/6464538073))|
| Changeset  |https://github.com/php/php-src/compare/1195f271d0..f437b8b0e9|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39660|0.39886|0.00058|0.15%|0.39718|0.00%|0.39700|0.00%|1.767|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1195f271d0)|0.38811|0.38968|0.00035|0.09%|0.38855|-2.17%|0.38846|-2.15%|1.526|8.614|0.000|24.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/f437b8b0e9)|0.38778|0.38943|0.00037|0.10%|0.38824|-2.25%|0.38815|-2.23%|1.566|8.614|0.000|24.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f437b8b0e9)|0.36287|0.36552|0.00060|0.16%|0.36363|-8.45%|0.36349|-8.44%|1.477|8.614|0.000|25.41 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67047|0.67284|0.00058|0.09%|0.67133|0.00%|0.67118|0.00%|0.741|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1195f271d0)|0.66902|0.67057|0.00038|0.06%|0.66957|-0.26%|0.66945|-0.26%|0.992|8.607|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/f437b8b0e9)|0.67144|0.67657|0.00086|0.13%|0.67253|0.18%|0.67232|0.17%|2.527|-6.994|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f437b8b0e9)|0.63759|0.64306|0.00097|0.15%|0.63875|-4.85%|0.63858|-4.86%|2.967|8.614|0.000|25.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58967|0.59554|0.00121|0.20%|0.59217|0.00%|0.59207|0.00%|0.495|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1195f271d0)|0.58734|0.59187|0.00080|0.14%|0.58903|-0.53%|0.58876|-0.56%|1.613|8.283|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/f437b8b0e9)|0.58750|0.59155|0.00067|0.11%|0.58913|-0.51%|0.58906|-0.51%|0.908|8.428|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f437b8b0e9)|0.51806|0.52150|0.00079|0.15%|0.51913|-12.33%|0.51891|-12.36%|1.427|8.614|0.000|25.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44189|0.44957|0.00105|0.24%|0.44310|0.00%|0.44298|0.00%|4.850|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1195f271d0)|0.44511|0.44744|0.00056|0.13%|0.44638|0.74%|0.44642|0.78%|-0.072|-8.269|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/f437b8b0e9)|0.44532|0.44920|0.00066|0.15%|0.44631|0.73%|0.44616|0.72%|1.790|-8.269|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f437b8b0e9)|0.14312|0.14688|0.00052|0.36%|0.14358|-67.60%|0.14352|-67.60%|5.435|8.614|0.000|25.26 MB|
