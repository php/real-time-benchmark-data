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
| Time          |2026-10-23 01:08:22 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/39882242475 ([Artifacts](https://github.com/php/php-src/actions/runs/39882242475/artifacts/12472059655))|
| Changeset  |https://github.com/php/php-src/compare/385f368057..a2bf170ee5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39916|0.40115|0.00029|0.07%|0.39955|0.00%|0.39951|0.00%|3.626|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/385f368057)|0.37973|0.38209|0.00047|0.12%|0.38029|-4.82%|0.38012|-4.85%|2.039|8.614|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/a2bf170ee5)|0.38121|0.38275|0.00031|0.08%|0.38171|-4.46%|0.38165|-4.47%|1.376|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a2bf170ee5)|0.35679|0.35863|0.00030|0.08%|0.35713|-10.62%|0.35703|-10.63%|2.845|8.614|0.000|26.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68106|0.68510|0.00092|0.13%|0.68271|0.00%|0.68252|0.00%|0.716|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/385f368057)|0.67684|0.67904|0.00044|0.07%|0.67741|-0.78%|0.67732|-0.76%|2.139|8.614|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/a2bf170ee5)|0.67781|0.68490|0.00109|0.16%|0.67870|-0.59%|0.67839|-0.61%|4.186|8.283|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a2bf170ee5)|0.64622|0.64782|0.00034|0.05%|0.64676|-5.27%|0.64670|-5.25%|1.219|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59086|0.59453|0.00084|0.14%|0.59235|0.00%|0.59228|0.00%|0.522|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/385f368057)|0.59510|0.59849|0.00065|0.11%|0.59598|0.61%|0.59577|0.59%|2.051|-8.614|0.000|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/a2bf170ee5)|0.59643|0.59863|0.00053|0.09%|0.59695|0.78%|0.59681|0.76%|1.974|-8.614|0.000|26.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a2bf170ee5)|0.52145|0.53214|0.00148|0.28%|0.52236|-11.82%|0.52210|-11.85%|6.193|8.614|0.000|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44349|0.44546|0.00045|0.10%|0.44456|0.00%|0.44458|0.00%|-0.128|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/385f368057)|0.45174|0.45447|0.00064|0.14%|0.45340|1.99%|0.45345|2.00%|-0.412|-8.614|0.000|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/a2bf170ee5)|0.45126|0.45444|0.00066|0.15%|0.45316|1.93%|0.45320|1.94%|-0.403|-8.614|0.000|26.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a2bf170ee5)|0.14393|0.14673|0.00048|0.33%|0.14460|-67.47%|0.14451|-67.50%|2.817|8.614|0.000|26.27 MB|
