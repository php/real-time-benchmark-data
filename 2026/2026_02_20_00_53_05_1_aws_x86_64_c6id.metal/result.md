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
| Time          |2026-02-20 00:53:05 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22206667882 ([Artifacts](https://github.com/php/php-src/actions/runs/22206667882/artifacts/5583247958))|
| Changeset  |https://github.com/php/php-src/compare/fa2caa0403..c891263900|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39469|0.39677|0.00031|0.08%|0.39518|0.00%|0.39513|0.00%|2.855|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa2caa0403)|0.38948|0.39161|0.00042|0.11%|0.38996|-1.32%|0.38983|-1.34%|2.047|8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/c891263900)|0.38962|0.39233|0.00051|0.13%|0.39026|-1.24%|0.39009|-1.28%|2.044|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c891263900)|0.36101|0.36365|0.00055|0.15%|0.36168|-8.48%|0.36156|-8.50%|1.339|8.614|0.000|25.37 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66940|0.67195|0.00055|0.08%|0.67008|0.00%|0.66990|0.00%|1.413|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa2caa0403)|0.66128|0.66267|0.00031|0.05%|0.66178|-1.24%|0.66169|-1.23%|1.110|8.614|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/c891263900)|0.66144|0.66330|0.00034|0.05%|0.66197|-1.21%|0.66192|-1.19%|1.514|8.614|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c891263900)|0.63030|0.63705|0.00128|0.20%|0.63113|-5.81%|0.63084|-5.83%|4.174|8.614|0.000|25.34 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58790|0.59315|0.00121|0.20%|0.59018|0.00%|0.58989|0.00%|0.353|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa2caa0403)|0.58563|0.58881|0.00053|0.09%|0.58641|-0.64%|0.58627|-0.61%|2.320|8.586|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/c891263900)|0.58582|0.58932|0.00070|0.12%|0.58660|-0.61%|0.58644|-0.59%|2.701|8.435|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c891263900)|0.51667|0.52095|0.00071|0.14%|0.51749|-12.32%|0.51734|-12.30%|3.847|8.614|0.000|25.44 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44187|0.44549|0.00063|0.14%|0.44280|0.00%|0.44274|0.00%|1.580|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fa2caa0403)|0.44436|0.44687|0.00057|0.13%|0.44573|0.66%|0.44579|0.69%|-0.080|-8.490|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/c891263900)|0.44472|0.44642|0.00042|0.10%|0.44567|0.65%|0.44562|0.65%|-0.213|-8.510|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c891263900)|0.14339|0.14431|0.00020|0.14%|0.14377|-67.53%|0.14375|-67.53%|0.225|8.614|0.000|25.44 MB|
