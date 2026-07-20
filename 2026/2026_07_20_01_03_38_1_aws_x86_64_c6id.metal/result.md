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
| Time          |2026-07-20 01:03:38 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29710333288 ([Artifacts](https://github.com/php/php-src/actions/runs/29710333288/artifacts/8449076554))|
| Changeset  |https://github.com/php/php-src/compare/c9bead8acb..5c4bff6578|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39483|0.39720|0.00082|0.21%|0.39562|0.00%|0.39516|0.00%|0.808|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c9bead8acb)|0.38715|0.38890|0.00031|0.08%|0.38770|-2.00%|0.38766|-1.90%|1.503|8.614|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c4bff6578)|0.38715|0.38933|0.00038|0.10%|0.38758|-2.03%|0.38749|-1.94%|2.755|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c4bff6578)|0.35727|0.35869|0.00030|0.08%|0.35789|-9.54%|0.35787|-9.44%|0.505|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67288|0.67601|0.00065|0.10%|0.67367|0.00%|0.67344|0.00%|1.716|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c9bead8acb)|0.66460|0.67000|0.00081|0.12%|0.66515|-1.26%|0.66494|-1.26%|4.729|8.614|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c4bff6578)|0.66065|0.66269|0.00040|0.06%|0.66160|-1.79%|0.66155|-1.76%|0.803|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c4bff6578)|0.63074|0.63838|0.00129|0.20%|0.63172|-6.23%|0.63150|-6.23%|4.086|8.614|0.000|26.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58830|0.59327|0.00107|0.18%|0.59063|0.00%|0.59050|0.00%|0.289|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c9bead8acb)|0.58615|0.59024|0.00090|0.15%|0.58764|-0.51%|0.58749|-0.51%|0.848|8.262|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c4bff6578)|0.58518|0.59296|0.00106|0.18%|0.58615|-0.76%|0.58588|-0.78%|5.712|8.276|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c4bff6578)|0.51416|0.51787|0.00068|0.13%|0.51515|-12.78%|0.51501|-12.79%|2.069|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44322|0.44561|0.00057|0.13%|0.44441|0.00%|0.44439|0.00%|0.110|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c9bead8acb)|0.44802|0.44945|0.00035|0.08%|0.44884|1.00%|0.44897|1.03%|-0.629|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c4bff6578)|0.44832|0.44989|0.00034|0.08%|0.44911|1.06%|0.44913|1.06%|0.104|-8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c4bff6578)|0.14406|0.14493|0.00019|0.13%|0.14450|-67.48%|0.14451|-67.48%|-0.070|8.614|0.000|26.28 MB|
