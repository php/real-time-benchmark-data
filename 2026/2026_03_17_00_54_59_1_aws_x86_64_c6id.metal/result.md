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
| Time          |2026-03-17 00:54:59 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23173201837 ([Artifacts](https://github.com/php/php-src/actions/runs/23173201837/artifacts/5956431624))|
| Changeset  |https://github.com/php/php-src/compare/3927630e62..8cf917990c|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39637|0.39835|0.00059|0.15%|0.39703|0.00%|0.39677|0.00%|1.271|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3927630e62)|0.39185|0.39374|0.00032|0.08%|0.39227|-1.20%|0.39222|-1.15%|2.278|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/8cf917990c)|0.38983|0.39206|0.00057|0.15%|0.39038|-1.68%|0.39016|-1.67%|1.657|8.614|0.000|25.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8cf917990c)|0.36354|0.36652|0.00051|0.14%|0.36405|-8.31%|0.36394|-8.28%|3.090|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66907|0.67940|0.00155|0.23%|0.66998|0.00%|0.66954|0.00%|4.989|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3927630e62)|0.66589|0.66928|0.00056|0.08%|0.66646|-0.53%|0.66631|-0.48%|3.129|8.545|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/8cf917990c)|0.66636|0.66952|0.00062|0.09%|0.66693|-0.45%|0.66678|-0.41%|2.836|8.366|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8cf917990c)|0.63454|0.63983|0.00072|0.11%|0.63511|-5.20%|0.63499|-5.16%|6.069|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58910|0.59365|0.00097|0.16%|0.59150|0.00%|0.59154|0.00%|0.136|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3927630e62)|0.58698|0.59123|0.00091|0.15%|0.58811|-0.57%|0.58790|-0.61%|2.564|8.169|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/8cf917990c)|0.58700|0.59114|0.00083|0.14%|0.58817|-0.56%|0.58791|-0.61%|1.930|8.359|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8cf917990c)|0.51638|0.52019|0.00073|0.14%|0.51741|-12.53%|0.51727|-12.55%|2.590|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44165|0.45103|0.00129|0.29%|0.44319|0.00%|0.44306|0.00%|4.712|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3927630e62)|0.44391|0.44647|0.00066|0.15%|0.44526|0.47%|0.44521|0.49%|-0.026|-8.166|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/8cf917990c)|0.44426|0.44663|0.00056|0.13%|0.44542|0.50%|0.44547|0.54%|-0.210|-8.221|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8cf917990c)|0.14343|0.14443|0.00020|0.14%|0.14392|-67.53%|0.14394|-67.51%|0.200|8.614|0.000|25.35 MB|
