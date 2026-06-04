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
| Time          |2026-06-04 01:38:18 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26924548596 ([Artifacts](https://github.com/php/php-src/actions/runs/26924548596/artifacts/7401603783))|
| Changeset  |https://github.com/php/php-src/compare/b5c17e76a2..425cd3d6a1|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39472|0.39700|0.00073|0.19%|0.39556|0.00%|0.39518|0.00%|0.766|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b5c17e76a2)|0.38625|0.38767|0.00030|0.08%|0.38684|-2.21%|0.38684|-2.11%|0.345|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/425cd3d6a1)|0.38514|0.38681|0.00043|0.11%|0.38571|-2.49%|0.38567|-2.41%|1.334|8.614|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/425cd3d6a1)|0.36153|0.36388|0.00050|0.14%|0.36220|-8.43%|0.36215|-8.36%|1.723|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67300|0.67482|0.00047|0.07%|0.67364|0.00%|0.67348|0.00%|0.970|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b5c17e76a2)|0.66546|0.66707|0.00037|0.06%|0.66613|-1.12%|0.66611|-1.09%|0.347|8.614|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/425cd3d6a1)|0.66935|0.67174|0.00046|0.07%|0.67021|-0.51%|0.67016|-0.49%|1.023|8.614|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/425cd3d6a1)|0.63768|0.65129|0.00189|0.30%|0.63859|-5.20%|0.63824|-5.23%|6.460|8.614|0.000|26.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58837|0.59380|0.00119|0.20%|0.59112|0.00%|0.59089|0.00%|0.301|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b5c17e76a2)|0.58631|0.59004|0.00080|0.14%|0.58704|-0.69%|0.58679|-0.70%|2.534|8.510|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/425cd3d6a1)|0.58683|0.59082|0.00078|0.13%|0.58752|-0.61%|0.58729|-0.61%|3.280|8.304|0.000|25.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/425cd3d6a1)|0.51582|0.51950|0.00079|0.15%|0.51671|-12.59%|0.51654|-12.58%|2.332|8.614|0.000|26.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44265|0.44579|0.00052|0.12%|0.44450|0.00%|0.44454|0.00%|-0.601|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b5c17e76a2)|0.45027|0.45458|0.00066|0.15%|0.45133|1.54%|0.45127|1.52%|2.330|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/425cd3d6a1)|0.44972|0.45316|0.00082|0.18%|0.45157|1.59%|0.45172|1.62%|-0.401|-8.614|0.000|25.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/425cd3d6a1)|0.14556|0.14942|0.00072|0.49%|0.14602|-67.15%|0.14585|-67.19%|4.391|8.614|0.000|26.26 MB|
