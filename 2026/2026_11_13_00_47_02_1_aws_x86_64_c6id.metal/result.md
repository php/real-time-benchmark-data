### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-13 00:47:02 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/43339760525 ([Artifacts](https://github.com/php/php-src/actions/runs/43339760525/artifacts/13999929194))|
| Changeset  |https://github.com/php/php-src/compare/8eb02dbaa3..4f3d9508be|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39738|0.39834|0.00018|0.05%|0.39769|0.00%|0.39769|0.00%|0.798|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8eb02dbaa3)|0.37925|0.38031|0.00018|0.05%|0.37967|-4.53%|0.37964|-4.54%|0.878|8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3d9508be)|0.37926|0.38081|0.00040|0.11%|0.37989|-4.48%|0.37979|-4.50%|0.996|8.614|0.000|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3d9508be)|0.35371|0.35602|0.00050|0.14%|0.35463|-10.83%|0.35459|-10.84%|0.404|8.614|0.000|26.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67637|0.68824|0.00209|0.31%|0.67760|0.00%|0.67696|0.00%|3.948|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8eb02dbaa3)|0.67690|0.68172|0.00078|0.12%|0.67758|-0.00%|0.67739|0.06%|3.754|-3.474|0.001|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3d9508be)|0.67669|0.68046|0.00065|0.10%|0.67734|-0.04%|0.67718|0.03%|2.839|-1.582|0.114|26.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3d9508be)|0.64803|0.64898|0.00023|0.04%|0.64852|-4.29%|0.64852|-4.20%|0.124|8.614|0.000|26.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59067|0.59497|0.00088|0.15%|0.59212|0.00%|0.59200|0.00%|0.887|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8eb02dbaa3)|0.58802|0.59078|0.00044|0.07%|0.58868|-0.58%|0.58866|-0.56%|2.143|8.607|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3d9508be)|0.58811|0.59618|0.00134|0.23%|0.58962|-0.42%|0.58932|-0.45%|2.871|7.638|0.000|26.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3d9508be)|0.51527|0.52561|0.00149|0.29%|0.51610|-12.84%|0.51581|-12.87%|5.642|8.614|0.000|26.37 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44307|0.44590|0.00064|0.14%|0.44461|0.00%|0.44465|0.00%|-0.012|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8eb02dbaa3)|0.45303|0.45576|0.00057|0.13%|0.45430|2.18%|0.45430|2.17%|0.346|-8.614|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3d9508be)|0.45243|0.45552|0.00069|0.15%|0.45395|2.10%|0.45397|2.10%|-0.165|-8.614|0.000|26.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3d9508be)|0.14512|0.14912|0.00097|0.66%|0.14584|-67.20%|0.14561|-67.25%|2.952|8.614|0.000|26.37 MB|
