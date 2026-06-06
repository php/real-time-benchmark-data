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
| Time          |2026-06-06 01:22:32 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27048606759 ([Artifacts](https://github.com/php/php-src/actions/runs/27048606759/artifacts/7450271990))|
| Changeset  |https://github.com/php/php-src/compare/95b5b48799..95b5b48799|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39470|0.39524|0.00014|0.04%|0.39498|0.00%|0.39497|0.00%|0.106|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95b5b48799)|0.38329|0.38471|0.00030|0.08%|0.38367|-2.86%|0.38357|-2.88%|1.459|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/95b5b48799)|0.38312|0.38464|0.00038|0.10%|0.38355|-2.89%|0.38343|-2.92%|1.857|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95b5b48799)|0.35875|0.36139|0.00049|0.14%|0.35942|-9.00%|0.35931|-9.03%|2.478|8.614|0.000|25.76 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67204|0.67414|0.00054|0.08%|0.67294|0.00%|0.67279|0.00%|0.738|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95b5b48799)|0.66624|0.67013|0.00073|0.11%|0.66747|-0.81%|0.66740|-0.80%|1.142|8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/95b5b48799)|0.66606|0.66941|0.00083|0.13%|0.66733|-0.83%|0.66726|-0.82%|0.660|8.614|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95b5b48799)|0.63508|0.63811|0.00082|0.13%|0.63653|-5.41%|0.63648|-5.40%|0.121|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58850|0.59591|0.00121|0.21%|0.59027|0.00%|0.59014|0.00%|2.065|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95b5b48799)|0.58516|0.58698|0.00042|0.07%|0.58577|-0.76%|0.58566|-0.76%|0.949|8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/95b5b48799)|0.58492|0.59034|0.00105|0.18%|0.58588|-0.74%|0.58565|-0.76%|2.822|8.331|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95b5b48799)|0.51541|0.51985|0.00077|0.15%|0.51612|-12.56%|0.51595|-12.57%|3.348|8.614|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44286|0.45174|0.00121|0.27%|0.44457|0.00%|0.44446|0.00%|4.234|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/95b5b48799)|0.44993|0.45267|0.00063|0.14%|0.45121|1.49%|0.45118|1.51%|0.314|-8.345|0.000|25.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/95b5b48799)|0.45009|0.45303|0.00061|0.14%|0.45120|1.49%|0.45109|1.49%|0.527|-8.331|0.000|25.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95b5b48799)|0.14537|0.14947|0.00056|0.38%|0.14583|-67.20%|0.14573|-67.21%|5.861|8.614|0.000|26.21 MB|
