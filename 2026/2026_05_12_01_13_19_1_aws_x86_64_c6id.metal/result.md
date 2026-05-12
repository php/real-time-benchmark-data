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
| Time          |2026-05-12 01:13:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25707077419 ([Artifacts](https://github.com/php/php-src/actions/runs/25707077419/artifacts/6934103908))|
| Changeset  |https://github.com/php/php-src/compare/eb3204252e..10dad92c8b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39332|0.39431|0.00018|0.05%|0.39368|0.00%|0.39367|0.00%|1.050|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eb3204252e)|0.38651|0.38790|0.00027|0.07%|0.38709|-1.67%|0.38703|-1.69%|0.998|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/10dad92c8b)|0.38661|0.38999|0.00055|0.14%|0.38712|-1.67%|0.38698|-1.70%|3.381|8.614|0.000|25.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10dad92c8b)|0.35848|0.36097|0.00047|0.13%|0.35906|-8.79%|0.35890|-8.83%|2.379|8.614|0.000|25.51 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67195|0.67363|0.00042|0.06%|0.67259|0.00%|0.67251|0.00%|0.747|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eb3204252e)|0.66494|0.67106|0.00105|0.16%|0.66580|-1.01%|0.66546|-1.05%|3.131|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/10dad92c8b)|0.66220|0.66431|0.00052|0.08%|0.66285|-1.45%|0.66271|-1.46%|1.399|8.614|0.000|25.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10dad92c8b)|0.63012|0.63181|0.00031|0.05%|0.63067|-6.23%|0.63062|-6.23%|1.499|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58688|0.59207|0.00121|0.21%|0.58886|0.00%|0.58880|0.00%|0.329|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eb3204252e)|0.58437|0.58697|0.00063|0.11%|0.58517|-0.63%|0.58501|-0.64%|1.109|8.600|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/10dad92c8b)|0.58438|0.58694|0.00065|0.11%|0.58510|-0.64%|0.58494|-0.66%|1.410|8.586|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10dad92c8b)|0.51493|0.51975|0.00080|0.16%|0.51585|-12.40%|0.51569|-12.42%|2.981|8.614|0.000|25.38 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44164|0.45000|0.00116|0.26%|0.44299|0.00%|0.44285|0.00%|4.755|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eb3204252e)|0.44749|0.45060|0.00055|0.12%|0.44852|1.25%|0.44843|1.26%|0.880|-8.276|0.000|25.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/10dad92c8b)|0.44551|0.44823|0.00052|0.12%|0.44669|0.84%|0.44671|0.87%|0.358|-8.269|0.000|25.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10dad92c8b)|0.14358|0.14558|0.00035|0.24%|0.14412|-67.47%|0.14411|-67.46%|2.057|8.614|0.000|25.40 MB|
