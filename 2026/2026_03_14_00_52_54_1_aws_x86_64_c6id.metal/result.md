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
| Time          |2026-03-14 00:52:54 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23076555822 ([Artifacts](https://github.com/php/php-src/actions/runs/23076555822/artifacts/5921081737))|
| Changeset  |https://github.com/php/php-src/compare/5ccaccda97..92ba1e4ea0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39649|0.39875|0.00045|0.11%|0.39702|0.00%|0.39687|0.00%|2.267|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5ccaccda97)|0.39037|0.39329|0.00058|0.15%|0.39084|-1.56%|0.39069|-1.56%|3.268|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/92ba1e4ea0)|0.39068|0.39524|0.00069|0.18%|0.39137|-1.42%|0.39120|-1.43%|3.981|8.614|0.000|25.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92ba1e4ea0)|0.36350|0.36509|0.00028|0.08%|0.36399|-8.32%|0.36393|-8.30%|1.471|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67021|0.67180|0.00042|0.06%|0.67081|0.00%|0.67067|0.00%|0.823|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5ccaccda97)|0.66869|0.67156|0.00068|0.10%|0.66933|-0.22%|0.66918|-0.22%|2.011|7.607|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/92ba1e4ea0)|0.66681|0.67354|0.00100|0.15%|0.66754|-0.49%|0.66728|-0.51%|4.719|8.269|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92ba1e4ea0)|0.63625|0.63797|0.00032|0.05%|0.63691|-5.05%|0.63685|-5.04%|0.905|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58964|0.59447|0.00112|0.19%|0.59194|0.00%|0.59215|0.00%|-0.092|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5ccaccda97)|0.58650|0.58959|0.00047|0.08%|0.58730|-0.79%|0.58722|-0.83%|2.410|8.614|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/92ba1e4ea0)|0.58752|0.59120|0.00072|0.12%|0.58847|-0.59%|0.58833|-0.64%|2.434|8.421|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92ba1e4ea0)|0.51729|0.52099|0.00094|0.18%|0.51846|-12.41%|0.51813|-12.50%|1.368|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44169|0.44459|0.00055|0.12%|0.44274|0.00%|0.44262|0.00%|0.895|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5ccaccda97)|0.44380|0.44916|0.00084|0.19%|0.44548|0.62%|0.44543|0.64%|1.513|-8.572|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/92ba1e4ea0)|0.44448|0.44657|0.00051|0.11%|0.44560|0.65%|0.44573|0.70%|-0.492|-8.607|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92ba1e4ea0)|0.14351|0.14444|0.00022|0.16%|0.14393|-67.49%|0.14395|-67.48%|0.364|8.614|0.000|25.35 MB|
