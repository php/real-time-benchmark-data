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
| Time          |2026-09-24 01:07:38 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35941517149 ([Artifacts](https://github.com/php/php-src/actions/runs/35941517149/artifacts/10785488740))|
| Changeset  |https://github.com/php/php-src/compare/10a2b0dae0..42c147ab67|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39523|0.39798|0.00038|0.10%|0.39565|0.00%|0.39560|0.00%|4.667|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10a2b0dae0)|0.37400|0.37629|0.00043|0.11%|0.37445|-5.36%|0.37433|-5.38%|2.418|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/42c147ab67)|0.37266|0.37412|0.00033|0.09%|0.37301|-5.72%|0.37292|-5.73%|1.671|8.614|0.000|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42c147ab67)|0.35038|0.35195|0.00027|0.08%|0.35101|-11.28%|0.35099|-11.28%|0.992|8.614|0.000|26.10 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67464|0.67808|0.00093|0.14%|0.67616|0.00%|0.67620|0.00%|0.208|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10a2b0dae0)|0.67008|0.67119|0.00029|0.04%|0.67059|-0.82%|0.67059|-0.83%|0.402|8.614|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/42c147ab67)|0.66690|0.66823|0.00030|0.04%|0.66757|-1.27%|0.66758|-1.27%|-0.045|8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42c147ab67)|0.63506|0.63712|0.00040|0.06%|0.63567|-5.99%|0.63558|-6.01%|1.184|8.614|0.000|26.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58690|0.59051|0.00090|0.15%|0.58859|0.00%|0.58851|0.00%|0.316|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10a2b0dae0)|0.58853|0.59166|0.00069|0.12%|0.58936|0.13%|0.58914|0.11%|1.816|-4.167|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/42c147ab67)|0.58899|0.59226|0.00074|0.13%|0.58966|0.18%|0.58946|0.16%|2.402|-5.401|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42c147ab67)|0.51905|0.52237|0.00076|0.15%|0.51978|-11.69%|0.51956|-11.72%|2.565|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44349|0.44556|0.00052|0.12%|0.44464|0.00%|0.44461|0.00%|-0.129|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/10a2b0dae0)|0.45142|0.45490|0.00078|0.17%|0.45283|1.84%|0.45281|1.85%|0.236|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/42c147ab67)|0.45142|0.45460|0.00074|0.16%|0.45285|1.85%|0.45282|1.85%|0.153|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42c147ab67)|0.14447|0.14514|0.00016|0.11%|0.14485|-67.42%|0.14485|-67.42%|-0.214|8.614|0.000|26.28 MB|
