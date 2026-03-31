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
| Time          |2026-03-31 01:00:32 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23775318319 ([Artifacts](https://github.com/php/php-src/actions/runs/23775318319/artifacts/6190971799))|
| Changeset  |https://github.com/php/php-src/compare/73c4690c0e..b1710f48ba|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39437|0.39540|0.00019|0.05%|0.39472|0.00%|0.39467|0.00%|1.067|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/73c4690c0e)|0.38795|0.38921|0.00027|0.07%|0.38837|-1.61%|0.38832|-1.61%|1.465|8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1710f48ba)|0.38885|0.39103|0.00040|0.10%|0.38931|-1.37%|0.38918|-1.39%|2.357|8.614|0.000|25.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1710f48ba)|0.36142|0.36359|0.00051|0.14%|0.36218|-8.24%|0.36205|-8.27%|1.467|8.614|0.000|25.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66642|0.67110|0.00080|0.12%|0.66731|0.00%|0.66701|0.00%|2.450|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/73c4690c0e)|0.66249|0.66684|0.00094|0.14%|0.66338|-0.59%|0.66306|-0.59%|2.576|8.490|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1710f48ba)|0.66187|0.66449|0.00054|0.08%|0.66242|-0.73%|0.66227|-0.71%|1.913|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1710f48ba)|0.63258|0.63840|0.00081|0.13%|0.63309|-5.13%|0.63296|-5.10%|6.002|8.614|0.000|25.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58813|0.59330|0.00108|0.18%|0.58989|0.00%|0.58964|0.00%|1.244|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/73c4690c0e)|0.58619|0.59416|0.00152|0.26%|0.58712|-0.47%|0.58669|-0.50%|3.952|7.766|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1710f48ba)|0.58471|0.59171|0.00112|0.19%|0.58572|-0.71%|0.58548|-0.71%|3.683|8.297|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1710f48ba)|0.51456|0.51953|0.00092|0.18%|0.51561|-12.59%|0.51542|-12.59%|2.797|8.614|0.000|25.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44148|0.44381|0.00056|0.13%|0.44289|0.00%|0.44293|0.00%|-0.437|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/73c4690c0e)|0.44411|0.44679|0.00063|0.14%|0.44551|0.59%|0.44562|0.61%|-0.293|-8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/b1710f48ba)|0.44273|0.44604|0.00077|0.17%|0.44460|0.39%|0.44472|0.41%|-0.288|-7.973|0.000|25.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b1710f48ba)|0.14329|0.14417|0.00018|0.13%|0.14373|-67.55%|0.14369|-67.56%|0.024|8.614|0.000|25.37 MB|
