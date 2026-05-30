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
| Time          |2026-05-30 13:25:50 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26670504487 ([Artifacts](https://github.com/php/php-src/actions/runs/26670504487/artifacts/7308801497))|
| Changeset  |https://github.com/php/php-src/compare/9898293af9..f2b371e747|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39649|0.39929|0.00076|0.19%|0.39725|0.00%|0.39690|0.00%|1.264|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9898293af9)|0.38880|0.39174|0.00046|0.12%|0.38922|-2.02%|0.38910|-1.96%|3.714|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/f2b371e747)|0.39119|0.39283|0.00033|0.08%|0.39159|-1.42%|0.39153|-1.35%|2.177|8.614|0.000|25.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f2b371e747)|0.36278|0.36573|0.00048|0.13%|0.36339|-8.52%|0.36330|-8.47%|3.091|8.614|0.000|25.73 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67505|0.67779|0.00070|0.10%|0.67586|0.00%|0.67557|0.00%|1.177|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9898293af9)|0.66792|0.66959|0.00042|0.06%|0.66844|-1.10%|0.66829|-1.08%|1.399|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/f2b371e747)|0.66846|0.67382|0.00078|0.12%|0.66941|-0.95%|0.66924|-0.94%|3.911|8.614|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f2b371e747)|0.63476|0.64874|0.00237|0.37%|0.63579|-5.93%|0.63517|-5.98%|4.637|8.614|0.000|26.23 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59081|0.59542|0.00112|0.19%|0.59258|0.00%|0.59237|0.00%|0.711|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9898293af9)|0.58812|0.59173|0.00056|0.09%|0.58878|-0.64%|0.58866|-0.63%|3.279|8.531|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/f2b371e747)|0.58961|0.59432|0.00109|0.18%|0.59066|-0.32%|0.59035|-0.34%|2.331|7.159|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f2b371e747)|0.51841|0.52202|0.00088|0.17%|0.51926|-12.37%|0.51893|-12.40%|1.904|8.614|0.000|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44299|0.45098|0.00116|0.26%|0.44469|0.00%|0.44457|0.00%|3.472|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9898293af9)|0.45234|0.45451|0.00047|0.10%|0.45339|1.96%|0.45339|1.98%|0.137|-8.614|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/f2b371e747)|0.44994|0.45205|0.00052|0.11%|0.45109|1.44%|0.45112|1.47%|-0.301|-8.455|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f2b371e747)|0.14553|0.15430|0.00149|1.02%|0.14647|-67.06%|0.14600|-67.16%|3.664|8.614|0.000|26.25 MB|
