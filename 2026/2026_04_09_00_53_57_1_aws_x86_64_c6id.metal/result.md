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
| Time          |2026-04-09 00:53:57 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24166625230 ([Artifacts](https://github.com/php/php-src/actions/runs/24166625230/artifacts/6340718578))|
| Changeset  |https://github.com/php/php-src/compare/961355c13d..0f3e741b53|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39962|0.40215|0.00071|0.18%|0.40046|0.00%|0.40016|0.00%|1.000|0.000|1.000|26.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/961355c13d)|0.39278|0.39449|0.00032|0.08%|0.39335|-1.77%|0.39331|-1.71%|1.140|8.614|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f3e741b53)|0.39185|0.39405|0.00046|0.12%|0.39234|-2.03%|0.39223|-1.98%|2.299|8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f3e741b53)|0.36661|0.36852|0.00046|0.13%|0.36734|-8.27%|0.36721|-8.23%|0.905|8.614|0.000|25.26 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67416|0.67654|0.00064|0.09%|0.67494|0.00%|0.67467|0.00%|1.085|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/961355c13d)|0.68001|0.68311|0.00065|0.10%|0.68081|0.87%|0.68063|0.88%|1.337|-8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f3e741b53)|0.67610|0.67759|0.00036|0.05%|0.67670|0.26%|0.67666|0.30%|0.675|-8.352|0.000|25.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f3e741b53)|0.64512|0.65177|0.00108|0.17%|0.64599|-4.29%|0.64576|-4.28%|4.366|8.614|0.000|25.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59654|0.60132|0.00119|0.20%|0.59861|0.00%|0.59856|0.00%|0.386|0.000|1.000|26.76 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/961355c13d)|0.59535|0.59842|0.00062|0.10%|0.59599|-0.44%|0.59583|-0.46%|2.236|8.207|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f3e741b53)|0.59455|0.59746|0.00072|0.12%|0.59542|-0.53%|0.59521|-0.56%|1.366|8.445|0.000|25.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f3e741b53)|0.52458|0.52828|0.00054|0.10%|0.52569|-12.18%|0.52563|-12.18%|2.121|8.614|0.000|25.30 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44181|0.44413|0.00051|0.11%|0.44303|0.00%|0.44303|0.00%|-0.107|0.000|1.000|26.76 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/961355c13d)|0.44549|0.44902|0.00055|0.12%|0.44650|0.78%|0.44643|0.77%|1.764|-8.614|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/0f3e741b53)|0.44506|0.44714|0.00056|0.13%|0.44610|0.69%|0.44605|0.68%|0.139|-8.614|0.000|25.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0f3e741b53)|0.14335|0.14437|0.00023|0.16%|0.14382|-67.54%|0.14381|-67.54%|0.422|8.614|0.000|25.30 MB|
