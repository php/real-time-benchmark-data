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
| Time          |2026-04-11 00:59:04 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24270915613 ([Artifacts](https://github.com/php/php-src/actions/runs/24270915613/artifacts/6382400525))|
| Changeset  |https://github.com/php/php-src/compare/715645f5d7..555e65242f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39634|0.39826|0.00063|0.16%|0.39691|0.00%|0.39663|0.00%|1.286|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/715645f5d7)|0.38831|0.39023|0.00036|0.09%|0.38880|-2.04%|0.38876|-1.99%|1.893|8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/555e65242f)|0.39007|0.39183|0.00037|0.09%|0.39061|-1.59%|0.39051|-1.54%|1.280|8.614|0.000|25.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/555e65242f)|0.36312|0.36428|0.00026|0.07%|0.36364|-8.38%|0.36366|-8.31%|0.125|8.614|0.000|25.25 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66910|0.67273|0.00072|0.11%|0.66991|0.00%|0.66966|0.00%|1.908|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/715645f5d7)|0.66363|0.66884|0.00112|0.17%|0.66459|-0.79%|0.66426|-0.81%|3.001|8.614|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/555e65242f)|0.66479|0.67009|0.00076|0.11%|0.66540|-0.67%|0.66522|-0.66%|4.916|8.373|0.000|25.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/555e65242f)|0.63537|0.63875|0.00054|0.08%|0.63592|-5.07%|0.63581|-5.05%|3.362|8.614|0.000|25.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58962|0.59389|0.00091|0.15%|0.59163|0.00%|0.59163|0.00%|0.127|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/715645f5d7)|0.58657|0.59032|0.00074|0.13%|0.58774|-0.66%|0.58756|-0.69%|1.868|8.552|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/555e65242f)|0.58578|0.58798|0.00043|0.07%|0.58650|-0.87%|0.58642|-0.88%|1.347|8.614|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/555e65242f)|0.51689|0.52008|0.00068|0.13%|0.51781|-12.48%|0.51764|-12.50%|1.777|8.614|0.000|25.32 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44141|0.45351|0.00162|0.36%|0.44316|0.00%|0.44302|0.00%|5.519|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/715645f5d7)|0.44472|0.44787|0.00052|0.12%|0.44583|0.60%|0.44580|0.63%|1.151|-8.269|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/555e65242f)|0.44507|0.44709|0.00041|0.09%|0.44580|0.60%|0.44572|0.61%|0.943|-8.269|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/555e65242f)|0.14350|0.14411|0.00015|0.11%|0.14376|-67.56%|0.14374|-67.55%|0.356|8.614|0.000|25.32 MB|
