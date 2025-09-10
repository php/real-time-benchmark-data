### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250818|
| GCC           |14.2.1|
| Time          |2025-09-10 00:49:59 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47527|0.48222|0.00098|0.21%|0.47645|0.00%|0.47624|0.00%|3.971|0.999|180946787|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156c847467)|0.47067|0.47483|0.00067|0.14%|0.47165|-1.01%|0.47150|-0.99%|1.699|0.000|176311949|44.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e2c991767)|0.46333|0.47227|0.00092|0.20%|0.47054|-1.24%|0.47051|-1.20%|-4.648|0.000|176385482|44.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e2c991767)|0.44960|0.45132|0.00039|0.09%|0.45046|-5.46%|0.45046|-5.41%|0.139|0.000|147822737|53.49 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.73088|0.75199|0.00165|0.22%|0.74057|0.00%|0.74048|0.00%|1.351|0.999|291622970|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156c847467)|0.73464|0.74740|0.00187|0.25%|0.73684|-0.50%|0.73636|-0.56%|3.605|0.000|287348813|40.74 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e2c991767)|0.73599|0.74364|0.00133|0.18%|0.73802|-0.34%|0.73770|-0.37%|1.572|0.000|287345280|40.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e2c991767)|0.70794|0.71305|0.00090|0.13%|0.70936|-4.21%|0.70922|-4.22%|1.348|0.000|267698218|47.63 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58008|0.59330|0.00196|0.34%|0.58254|0.00%|0.58222|0.00%|3.982|0.999|1123346867|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156c847467)|0.58192|0.58616|0.00079|0.13%|0.58429|0.30%|0.58424|0.35%|-0.118|0.000|1121217283|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e2c991767)|0.58293|0.58784|0.00086|0.15%|0.58490|0.41%|0.58489|0.46%|0.225|0.000|1121225221|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e2c991767)|0.51605|0.51999|0.00066|0.13%|0.51826|-11.03%|0.51830|-10.98%|-0.549|0.000|867307360|61.60 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42674|0.44536|0.00237|0.55%|0.43338|0.00%|0.43297|0.00%|1.273|0.999|2020638161|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/156c847467)|0.42648|0.56076|0.03036|6.93%|0.43806|1.08%|0.43022|-0.63%|3.694|0.000|2020644579|27.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e2c991767)|0.42554|0.56010|0.03028|6.93%|0.43716|0.87%|0.42876|-0.97%|3.429|0.000|2020644977|27.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e2c991767)|0.14296|0.15164|0.00103|0.69%|0.14921|-65.57%|0.14919|-65.54%|-1.959|0.000|536613062|27.91 MB|
