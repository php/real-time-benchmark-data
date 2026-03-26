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
| Time          |2026-03-26 01:00:09 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23572129733 ([Artifacts](https://github.com/php/php-src/actions/runs/23572129733/artifacts/6114921827))|
| Changeset  |https://github.com/php/php-src/compare/e4dcd2e272..1655d57751|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39416|0.39605|0.00026|0.07%|0.39459|0.00%|0.39455|0.00%|3.595|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4dcd2e272)|0.38718|0.38870|0.00030|0.08%|0.38765|-1.76%|0.38756|-1.77%|1.506|8.614|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/1655d57751)|0.38741|0.38823|0.00019|0.05%|0.38770|-1.74%|0.38767|-1.74%|1.009|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1655d57751)|0.36047|0.36374|0.00078|0.22%|0.36138|-8.42%|0.36106|-8.49%|1.688|8.614|0.000|25.32 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66579|0.66934|0.00067|0.10%|0.66666|0.00%|0.66638|0.00%|1.756|0.000|1.000|26.72 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4dcd2e272)|0.66249|0.66400|0.00035|0.05%|0.66315|-0.53%|0.66307|-0.50%|0.682|8.614|0.000|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/1655d57751)|0.66268|0.66505|0.00040|0.06%|0.66325|-0.51%|0.66318|-0.48%|1.959|8.614|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1655d57751)|0.63246|0.64843|0.00220|0.35%|0.63352|-4.97%|0.63314|-4.99%|6.627|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58760|0.59234|0.00112|0.19%|0.58999|0.00%|0.58987|0.00%|-0.210|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4dcd2e272)|0.58431|0.59361|0.00138|0.24%|0.58609|-0.66%|0.58574|-0.70%|3.892|8.117|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/1655d57751)|0.58447|0.58877|0.00083|0.14%|0.58608|-0.66%|0.58592|-0.67%|1.385|8.483|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1655d57751)|0.51434|0.51861|0.00086|0.17%|0.51569|-12.59%|0.51545|-12.62%|2.284|8.614|0.000|25.41 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44136|0.44479|0.00064|0.14%|0.44266|0.00%|0.44256|0.00%|0.818|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e4dcd2e272)|0.44457|0.44650|0.00045|0.10%|0.44576|0.70%|0.44579|0.73%|-0.432|-8.607|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/1655d57751)|0.44466|0.44692|0.00048|0.11%|0.44561|0.67%|0.44562|0.69%|0.081|-8.593|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1655d57751)|0.14347|0.14438|0.00023|0.16%|0.14388|-67.50%|0.14384|-67.50%|0.462|8.614|0.000|25.28 MB|
