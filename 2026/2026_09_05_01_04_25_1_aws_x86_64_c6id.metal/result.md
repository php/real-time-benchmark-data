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
| Binary layout strategy |none|
| Time          |2026-09-05 01:04:25 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33935004403 ([Artifacts](https://github.com/php/php-src/actions/runs/33935004403/artifacts/9960357318))|
| Changeset  |https://github.com/php/php-src/compare/0bf872bebf..1053403d9a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39908|0.40063|0.00024|0.06%|0.39947|0.00%|0.39943|0.00%|2.511|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0bf872bebf)|0.37303|0.37405|0.00020|0.05%|0.37339|-6.53%|0.37336|-6.53%|0.772|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/1053403d9a)|0.37392|0.37540|0.00037|0.10%|0.37440|-6.28%|0.37429|-6.29%|1.300|8.614|0.000|25.83 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68035|0.68389|0.00087|0.13%|0.68175|0.00%|0.68176|0.00%|0.476|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0bf872bebf)|0.66674|0.66847|0.00039|0.06%|0.66743|-2.10%|0.66732|-2.12%|0.909|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/1053403d9a)|0.66841|0.67371|0.00079|0.12%|0.66939|-1.81%|0.66922|-1.84%|3.976|8.614|0.000|25.80 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59110|0.59455|0.00094|0.16%|0.59248|0.00%|0.59235|0.00%|0.650|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0bf872bebf)|0.58999|0.59740|0.00105|0.18%|0.59098|-0.25%|0.59076|-0.27%|4.924|7.607|0.000|26.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/1053403d9a)|0.59076|0.59807|0.00113|0.19%|0.59195|-0.09%|0.59162|-0.12%|3.687|3.712|0.000|26.14 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44408|0.44958|0.00109|0.24%|0.44506|0.00%|0.44479|0.00%|2.682|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0bf872bebf)|0.45009|0.45200|0.00054|0.12%|0.45108|1.35%|0.45106|1.41%|-0.080|-8.614|0.000|26.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/1053403d9a)|0.45030|0.45370|0.00061|0.14%|0.45131|1.41%|0.45125|1.45%|2.122|-8.614|0.000|26.14 MB|
