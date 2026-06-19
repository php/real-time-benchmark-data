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
| Time          |2026-06-19 01:39:26 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27800110936 ([Artifacts](https://github.com/php/php-src/actions/runs/27800110936/artifacts/7740459374))|
| Changeset  |https://github.com/php/php-src/compare/2efafdb11d..e71b4e5928|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39828|0.40032|0.00032|0.08%|0.39876|0.00%|0.39872|0.00%|2.705|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2efafdb11d)|0.39167|0.39291|0.00028|0.07%|0.39217|-1.65%|0.39213|-1.65%|0.637|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/e71b4e5928)|0.39003|0.39186|0.00040|0.10%|0.39049|-2.07%|0.39038|-2.09%|1.741|8.614|0.000|25.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e71b4e5928)|0.36399|0.36685|0.00050|0.14%|0.36489|-8.49%|0.36484|-8.50%|1.648|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67756|0.67970|0.00046|0.07%|0.67825|0.00%|0.67814|0.00%|1.497|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2efafdb11d)|0.67126|0.67500|0.00076|0.11%|0.67216|-0.90%|0.67194|-0.91%|2.118|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/e71b4e5928)|0.66903|0.67565|0.00120|0.18%|0.67022|-1.18%|0.66973|-1.24%|2.365|8.614|0.000|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e71b4e5928)|0.63766|0.64535|0.00146|0.23%|0.63853|-5.86%|0.63809|-5.91%|3.935|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59244|0.59788|0.00115|0.19%|0.59443|0.00%|0.59433|0.00%|0.755|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2efafdb11d)|0.59097|0.59431|0.00080|0.14%|0.59184|-0.44%|0.59162|-0.46%|1.662|8.014|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/e71b4e5928)|0.58832|0.59159|0.00064|0.11%|0.58905|-0.91%|0.58890|-0.91%|2.451|8.614|0.000|25.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e71b4e5928)|0.52207|0.52874|0.00108|0.21%|0.52305|-12.01%|0.52284|-12.03%|3.785|8.614|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44325|0.44791|0.00070|0.16%|0.44466|0.00%|0.44466|0.00%|1.893|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2efafdb11d)|0.44898|0.45320|0.00068|0.15%|0.45065|1.35%|0.45059|1.33%|1.493|-8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/e71b4e5928)|0.44952|0.45208|0.00054|0.12%|0.45074|1.37%|0.45067|1.35%|0.304|-8.614|0.000|25.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e71b4e5928)|0.14451|0.14539|0.00019|0.13%|0.14486|-67.42%|0.14484|-67.43%|0.615|8.614|0.000|26.23 MB|
