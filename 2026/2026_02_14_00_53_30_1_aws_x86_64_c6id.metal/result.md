### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-14 00:53:30 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22007994758 ([Artifacts](https://github.com/php/php-src/actions/runs/22007994758/artifacts/5508252854))|
| Changeset  |https://github.com/php/php-src/compare/7134e69ab2..4fbe41116b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39745|0.39832|0.00019|0.05%|0.39797|0.00%|0.39798|0.00%|-0.478|0.000|1.000|26.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7134e69ab2)|0.39164|0.39340|0.00047|0.12%|0.39223|-1.44%|0.39204|-1.49%|1.072|8.614|0.000|25.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/4fbe41116b)|0.39146|0.39337|0.00052|0.13%|0.39202|-1.49%|0.39182|-1.55%|1.294|8.614|0.000|25.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4fbe41116b)|0.36338|0.36605|0.00060|0.17%|0.36395|-8.55%|0.36384|-8.58%|2.593|8.614|0.000|25.60 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67923|0.68245|0.00070|0.10%|0.67999|0.00%|0.67976|0.00%|1.844|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7134e69ab2)|0.68137|0.68431|0.00057|0.08%|0.68228|0.34%|0.68222|0.36%|1.014|-8.248|0.000|25.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/4fbe41116b)|0.68160|0.68441|0.00049|0.07%|0.68225|0.33%|0.68220|0.36%|1.882|-8.242|0.000|25.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4fbe41116b)|0.65048|0.65448|0.00079|0.12%|0.65131|-4.22%|0.65106|-4.22%|2.457|8.614|0.000|25.67 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58907|0.59463|0.00127|0.21%|0.59142|0.00%|0.59127|0.00%|0.416|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7134e69ab2)|0.58897|0.59399|0.00104|0.18%|0.59010|-0.22%|0.58988|-0.24%|2.737|5.825|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/4fbe41116b)|0.58869|0.59387|0.00110|0.19%|0.58965|-0.30%|0.58935|-0.33%|2.744|6.711|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4fbe41116b)|0.51978|0.52185|0.00042|0.08%|0.52054|-11.99%|0.52055|-11.96%|0.502|8.614|0.000|25.83 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44127|0.44647|0.00092|0.21%|0.44262|0.00%|0.44242|0.00%|2.156|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7134e69ab2)|0.44314|0.44768|0.00081|0.18%|0.44472|0.47%|0.44475|0.53%|1.177|-7.725|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/4fbe41116b)|0.44313|0.44547|0.00060|0.13%|0.44465|0.46%|0.44473|0.52%|-0.680|-7.718|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4fbe41116b)|0.14303|0.14404|0.00021|0.15%|0.14348|-67.58%|0.14347|-67.57%|0.351|8.614|0.000|25.83 MB|
