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
| Time          |2026-06-15 01:37:00 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27518934229 ([Artifacts](https://github.com/php/php-src/actions/runs/27518934229/artifacts/7627848587))|
| Changeset  |https://github.com/php/php-src/compare/a15155100d..92128ac93f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39654|0.39715|0.00015|0.04%|0.39688|0.00%|0.39688|0.00%|-0.258|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a15155100d)|0.38660|0.38954|0.00042|0.11%|0.38865|-2.07%|0.38863|-2.08%|-1.921|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/92128ac93f)|0.38858|0.39016|0.00036|0.09%|0.38913|-1.95%|0.38904|-1.98%|1.247|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92128ac93f)|0.36081|0.36317|0.00049|0.14%|0.36140|-8.94%|0.36129|-8.97%|1.716|8.614|0.000|25.79 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67544|0.67814|0.00054|0.08%|0.67621|0.00%|0.67612|0.00%|1.327|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a15155100d)|0.66812|0.67745|0.00171|0.26%|0.66928|-1.03%|0.66869|-1.10%|3.361|8.283|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/92128ac93f)|0.67585|0.68245|0.00104|0.15%|0.67812|0.28%|0.67807|0.29%|1.379|-7.918|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92128ac93f)|0.64674|0.65433|0.00115|0.18%|0.64790|-4.19%|0.64761|-4.22%|3.918|8.614|0.000|26.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59136|0.59568|0.00101|0.17%|0.59354|0.00%|0.59352|0.00%|0.322|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a15155100d)|0.58866|0.59361|0.00074|0.13%|0.58965|-0.66%|0.58947|-0.68%|3.456|8.421|0.000|25.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/92128ac93f)|0.58774|0.59144|0.00081|0.14%|0.58873|-0.81%|0.58854|-0.84%|1.916|8.607|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92128ac93f)|0.52086|0.52532|0.00083|0.16%|0.52174|-12.10%|0.52148|-12.14%|3.017|8.614|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44350|0.44995|0.00098|0.22%|0.44471|0.00%|0.44463|0.00%|3.109|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a15155100d)|0.45028|0.45464|0.00071|0.16%|0.45154|1.54%|0.45147|1.54%|1.696|-8.614|0.000|25.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/92128ac93f)|0.44868|0.45213|0.00080|0.18%|0.44993|1.17%|0.44978|1.16%|0.930|-8.407|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92128ac93f)|0.14438|0.14649|0.00038|0.26%|0.14488|-67.42%|0.14478|-67.44%|1.776|8.614|0.000|26.23 MB|
