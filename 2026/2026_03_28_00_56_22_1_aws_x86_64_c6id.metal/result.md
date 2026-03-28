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
| Time          |2026-03-28 00:56:22 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23673772093 ([Artifacts](https://github.com/php/php-src/actions/runs/23673772093/artifacts/6155290022))|
| Changeset  |https://github.com/php/php-src/compare/8df516c2cd..83b8a895a5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39654|0.39858|0.00054|0.14%|0.39711|0.00%|0.39694|0.00%|1.846|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8df516c2cd)|0.38967|0.39320|0.00069|0.18%|0.39147|-1.42%|0.39166|-1.33%|-1.145|8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/83b8a895a5)|0.39021|0.39284|0.00077|0.20%|0.39128|-1.47%|0.39119|-1.45%|0.236|8.614|0.000|25.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/83b8a895a5)|0.36439|0.36637|0.00039|0.11%|0.36501|-8.08%|0.36494|-8.06%|1.365|8.614|0.000|25.33 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67039|0.67366|0.00064|0.10%|0.67111|0.00%|0.67095|0.00%|1.934|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8df516c2cd)|0.66647|0.66864|0.00045|0.07%|0.66702|-0.61%|0.66690|-0.60%|1.642|8.614|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/83b8a895a5)|0.67107|0.67297|0.00039|0.06%|0.67160|0.07%|0.67153|0.09%|1.269|-5.346|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/83b8a895a5)|0.63893|0.64251|0.00052|0.08%|0.63977|-4.67%|0.63971|-4.66%|3.018|8.614|0.000|25.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59000|0.59353|0.00094|0.16%|0.59157|0.00%|0.59162|0.00%|-0.011|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8df516c2cd)|0.58601|0.59091|0.00086|0.15%|0.58733|-0.72%|0.58710|-0.76%|2.764|8.483|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/83b8a895a5)|0.58716|0.58983|0.00061|0.10%|0.58790|-0.62%|0.58778|-0.65%|2.019|8.614|0.000|25.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/83b8a895a5)|0.51680|0.52050|0.00096|0.18%|0.51787|-12.46%|0.51756|-12.52%|1.878|8.614|0.000|25.34 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44156|0.44402|0.00059|0.13%|0.44290|0.00%|0.44299|0.00%|-0.515|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8df516c2cd)|0.44376|0.44655|0.00065|0.15%|0.44524|0.53%|0.44531|0.53%|-0.059|-8.600|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/83b8a895a5)|0.44379|0.44889|0.00078|0.18%|0.44530|0.54%|0.44530|0.52%|1.622|-8.600|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/83b8a895a5)|0.14360|0.14497|0.00026|0.18%|0.14410|-67.46%|0.14409|-67.47%|0.748|8.614|0.000|25.32 MB|
