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
| Time          |2026-03-18 00:57:01 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23223807803 ([Artifacts](https://github.com/php/php-src/actions/runs/23223807803/artifacts/5977416972))|
| Changeset  |https://github.com/php/php-src/compare/8cf917990c..e6db18b74c|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39445|0.39670|0.00039|0.10%|0.39480|0.00%|0.39470|0.00%|3.536|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8cf917990c)|0.38721|0.38900|0.00030|0.08%|0.38783|-1.77%|0.38780|-1.75%|1.547|8.614|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6db18b74c)|0.38808|0.39078|0.00045|0.12%|0.38865|-1.56%|0.38854|-1.56%|2.658|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6db18b74c)|0.36051|0.36314|0.00053|0.15%|0.36112|-8.53%|0.36095|-8.55%|2.673|8.614|0.000|25.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66645|0.66988|0.00070|0.10%|0.66728|0.00%|0.66698|0.00%|1.723|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8cf917990c)|0.66292|0.66621|0.00068|0.10%|0.66364|-0.55%|0.66345|-0.53%|2.554|8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6db18b74c)|0.66291|0.66440|0.00032|0.05%|0.66347|-0.57%|0.66342|-0.53%|0.885|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6db18b74c)|0.63234|0.63333|0.00024|0.04%|0.63278|-5.17%|0.63275|-5.13%|0.440|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58839|0.59270|0.00094|0.16%|0.59003|0.00%|0.59009|0.00%|0.603|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8cf917990c)|0.58541|0.58920|0.00054|0.09%|0.58629|-0.63%|0.58620|-0.66%|3.394|8.545|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6db18b74c)|0.58526|0.59219|0.00112|0.19%|0.58600|-0.68%|0.58568|-0.75%|3.989|8.283|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6db18b74c)|0.51405|0.51716|0.00059|0.11%|0.51486|-12.74%|0.51471|-12.77%|2.442|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44178|0.44475|0.00066|0.15%|0.44283|0.00%|0.44282|0.00%|0.786|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8cf917990c)|0.44319|0.44669|0.00067|0.15%|0.44541|0.58%|0.44546|0.60%|-0.872|-8.476|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/e6db18b74c)|0.44460|0.44676|0.00049|0.11%|0.44560|0.63%|0.44561|0.63%|0.266|-8.607|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e6db18b74c)|0.14331|0.14423|0.00019|0.13%|0.14380|-67.53%|0.14379|-67.53%|0.052|8.614|0.000|25.33 MB|
