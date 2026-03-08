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
| Time          |2026-03-08 00:55:40 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22810801179 ([Artifacts](https://github.com/php/php-src/actions/runs/22810801179/artifacts/5814861848))|
| Changeset  |https://github.com/php/php-src/compare/f99ca6347f..eedbffec2e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39447|0.39666|0.00029|0.07%|0.39503|0.00%|0.39503|0.00%|3.686|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99ca6347f)|0.38861|0.39205|0.00054|0.14%|0.38926|-1.46%|0.38913|-1.49%|3.223|8.614|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/eedbffec2e)|0.38891|0.39037|0.00035|0.09%|0.38941|-1.42%|0.38933|-1.44%|1.059|8.614|0.000|25.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eedbffec2e)|0.36103|0.36275|0.00039|0.11%|0.36163|-8.46%|0.36154|-8.48%|1.132|8.614|0.000|25.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66758|0.66946|0.00037|0.06%|0.66832|0.00%|0.66827|0.00%|0.683|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99ca6347f)|0.66489|0.66738|0.00043|0.06%|0.66552|-0.42%|0.66537|-0.43%|2.101|8.614|0.000|25.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/eedbffec2e)|0.66581|0.66835|0.00050|0.08%|0.66650|-0.27%|0.66641|-0.28%|1.856|8.276|0.000|25.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eedbffec2e)|0.63484|0.64245|0.00109|0.17%|0.63558|-4.90%|0.63535|-4.93%|5.495|8.614|0.000|25.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58773|0.59243|0.00101|0.17%|0.58981|0.00%|0.58971|0.00%|0.442|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99ca6347f)|0.58525|0.58871|0.00093|0.16%|0.58638|-0.58%|0.58608|-0.62%|1.468|8.441|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/eedbffec2e)|0.58481|0.58841|0.00074|0.13%|0.58567|-0.70%|0.58547|-0.72%|2.365|8.572|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eedbffec2e)|0.51489|0.51820|0.00082|0.16%|0.51590|-12.53%|0.51565|-12.56%|1.820|8.614|0.000|25.32 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44184|0.44373|0.00042|0.09%|0.44273|0.00%|0.44273|0.00%|0.190|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99ca6347f)|0.44464|0.44840|0.00062|0.14%|0.44593|0.72%|0.44583|0.70%|1.116|-8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/eedbffec2e)|0.44378|0.44667|0.00068|0.15%|0.44526|0.57%|0.44535|0.59%|-0.149|-8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eedbffec2e)|0.14349|0.14427|0.00017|0.12%|0.14383|-67.51%|0.14385|-67.51%|0.285|8.614|0.000|25.32 MB|
