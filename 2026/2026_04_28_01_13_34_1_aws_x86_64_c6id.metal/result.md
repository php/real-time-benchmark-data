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
| Time          |2026-04-28 01:13:34 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25028394599 ([Artifacts](https://github.com/php/php-src/actions/runs/25028394599/artifacts/6674878944))|
| Changeset  |https://github.com/php/php-src/compare/bd78496fb3..936f727106|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39478|0.39702|0.00068|0.17%|0.39555|0.00%|0.39521|0.00%|0.991|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bd78496fb3)|0.38654|0.38778|0.00030|0.08%|0.38693|-2.18%|0.38684|-2.12%|0.993|8.614|0.000|25.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/936f727106)|0.38667|0.38983|0.00053|0.14%|0.38719|-2.11%|0.38706|-2.06%|3.588|8.614|0.000|25.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/936f727106)|0.36399|0.36683|0.00043|0.12%|0.36495|-7.73%|0.36491|-7.67%|1.854|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66866|0.67043|0.00047|0.07%|0.66936|0.00%|0.66923|0.00%|0.943|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bd78496fb3)|0.66593|0.67106|0.00080|0.12%|0.66666|-0.40%|0.66640|-0.42%|3.850|8.269|0.000|25.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/936f727106)|0.66365|0.66506|0.00038|0.06%|0.66419|-0.77%|0.66406|-0.77%|0.634|8.614|0.000|25.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/936f727106)|0.63284|0.63421|0.00030|0.05%|0.63324|-5.40%|0.63317|-5.39%|1.388|8.614|0.000|25.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58787|0.59235|0.00099|0.17%|0.58987|0.00%|0.59002|0.00%|0.068|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bd78496fb3)|0.58397|0.58741|0.00063|0.11%|0.58485|-0.85%|0.58478|-0.89%|2.479|8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/936f727106)|0.58435|0.58753|0.00051|0.09%|0.58529|-0.78%|0.58515|-0.83%|2.250|8.614|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/936f727106)|0.51354|0.51694|0.00078|0.15%|0.51461|-12.76%|0.51439|-12.82%|1.622|8.614|0.000|25.30 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44135|0.45010|0.00154|0.35%|0.44297|0.00%|0.44264|0.00%|3.829|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bd78496fb3)|0.44516|0.44745|0.00051|0.11%|0.44642|0.78%|0.44641|0.85%|0.008|-7.924|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/936f727106)|0.44551|0.44730|0.00050|0.11%|0.44635|0.76%|0.44629|0.82%|0.087|-7.924|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/936f727106)|0.14310|0.14459|0.00024|0.17%|0.14354|-67.60%|0.14353|-67.57%|1.639|8.614|0.000|25.30 MB|
