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
| Time          |2026-03-07 00:51:49 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22788187095 ([Artifacts](https://github.com/php/php-src/actions/runs/22788187095/artifacts/5808312204))|
| Changeset  |https://github.com/php/php-src/compare/77925b971a..f99ca6347f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39612|0.39736|0.00020|0.05%|0.39654|0.00%|0.39651|0.00%|1.287|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/77925b971a)|0.39013|0.39171|0.00028|0.07%|0.39061|-1.49%|0.39057|-1.50%|1.559|8.614|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99ca6347f)|0.39014|0.39164|0.00033|0.08%|0.39069|-1.47%|0.39062|-1.49%|1.244|8.614|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99ca6347f)|0.36258|0.36455|0.00043|0.12%|0.36313|-8.42%|0.36303|-8.44%|1.648|8.614|0.000|25.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66940|0.67238|0.00066|0.10%|0.67023|0.00%|0.67002|0.00%|1.414|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/77925b971a)|0.66678|0.67048|0.00069|0.10%|0.66749|-0.41%|0.66726|-0.41%|2.561|8.352|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99ca6347f)|0.66664|0.66911|0.00046|0.07%|0.66735|-0.43%|0.66724|-0.42%|1.636|8.614|0.000|25.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99ca6347f)|0.63480|0.64310|0.00116|0.18%|0.63559|-5.17%|0.63539|-5.17%|5.879|8.614|0.000|25.33 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58899|0.59383|0.00119|0.20%|0.59102|0.00%|0.59104|0.00%|0.278|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/77925b971a)|0.58648|0.59100|0.00078|0.13%|0.58763|-0.57%|0.58740|-0.62%|2.689|8.304|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99ca6347f)|0.58696|0.59078|0.00081|0.14%|0.58775|-0.55%|0.58748|-0.60%|2.456|8.235|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99ca6347f)|0.51670|0.52783|0.00160|0.31%|0.51772|-12.40%|0.51739|-12.46%|5.502|8.614|0.000|25.60 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44171|0.44378|0.00053|0.12%|0.44276|0.00%|0.44272|0.00%|0.179|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/77925b971a)|0.44473|0.44804|0.00057|0.13%|0.44588|0.70%|0.44586|0.71%|1.064|-8.614|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99ca6347f)|0.44449|0.44792|0.00061|0.14%|0.44586|0.70%|0.44592|0.72%|0.557|-8.614|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99ca6347f)|0.14334|0.14427|0.00022|0.15%|0.14380|-67.52%|0.14379|-67.52%|0.270|8.614|0.000|25.60 MB|
