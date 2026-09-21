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
| Time          |2026-09-21 01:12:29 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35550113612 ([Artifacts](https://github.com/php/php-src/actions/runs/35550113612/artifacts/10619185161))|
| Changeset  |https://github.com/php/php-src/compare/894f215ba3..1f1d223bc0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40072|0.40226|0.00024|0.06%|0.40112|0.00%|0.40107|0.00%|2.289|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/894f215ba3)|0.37755|0.37951|0.00047|0.13%|0.37803|-5.76%|0.37790|-5.78%|1.558|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/1f1d223bc0)|0.37748|0.38068|0.00054|0.14%|0.37805|-5.75%|0.37788|-5.78%|2.865|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1f1d223bc0)|0.35685|0.35833|0.00028|0.08%|0.35742|-10.90%|0.35740|-10.89%|0.892|8.614|0.000|26.26 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68292|0.68716|0.00098|0.14%|0.68462|0.00%|0.68442|0.00%|0.910|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/894f215ba3)|0.67501|0.67724|0.00045|0.07%|0.67566|-1.31%|0.67558|-1.29%|1.276|8.614|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/1f1d223bc0)|0.67207|0.67662|0.00065|0.10%|0.67271|-1.74%|0.67259|-1.73%|4.526|8.614|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1f1d223bc0)|0.64075|0.65711|0.00257|0.40%|0.64177|-6.26%|0.64123|-6.31%|5.251|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59255|0.59603|0.00083|0.14%|0.59419|0.00%|0.59407|0.00%|0.248|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/894f215ba3)|0.59052|0.59389|0.00092|0.15%|0.59166|-0.43%|0.59136|-0.46%|1.147|8.066|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/1f1d223bc0)|0.59036|0.59363|0.00070|0.12%|0.59111|-0.52%|0.59094|-0.53%|2.176|8.428|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1f1d223bc0)|0.52278|0.53322|0.00156|0.30%|0.52384|-11.84%|0.52346|-11.89%|4.811|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44374|0.45270|0.00122|0.28%|0.44499|0.00%|0.44484|0.00%|5.235|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/894f215ba3)|0.45104|0.45340|0.00050|0.11%|0.45221|1.62%|0.45227|1.67%|-0.040|-8.317|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/1f1d223bc0)|0.45145|0.45551|0.00074|0.16%|0.45241|1.67%|0.45236|1.69%|2.233|-8.345|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1f1d223bc0)|0.14460|0.14577|0.00020|0.14%|0.14513|-67.38%|0.14513|-67.37%|0.353|8.614|0.000|26.28 MB|
