### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-10 00:44:21 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/42730541316 ([Artifacts](https://github.com/php/php-src/actions/runs/42730541316/artifacts/13726935449))|
| Changeset  |https://github.com/php/php-src/compare/497cf0875f..ac9b9c225d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39925|0.40044|0.00021|0.05%|0.39976|0.00%|0.39977|0.00%|0.398|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/497cf0875f)|0.38360|0.38468|0.00027|0.07%|0.38415|-3.91%|0.38415|-3.91%|-0.106|8.614|0.000|25.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9b9c225d)|0.38352|0.38605|0.00040|0.10%|0.38393|-3.96%|0.38387|-3.98%|3.349|8.614|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9b9c225d)|0.35833|0.36001|0.00031|0.09%|0.35876|-10.26%|0.35871|-10.27%|1.567|8.614|0.000|25.88 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67884|0.71188|0.00534|0.78%|0.68069|0.00%|0.67955|0.00%|5.174|0.000|1.000|26.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/497cf0875f)|0.68381|0.68739|0.00054|0.08%|0.68465|0.58%|0.68458|0.74%|2.779|-7.924|0.000|26.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9b9c225d)|0.68535|0.68981|0.00098|0.14%|0.68638|0.84%|0.68618|0.98%|2.216|-7.924|0.000|26.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9b9c225d)|0.65187|0.65315|0.00029|0.04%|0.65246|-4.15%|0.65242|-3.99%|0.217|8.614|0.000|26.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59307|0.59718|0.00090|0.15%|0.59455|0.00%|0.59447|0.00%|0.589|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/497cf0875f)|0.59866|0.60156|0.00069|0.12%|0.59947|0.83%|0.59929|0.81%|1.716|-8.614|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9b9c225d)|0.59097|0.59404|0.00058|0.10%|0.59177|-0.47%|0.59167|-0.47%|2.180|8.435|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9b9c225d)|0.51915|0.53052|0.00207|0.40%|0.52021|-12.50%|0.51976|-12.57%|4.428|8.614|0.000|26.44 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44365|0.44660|0.00056|0.13%|0.44482|0.00%|0.44468|0.00%|0.878|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/497cf0875f)|0.45263|0.45680|0.00078|0.17%|0.45408|2.08%|0.45412|2.12%|0.760|-8.614|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9b9c225d)|0.45308|0.45530|0.00058|0.13%|0.45418|2.11%|0.45416|2.13%|-0.121|-8.614|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9b9c225d)|0.14474|0.14775|0.00067|0.46%|0.14542|-67.31%|0.14526|-67.33%|2.399|8.614|0.000|26.44 MB|
