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
| Time          |2026-04-22 01:04:12 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24754656040 ([Artifacts](https://github.com/php/php-src/actions/runs/24754656040/artifacts/6569010448))|
| Changeset  |https://github.com/php/php-src/compare/e07d06684e..239a8bed9b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39985|0.40219|0.00067|0.17%|0.40054|0.00%|0.40029|0.00%|1.198|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e07d06684e)|0.39257|0.39391|0.00030|0.08%|0.39309|-1.86%|0.39303|-1.81%|1.246|8.614|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/239a8bed9b)|0.39256|0.39452|0.00039|0.10%|0.39310|-1.86%|0.39303|-1.81%|1.498|8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/239a8bed9b)|0.36516|0.36738|0.00055|0.15%|0.36594|-8.64%|0.36577|-8.62%|1.300|8.614|0.000|25.40 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67386|0.67677|0.00054|0.08%|0.67467|0.00%|0.67453|0.00%|1.622|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e07d06684e)|0.66906|0.67229|0.00064|0.10%|0.66982|-0.72%|0.66980|-0.70%|1.629|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/239a8bed9b)|0.67005|0.67373|0.00074|0.11%|0.67071|-0.59%|0.67046|-0.60%|2.706|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/239a8bed9b)|0.63746|0.64974|0.00254|0.40%|0.63920|-5.26%|0.63801|-5.41%|2.153|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59279|0.59733|0.00100|0.17%|0.59441|0.00%|0.59423|0.00%|0.682|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e07d06684e)|0.59002|0.59278|0.00059|0.10%|0.59091|-0.59%|0.59075|-0.59%|1.826|8.614|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/239a8bed9b)|0.59021|0.59308|0.00054|0.09%|0.59088|-0.59%|0.59075|-0.59%|2.486|8.572|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/239a8bed9b)|0.52165|0.52489|0.00052|0.10%|0.52269|-12.07%|0.52265|-12.05%|2.604|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44146|0.44570|0.00072|0.16%|0.44292|0.00%|0.44293|0.00%|1.088|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e07d06684e)|0.44577|0.44859|0.00058|0.13%|0.44690|0.90%|0.44685|0.88%|0.349|-8.614|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/239a8bed9b)|0.44559|0.44760|0.00047|0.11%|0.44680|0.88%|0.44680|0.87%|-0.389|-8.600|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/239a8bed9b)|0.14329|0.14405|0.00018|0.13%|0.14364|-67.57%|0.14363|-67.57%|0.158|8.614|0.000|25.39 MB|
