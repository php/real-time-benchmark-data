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
| Time          |2026-05-27 01:26:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26485100918 ([Artifacts](https://github.com/php/php-src/actions/runs/26485100918/artifacts/7230531026))|
| Changeset  |https://github.com/php/php-src/compare/9e1b285f65..9898293af9|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39276|0.39423|0.00024|0.06%|0.39311|0.00%|0.39307|0.00%|2.544|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9e1b285f65)|0.38497|0.38903|0.00058|0.15%|0.38551|-1.93%|0.38537|-1.96%|4.868|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/9898293af9)|0.38479|0.38618|0.00031|0.08%|0.38518|-2.02%|0.38511|-2.03%|1.862|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9898293af9)|0.35918|0.36113|0.00033|0.09%|0.35989|-8.45%|0.35988|-8.45%|0.900|8.614|0.000|25.73 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67099|0.68586|0.00219|0.33%|0.67196|0.00%|0.67146|0.00%|5.662|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9e1b285f65)|0.66649|0.67095|0.00069|0.10%|0.66713|-0.72%|0.66694|-0.67%|3.944|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/9898293af9)|0.66320|0.66525|0.00036|0.05%|0.66380|-1.21%|0.66376|-1.15%|1.594|8.614|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9898293af9)|0.63195|0.63326|0.00027|0.04%|0.63240|-5.89%|0.63237|-5.82%|0.915|8.614|0.000|26.22 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58712|0.59155|0.00098|0.17%|0.58872|0.00%|0.58856|0.00%|0.908|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9e1b285f65)|0.58363|0.59116|0.00118|0.20%|0.58470|-0.68%|0.58444|-0.70%|3.873|8.269|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/9898293af9)|0.58396|0.59078|0.00118|0.20%|0.58485|-0.66%|0.58448|-0.69%|3.273|8.228|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9898293af9)|0.51258|0.52338|0.00157|0.31%|0.51360|-12.76%|0.51319|-12.81%|5.180|8.614|0.000|26.31 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44163|0.44443|0.00052|0.12%|0.44273|0.00%|0.44269|0.00%|0.878|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9e1b285f65)|0.45045|0.45243|0.00043|0.09%|0.45175|2.04%|0.45184|2.07%|-0.780|-8.614|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/9898293af9)|0.45085|0.45259|0.00039|0.09%|0.45164|2.01%|0.45163|2.02%|0.117|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9898293af9)|0.14368|0.14665|0.00071|0.49%|0.14428|-67.41%|0.14412|-67.44%|2.887|8.614|0.000|26.32 MB|
