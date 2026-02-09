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
| Time          |2026-02-09 00:57:03 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21808717421 ([Artifacts](https://github.com/php/php-src/actions/runs/21808717421/artifacts/5426046799))|
| Changeset  |https://github.com/php/php-src/compare/52e9436629..96be28cb0e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39665|0.39970|0.00037|0.09%|0.39847|0.00%|0.39847|0.00%|-1.828|0.000|1.000|26.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/52e9436629)|0.39092|0.39252|0.00041|0.11%|0.39144|-1.77%|0.39130|-1.80%|1.055|8.614|0.000|25.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/96be28cb0e)|0.39041|0.39256|0.00047|0.12%|0.39094|-1.89%|0.39075|-1.94%|1.717|8.614|0.000|25.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96be28cb0e)|0.36414|0.36797|0.00075|0.21%|0.36474|-8.47%|0.36453|-8.52%|2.999|8.614|0.000|25.60 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67806|0.68002|0.00045|0.07%|0.67862|0.00%|0.67847|0.00%|1.304|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/52e9436629)|0.67611|0.67825|0.00047|0.07%|0.67682|-0.26%|0.67674|-0.25%|0.873|8.538|0.000|25.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/96be28cb0e)|0.67422|0.68087|0.00114|0.17%|0.67532|-0.49%|0.67493|-0.52%|3.021|8.255|0.000|25.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96be28cb0e)|0.64363|0.65698|0.00184|0.29%|0.64474|-4.99%|0.64436|-5.03%|6.253|8.614|0.000|25.74 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58957|0.59469|0.00113|0.19%|0.59172|0.00%|0.59174|0.00%|0.209|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/52e9436629)|0.58954|0.59974|0.00146|0.25%|0.59040|-0.22%|0.59013|-0.27%|5.675|6.477|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/96be28cb0e)|0.58934|0.59331|0.00066|0.11%|0.59013|-0.27%|0.59000|-0.29%|3.412|6.973|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96be28cb0e)|0.51906|0.52205|0.00063|0.12%|0.52006|-12.11%|0.51992|-12.14%|1.659|8.614|0.000|25.83 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44099|0.44389|0.00070|0.16%|0.44222|0.00%|0.44219|0.00%|0.467|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/52e9436629)|0.44109|0.44545|0.00101|0.23%|0.44313|0.21%|0.44330|0.25%|-0.003|-4.457|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/96be28cb0e)|0.44175|0.44708|0.00079|0.18%|0.44436|0.48%|0.44442|0.50%|0.070|-8.124|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96be28cb0e)|0.14294|0.14487|0.00030|0.21%|0.14347|-67.56%|0.14345|-67.56%|2.217|8.614|0.000|25.83 MB|
