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
| Time          |2026-03-10 00:50:47 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22881836295 ([Artifacts](https://github.com/php/php-src/actions/runs/22881836295/artifacts/5841569263))|
| Changeset  |https://github.com/php/php-src/compare/c56e8caaed..f93b17076a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39454|0.39599|0.00023|0.06%|0.39489|0.00%|0.39487|0.00%|2.445|0.000|1.000|26.23 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c56e8caaed)|0.38865|0.39093|0.00037|0.10%|0.38920|-1.44%|0.38915|-1.45%|2.503|8.614|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/f93b17076a)|0.38817|0.39133|0.00059|0.15%|0.38876|-1.55%|0.38861|-1.59%|3.278|8.614|0.000|25.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f93b17076a)|0.36006|0.36151|0.00029|0.08%|0.36054|-8.70%|0.36050|-8.70%|0.845|8.614|0.000|25.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66694|0.67049|0.00070|0.10%|0.66785|0.00%|0.66764|0.00%|1.792|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c56e8caaed)|0.66465|0.66912|0.00063|0.09%|0.66546|-0.36%|0.66537|-0.34%|4.148|8.290|0.000|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/f93b17076a)|0.66554|0.66757|0.00033|0.05%|0.66609|-0.26%|0.66599|-0.25%|2.071|8.483|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f93b17076a)|0.63113|0.65187|0.00351|0.55%|0.63253|-5.29%|0.63157|-5.40%|4.285|8.614|0.000|25.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58810|0.59289|0.00106|0.18%|0.59006|0.00%|0.59005|0.00%|0.368|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c56e8caaed)|0.58438|0.58775|0.00068|0.12%|0.58554|-0.77%|0.58547|-0.78%|1.772|8.614|0.000|25.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/f93b17076a)|0.58491|0.58860|0.00073|0.12%|0.58550|-0.77%|0.58532|-0.80%|2.837|8.600|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f93b17076a)|0.51492|0.51801|0.00047|0.09%|0.51577|-12.59%|0.51573|-12.59%|2.279|8.614|0.000|25.34 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44197|0.44437|0.00058|0.13%|0.44290|0.00%|0.44279|0.00%|0.866|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c56e8caaed)|0.44312|0.44670|0.00074|0.17%|0.44525|0.53%|0.44542|0.59%|-0.646|-8.393|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/f93b17076a)|0.44384|0.44715|0.00069|0.15%|0.44522|0.52%|0.44514|0.53%|0.471|-8.545|0.000|25.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f93b17076a)|0.14335|0.14432|0.00022|0.15%|0.14383|-67.52%|0.14379|-67.53%|0.261|8.614|0.000|25.32 MB|
