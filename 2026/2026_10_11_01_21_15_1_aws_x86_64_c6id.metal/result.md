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
| Time          |2026-10-11 01:21:15 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/38101522133 ([Artifacts](https://github.com/php/php-src/actions/runs/38101522133/artifacts/11688851964))|
| Changeset  |https://github.com/php/php-src/compare/4561d52aaf..12df767920|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39606|0.39766|0.00026|0.07%|0.39645|0.00%|0.39641|0.00%|2.146|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4561d52aaf)|0.37602|0.37714|0.00024|0.06%|0.37650|-5.03%|0.37645|-5.04%|0.418|8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/12df767920)|0.37675|0.37861|0.00031|0.08%|0.37734|-4.82%|0.37727|-4.83%|2.245|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/12df767920)|0.35309|0.35491|0.00037|0.10%|0.35370|-10.78%|0.35362|-10.79%|0.996|8.614|0.000|26.24 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67499|0.68016|0.00086|0.13%|0.67738|0.00%|0.67737|0.00%|0.252|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4561d52aaf)|0.67151|0.67414|0.00051|0.08%|0.67228|-0.75%|0.67221|-0.76%|1.057|8.614|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/12df767920)|0.66841|0.67213|0.00059|0.09%|0.66892|-1.25%|0.66879|-1.27%|3.811|8.614|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/12df767920)|0.63478|0.65649|0.00347|0.54%|0.63619|-6.08%|0.63522|-6.22%|4.647|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58901|0.59381|0.00102|0.17%|0.59076|0.00%|0.59072|0.00%|0.437|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4561d52aaf)|0.59381|0.59827|0.00083|0.14%|0.59472|0.67%|0.59455|0.65%|2.507|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/12df767920)|0.58777|0.59248|0.00108|0.18%|0.58895|-0.31%|0.58859|-0.36%|2.191|6.942|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/12df767920)|0.51664|0.52828|0.00176|0.34%|0.51780|-12.35%|0.51734|-12.42%|4.669|8.614|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44361|0.44889|0.00079|0.18%|0.44481|0.00%|0.44473|0.00%|2.737|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4561d52aaf)|0.45222|0.45480|0.00062|0.14%|0.45354|1.96%|0.45358|1.99%|-0.187|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/12df767920)|0.45056|0.45478|0.00063|0.14%|0.45193|1.60%|0.45183|1.59%|1.888|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/12df767920)|0.14351|0.14454|0.00025|0.17%|0.14411|-67.60%|0.14413|-67.59%|-0.397|8.614|0.000|26.21 MB|
