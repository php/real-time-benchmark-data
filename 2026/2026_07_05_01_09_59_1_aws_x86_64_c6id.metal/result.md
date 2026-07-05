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
| Time          |2026-07-05 01:09:59 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28725273006 ([Artifacts](https://github.com/php/php-src/actions/runs/28725273006/artifacts/8087398961))|
| Changeset  |https://github.com/php/php-src/compare/19f94430d5..dcfa40cccf|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39823|0.40040|0.00072|0.18%|0.39887|0.00%|0.39858|0.00%|1.376|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/19f94430d5)|0.38926|0.39108|0.00035|0.09%|0.39001|-2.22%|0.38998|-2.16%|1.031|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/dcfa40cccf)|0.38973|0.39204|0.00043|0.11%|0.39053|-2.09%|0.39046|-2.04%|1.164|8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dcfa40cccf)|0.36385|0.36709|0.00065|0.18%|0.36477|-8.55%|0.36458|-8.53%|1.573|8.614|0.000|25.86 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67768|0.67999|0.00052|0.08%|0.67842|0.00%|0.67820|0.00%|1.124|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/19f94430d5)|0.67413|0.67685|0.00063|0.09%|0.67493|-0.51%|0.67479|-0.50%|1.285|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/dcfa40cccf)|0.67390|0.67670|0.00065|0.10%|0.67468|-0.55%|0.67451|-0.54%|1.363|8.614|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dcfa40cccf)|0.64221|0.64525|0.00050|0.08%|0.64291|-5.23%|0.64282|-5.22%|2.167|8.614|0.000|26.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59194|0.59665|0.00086|0.14%|0.59360|0.00%|0.59359|0.00%|0.936|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/19f94430d5)|0.58945|0.59231|0.00059|0.10%|0.59024|-0.57%|0.59016|-0.58%|1.647|8.579|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/dcfa40cccf)|0.58947|0.59227|0.00042|0.07%|0.59010|-0.59%|0.59007|-0.59%|2.865|8.600|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dcfa40cccf)|0.52089|0.52473|0.00071|0.14%|0.52158|-12.13%|0.52141|-12.16%|3.540|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44322|0.44788|0.00086|0.19%|0.44468|0.00%|0.44459|0.00%|1.795|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/19f94430d5)|0.44947|0.45201|0.00061|0.13%|0.45071|1.36%|0.45072|1.38%|0.087|-8.614|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/dcfa40cccf)|0.45004|0.45331|0.00056|0.13%|0.45101|1.42%|0.45091|1.42%|1.401|-8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dcfa40cccf)|0.14401|0.14502|0.00020|0.14%|0.14451|-67.50%|0.14451|-67.50%|-0.189|8.614|0.000|26.24 MB|
