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
| Time          |2026-02-22 00:56:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22267620435 ([Artifacts](https://github.com/php/php-src/actions/runs/22267620435/artifacts/5604433811))|
| Changeset  |https://github.com/php/php-src/compare/da6d890e00..da6d890e00|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39624|0.39802|0.00033|0.08%|0.39667|0.00%|0.39663|0.00%|2.302|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da6d890e00)|0.39093|0.39503|0.00077|0.20%|0.39163|-1.27%|0.39134|-1.33%|2.460|8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/da6d890e00)|0.39092|0.39299|0.00038|0.10%|0.39156|-1.29%|0.39150|-1.29%|1.375|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da6d890e00)|0.36299|0.36618|0.00049|0.14%|0.36348|-8.37%|0.36338|-8.38%|3.629|8.614|0.000|25.38 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66887|0.67367|0.00094|0.14%|0.66967|0.00%|0.66934|0.00%|3.127|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da6d890e00)|0.66119|0.66442|0.00057|0.09%|0.66181|-1.17%|0.66167|-1.15%|3.097|8.614|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/da6d890e00)|0.66125|0.66262|0.00028|0.04%|0.66186|-1.17%|0.66187|-1.12%|0.424|8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da6d890e00)|0.63031|0.65201|0.00306|0.48%|0.63138|-5.72%|0.63084|-5.75%|6.543|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58970|0.59629|0.00136|0.23%|0.59247|0.00%|0.59229|0.00%|0.364|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da6d890e00)|0.58807|0.59159|0.00059|0.10%|0.58871|-0.63%|0.58861|-0.62%|3.424|8.497|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/da6d890e00)|0.58818|0.59492|0.00117|0.20%|0.58921|-0.55%|0.58884|-0.58%|3.016|7.993|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da6d890e00)|0.51965|0.52312|0.00061|0.12%|0.52028|-12.18%|0.52018|-12.17%|3.761|8.614|0.000|25.41 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44210|0.44388|0.00049|0.11%|0.44288|0.00%|0.44276|0.00%|0.252|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da6d890e00)|0.44499|0.44898|0.00059|0.13%|0.44578|0.66%|0.44565|0.65%|3.358|-8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/da6d890e00)|0.44463|0.44912|0.00067|0.15%|0.44582|0.67%|0.44583|0.69%|2.251|-8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da6d890e00)|0.14343|0.14449|0.00021|0.14%|0.14381|-67.53%|0.14380|-67.52%|0.645|8.614|0.000|25.41 MB|
