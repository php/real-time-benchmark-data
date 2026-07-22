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
| Time          |2026-07-22 01:00:38 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29881843892 ([Artifacts](https://github.com/php/php-src/actions/runs/29881843892/artifacts/8515940013))|
| Changeset  |https://github.com/php/php-src/compare/d0f00ccd98..786e42386d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39830|0.40077|0.00072|0.18%|0.39898|0.00%|0.39864|0.00%|1.118|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0f00ccd98)|0.39231|0.39379|0.00038|0.10%|0.39276|-1.56%|0.39261|-1.51%|1.389|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/786e42386d)|0.39260|0.39506|0.00044|0.11%|0.39306|-1.48%|0.39297|-1.42%|3.783|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/786e42386d)|0.36256|0.36475|0.00042|0.12%|0.36324|-8.96%|0.36318|-8.90%|1.420|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67668|0.68329|0.00116|0.17%|0.67777|0.00%|0.67746|0.00%|2.861|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0f00ccd98)|0.67021|0.67467|0.00108|0.16%|0.67154|-0.92%|0.67126|-0.92%|1.254|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/786e42386d)|0.67040|0.67665|0.00109|0.16%|0.67147|-0.93%|0.67106|-0.95%|2.570|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/786e42386d)|0.64275|0.64780|0.00077|0.12%|0.64379|-5.01%|0.64361|-5.00%|3.128|8.614|0.000|26.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59198|0.59550|0.00093|0.16%|0.59373|0.00%|0.59366|0.00%|0.107|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0f00ccd98)|0.58760|0.59310|0.00102|0.17%|0.58885|-0.82%|0.58864|-0.85%|2.683|8.448|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/786e42386d)|0.58751|0.59547|0.00120|0.20%|0.58848|-0.89%|0.58819|-0.92%|4.522|8.276|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/786e42386d)|0.51809|0.52935|0.00178|0.34%|0.51910|-12.57%|0.51861|-12.64%|4.507|8.614|0.000|26.30 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44319|0.44887|0.00091|0.21%|0.44478|0.00%|0.44456|0.00%|2.472|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0f00ccd98)|0.44822|0.44979|0.00036|0.08%|0.44902|0.95%|0.44905|1.01%|-0.076|-8.490|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/786e42386d)|0.44845|0.44972|0.00030|0.07%|0.44912|0.98%|0.44913|1.03%|-0.001|-8.545|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/786e42386d)|0.14415|0.14861|0.00070|0.48%|0.14471|-67.46%|0.14459|-67.48%|4.434|8.614|0.000|26.30 MB|
