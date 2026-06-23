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
| Time          |2026-06-23 01:21:31 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27995534763 ([Artifacts](https://github.com/php/php-src/actions/runs/27995534763/artifacts/7809821448))|
| Changeset  |https://github.com/php/php-src/compare/a7a3a5f1d2..e0113cd1d6|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39474|0.39695|0.00072|0.18%|0.39536|0.00%|0.39504|0.00%|1.282|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.38799|0.38910|0.00025|0.07%|0.38844|-1.75%|0.38838|-1.68%|0.928|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0113cd1d6)|0.38894|0.39071|0.00034|0.09%|0.38981|-1.40%|0.38978|-1.33%|0.406|8.614|0.000|25.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0113cd1d6)|0.36237|0.36574|0.00065|0.18%|0.36329|-8.11%|0.36309|-8.09%|1.509|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67154|0.67500|0.00061|0.09%|0.67247|0.00%|0.67232|0.00%|2.078|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.66486|0.66688|0.00057|0.09%|0.66554|-1.03%|0.66532|-1.04%|1.001|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0113cd1d6)|0.66517|0.67026|0.00090|0.14%|0.66605|-0.95%|0.66581|-0.97%|2.891|8.614|0.000|25.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0113cd1d6)|0.63715|0.64243|0.00094|0.15%|0.63825|-5.09%|0.63801|-5.10%|2.400|8.614|0.000|26.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58831|0.59276|0.00097|0.17%|0.59023|0.00%|0.59019|0.00%|0.617|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.58669|0.58879|0.00038|0.06%|0.58734|-0.49%|0.58728|-0.49%|1.215|8.600|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0113cd1d6)|0.58660|0.59028|0.00098|0.17%|0.58748|-0.47%|0.58717|-0.51%|1.911|7.787|0.000|25.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0113cd1d6)|0.51795|0.52185|0.00069|0.13%|0.51872|-12.12%|0.51851|-12.15%|2.802|8.614|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44316|0.44578|0.00055|0.12%|0.44451|0.00%|0.44442|0.00%|0.105|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.44907|0.45351|0.00074|0.16%|0.45051|1.35%|0.45038|1.34%|1.433|-8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/e0113cd1d6)|0.44866|0.45138|0.00059|0.13%|0.45038|1.32%|0.45044|1.36%|-0.585|-8.614|0.000|25.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e0113cd1d6)|0.14420|0.14491|0.00017|0.12%|0.14455|-67.48%|0.14457|-67.47%|-0.183|8.614|0.000|26.23 MB|
