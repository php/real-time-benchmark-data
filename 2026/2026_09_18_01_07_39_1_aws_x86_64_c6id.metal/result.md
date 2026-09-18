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
| Time          |2026-09-18 01:07:39 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35294028945 ([Artifacts](https://github.com/php/php-src/actions/runs/35294028945/artifacts/10527628462))|
| Changeset  |https://github.com/php/php-src/compare/ad4cb0ebd0..703b5bb37a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39898|0.40328|0.00061|0.15%|0.39947|0.00%|0.39935|0.00%|5.295|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cb0ebd0)|0.37460|0.37783|0.00045|0.12%|0.37510|-6.10%|0.37503|-6.09%|4.979|8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/703b5bb37a)|0.37410|0.37539|0.00028|0.08%|0.37450|-6.25%|0.37444|-6.24%|1.457|8.614|0.000|25.90 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68065|0.68489|0.00080|0.12%|0.68163|0.00%|0.68139|0.00%|1.820|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cb0ebd0)|0.67298|0.67511|0.00040|0.06%|0.67376|-1.15%|0.67370|-1.13%|1.002|8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/703b5bb37a)|0.66984|0.67353|0.00074|0.11%|0.67080|-1.59%|0.67065|-1.58%|2.048|8.614|0.000|26.28 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59091|0.59499|0.00092|0.16%|0.59236|0.00%|0.59229|0.00%|0.983|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cb0ebd0)|0.58981|0.59755|0.00123|0.21%|0.59135|-0.17%|0.59114|-0.19%|2.886|5.487|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/703b5bb37a)|0.58883|0.59197|0.00055|0.09%|0.58963|-0.46%|0.58961|-0.45%|2.485|8.373|0.000|26.21 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44386|0.44772|0.00061|0.14%|0.44489|0.00%|0.44491|0.00%|1.952|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ad4cb0ebd0)|0.45183|0.45398|0.00047|0.10%|0.45282|1.78%|0.45290|1.80%|-0.217|-8.614|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/703b5bb37a)|0.45086|0.45302|0.00045|0.10%|0.45210|1.62%|0.45213|1.62%|-0.324|-8.614|0.000|26.21 MB|
