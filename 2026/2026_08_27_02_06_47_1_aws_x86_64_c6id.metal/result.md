### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Time          |2026-08-27 02:06:47 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33032233200 ([Artifacts](https://github.com/php/php-src/actions/runs/33032233200/artifacts/9631213923))|
| Changeset  |https://github.com/php/php-src/compare/846773a4e9..53c3116c38|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39916|0.40091|0.00028|0.07%|0.39954|0.00%|0.39952|0.00%|2.590|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/846773a4e9)|0.37225|0.37404|0.00031|0.08%|0.37273|-6.71%|0.37269|-6.72%|1.795|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/53c3116c38)|0.37289|0.37477|0.00041|0.11%|0.37346|-6.53%|0.37338|-6.54%|1.728|8.614|0.000|25.87 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68055|0.68437|0.00083|0.12%|0.68187|0.00%|0.68181|0.00%|0.902|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/846773a4e9)|0.66996|0.67252|0.00055|0.08%|0.67091|-1.61%|0.67082|-1.61%|0.839|8.614|0.000|25.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/53c3116c38)|0.67054|0.67204|0.00032|0.05%|0.67107|-1.58%|0.67103|-1.58%|1.113|8.614|0.000|25.89 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59084|0.59403|0.00085|0.14%|0.59241|0.00%|0.59232|0.00%|0.055|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/846773a4e9)|0.58861|0.59420|0.00096|0.16%|0.58997|-0.41%|0.58979|-0.43%|2.236|7.938|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/53c3116c38)|0.58913|0.59176|0.00049|0.08%|0.59012|-0.39%|0.59006|-0.38%|0.778|8.490|0.000|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44366|0.44854|0.00079|0.18%|0.44479|0.00%|0.44467|0.00%|2.766|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/846773a4e9)|0.45005|0.45273|0.00053|0.12%|0.45110|1.42%|0.45106|1.44%|0.493|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/53c3116c38)|0.45056|0.45661|0.00095|0.21%|0.45202|1.63%|0.45198|1.64%|2.615|-8.614|0.000|26.25 MB|
