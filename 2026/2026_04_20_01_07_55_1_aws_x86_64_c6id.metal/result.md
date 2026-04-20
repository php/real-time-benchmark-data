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
| Time          |2026-04-20 01:07:55 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24643745228 ([Artifacts](https://github.com/php/php-src/actions/runs/24643745228/artifacts/6522946699))|
| Changeset  |https://github.com/php/php-src/compare/b40cae2b1f..fad4323634|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39632|0.39866|0.00072|0.18%|0.39707|0.00%|0.39667|0.00%|0.944|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b40cae2b1f)|0.38794|0.38975|0.00039|0.10%|0.38848|-2.16%|0.38840|-2.09%|1.612|8.614|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/fad4323634)|0.38792|0.39140|0.00066|0.17%|0.38868|-2.11%|0.38843|-2.08%|2.289|8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fad4323634)|0.36164|0.36372|0.00041|0.11%|0.36217|-8.79%|0.36209|-8.72%|2.107|8.614|0.000|25.39 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66853|0.67238|0.00071|0.11%|0.66937|0.00%|0.66917|0.00%|2.241|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b40cae2b1f)|0.66347|0.66463|0.00028|0.04%|0.66391|-0.81%|0.66386|-0.79%|1.043|8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/fad4323634)|0.66311|0.66577|0.00045|0.07%|0.66374|-0.84%|0.66366|-0.82%|2.075|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fad4323634)|0.63106|0.63333|0.00050|0.08%|0.63168|-5.63%|0.63153|-5.63%|1.614|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58919|0.59454|0.00129|0.22%|0.59168|0.00%|0.59181|0.00%|0.062|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b40cae2b1f)|0.58741|0.58952|0.00051|0.09%|0.58794|-0.63%|0.58778|-0.68%|1.620|8.586|0.000|25.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/fad4323634)|0.58720|0.58981|0.00057|0.10%|0.58792|-0.63%|0.58773|-0.69%|1.548|8.566|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fad4323634)|0.51760|0.52146|0.00053|0.10%|0.51839|-12.39%|0.51833|-12.42%|4.021|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44148|0.44524|0.00066|0.15%|0.44275|0.00%|0.44269|0.00%|0.948|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b40cae2b1f)|0.44509|0.44999|0.00072|0.16%|0.44655|0.86%|0.44657|0.87%|1.889|-8.607|0.000|25.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/fad4323634)|0.44450|0.44959|0.00072|0.16%|0.44641|0.83%|0.44631|0.82%|1.382|-8.600|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/fad4323634)|0.14326|0.14406|0.00017|0.12%|0.14360|-67.57%|0.14360|-67.56%|0.224|8.614|0.000|25.39 MB|
