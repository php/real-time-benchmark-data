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
| Time          |2026-07-11 01:00:59 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29133787317 ([Artifacts](https://github.com/php/php-src/actions/runs/29133787317/artifacts/8243411184))|
| Changeset  |https://github.com/php/php-src/compare/c3f1015e56..9073875eb9|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39443|0.39761|0.00086|0.22%|0.39529|0.00%|0.39482|0.00%|0.975|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c3f1015e56)|0.38483|0.38699|0.00047|0.12%|0.38534|-2.52%|0.38526|-2.42%|1.842|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/9073875eb9)|0.38510|0.38841|0.00053|0.14%|0.38563|-2.44%|0.38547|-2.37%|3.254|8.614|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9073875eb9)|0.35867|0.36384|0.00130|0.36%|0.36029|-8.85%|0.35973|-8.89%|0.922|8.614|0.000|25.77 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67215|0.67513|0.00069|0.10%|0.67288|0.00%|0.67267|0.00%|1.384|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c3f1015e56)|0.67146|0.67460|0.00063|0.09%|0.67222|-0.10%|0.67208|-0.09%|2.057|5.663|0.000|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/9073875eb9)|0.66342|0.66644|0.00050|0.07%|0.66397|-1.32%|0.66387|-1.31%|3.214|8.614|0.000|25.68 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9073875eb9)|0.63525|0.64483|0.00143|0.22%|0.63653|-5.40%|0.63630|-5.41%|4.653|8.614|0.000|26.17 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58773|0.59209|0.00103|0.17%|0.59001|0.00%|0.58987|0.00%|-0.024|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c3f1015e56)|0.58505|0.59427|0.00149|0.25%|0.58610|-0.66%|0.58579|-0.69%|4.241|7.904|0.000|26.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/9073875eb9)|0.58476|0.59281|0.00112|0.19%|0.58600|-0.68%|0.58569|-0.71%|4.914|8.255|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9073875eb9)|0.51609|0.52001|0.00085|0.16%|0.51696|-12.38%|0.51675|-12.40%|2.460|8.614|0.000|26.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44322|0.44586|0.00058|0.13%|0.44442|0.00%|0.44446|0.00%|0.026|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c3f1015e56)|0.44938|0.45192|0.00066|0.15%|0.45065|1.40%|0.45075|1.41%|0.037|-8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/9073875eb9)|0.44942|0.45197|0.00062|0.14%|0.45075|1.42%|0.45076|1.42%|-0.076|-8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9073875eb9)|0.14400|0.14520|0.00026|0.18%|0.14449|-67.49%|0.14455|-67.48%|0.192|8.614|0.000|26.27 MB|
