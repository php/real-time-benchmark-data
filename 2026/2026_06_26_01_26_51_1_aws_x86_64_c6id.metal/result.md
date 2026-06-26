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
| Time          |2026-06-26 01:26:51 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28211211003 ([Artifacts](https://github.com/php/php-src/actions/runs/28211211003/artifacts/7895599792))|
| Changeset  |https://github.com/php/php-src/compare/5cd9a3b047..08c6ecac52|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39475|0.39698|0.00068|0.17%|0.39546|0.00%|0.39519|0.00%|1.246|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5cd9a3b047)|0.38662|0.38829|0.00034|0.09%|0.38718|-2.09%|0.38713|-2.04%|1.429|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/08c6ecac52)|0.38642|0.38782|0.00032|0.08%|0.38693|-2.16%|0.38685|-2.11%|1.109|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/08c6ecac52)|0.35905|0.36156|0.00043|0.12%|0.35955|-9.08%|0.35947|-9.04%|2.697|8.614|0.000|25.73 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67234|0.67520|0.00055|0.08%|0.67323|0.00%|0.67310|0.00%|1.224|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5cd9a3b047)|0.66377|0.66584|0.00036|0.05%|0.66445|-1.30%|0.66438|-1.30%|1.846|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/08c6ecac52)|0.67058|0.70419|0.00468|0.70%|0.67215|-0.16%|0.67131|-0.27%|6.828|7.573|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/08c6ecac52)|0.63411|0.64105|0.00103|0.16%|0.63515|-5.66%|0.63497|-5.67%|4.327|8.614|0.000|25.83 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58854|0.59314|0.00114|0.19%|0.59082|0.00%|0.59074|0.00%|0.297|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5cd9a3b047)|0.58418|0.58907|0.00099|0.17%|0.58524|-0.94%|0.58494|-0.98%|2.366|8.600|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/08c6ecac52)|0.58410|0.58741|0.00055|0.09%|0.58480|-1.02%|0.58465|-1.03%|2.663|8.614|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/08c6ecac52)|0.51526|0.52710|0.00179|0.35%|0.51652|-12.58%|0.51599|-12.65%|4.538|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44373|0.45120|0.00106|0.24%|0.44451|0.00%|0.44428|0.00%|5.280|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5cd9a3b047)|0.44960|0.45309|0.00061|0.14%|0.45066|1.38%|0.45055|1.41%|1.381|-8.317|0.000|25.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/08c6ecac52)|0.44932|0.45151|0.00060|0.13%|0.45043|1.33%|0.45039|1.37%|0.027|-8.310|0.000|25.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/08c6ecac52)|0.14441|0.14538|0.00023|0.16%|0.14484|-67.42%|0.14483|-67.40%|0.365|8.614|0.000|26.30 MB|
