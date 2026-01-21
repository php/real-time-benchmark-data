### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-21 00:50:29 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21192948075 ([Artifacts](#ARTIFACT_URL#))|
| Changeset  |https://github.com/php/php-src/compare/b17b699c69..aeb8524584|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45119|0.45877|0.00119|0.26%|0.45198|0.00%|0.45177|0.00%|5.114|0.999|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b17b699c69)|0.44593|0.45335|0.00076|0.17%|0.44684|-1.14%|0.44671|-1.12%|6.506|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/aeb8524584)|0.44554|0.44720|0.00032|0.07%|0.44619|-1.28%|0.44614|-1.25%|1.054|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aeb8524584)|0.42682|0.42840|0.00031|0.07%|0.42733|-5.45%|0.42727|-5.42%|1.477|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.76964|0.78681|0.00226|0.29%|0.77469|0.00%|0.77422|0.00%|4.417|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b17b699c69)|0.77070|0.78384|0.00135|0.17%|0.77194|-0.35%|0.77170|-0.33%|7.186|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/aeb8524584)|0.76143|0.77190|0.00156|0.20%|0.76902|-0.73%|0.76943|-0.62%|-2.071|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aeb8524584)|1.01415|1.20003|0.02248|1.91%|1.17988|52.30%|1.18555|53.13%|-5.071|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65906|0.67981|0.00201|0.30%|0.66021|0.00%|0.65998|0.00%|9.502|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b17b699c69)|0.66453|0.68447|0.00271|0.41%|0.66580|0.85%|0.66538|0.82%|6.682|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/aeb8524584)|0.66507|0.68751|0.00288|0.43%|0.66635|0.93%|0.66590|0.90%|6.814|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aeb8524584)|0.59218|0.59458|0.00039|0.07%|0.59327|-10.14%|0.59327|-10.11%|0.483|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42522|0.43677|0.00162|0.38%|0.42830|0.00%|0.42815|0.00%|1.637|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b17b699c69)|0.42351|0.44358|0.00223|0.52%|0.42676|-0.36%|0.42653|-0.38%|4.363|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/aeb8524584)|0.42287|0.43107|0.00143|0.34%|0.42625|-0.48%|0.42598|-0.51%|0.737|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/aeb8524584)|0.13751|0.14420|0.00116|0.82%|0.14058|-67.18%|0.14034|-67.22%|0.594|0.000|27.01 MB|
