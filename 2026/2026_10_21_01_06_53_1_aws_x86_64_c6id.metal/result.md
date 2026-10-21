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
| Time          |2026-10-21 01:06:53 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/39525344092 ([Artifacts](https://github.com/php/php-src/actions/runs/39525344092/artifacts/12314641360))|
| Changeset  |https://github.com/php/php-src/compare/a17dcadd4c..b9ea38ef63|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39902|0.40097|0.00039|0.10%|0.39943|0.00%|0.39935|0.00%|2.506|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a17dcadd4c)|0.37943|0.38057|0.00027|0.07%|0.37991|-4.89%|0.37984|-4.89%|0.745|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9ea38ef63)|0.38031|0.38357|0.00056|0.15%|0.38085|-4.65%|0.38074|-4.66%|3.174|8.614|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9ea38ef63)|0.35309|0.35566|0.00049|0.14%|0.35394|-11.39%|0.35379|-11.41%|1.010|8.614|0.000|26.19 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68033|0.68974|0.00140|0.21%|0.68187|0.00%|0.68163|0.00%|3.761|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a17dcadd4c)|0.67765|0.68154|0.00063|0.09%|0.67872|-0.46%|0.67858|-0.45%|2.046|8.448|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9ea38ef63)|0.67329|0.68459|0.00214|0.32%|0.67502|-1.00%|0.67409|-1.11%|2.502|8.276|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9ea38ef63)|0.63891|0.64251|0.00050|0.08%|0.63988|-6.16%|0.63987|-6.13%|2.966|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59124|0.59670|0.00092|0.15%|0.59276|0.00%|0.59265|0.00%|1.856|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a17dcadd4c)|0.59177|0.59534|0.00070|0.12%|0.59268|-0.01%|0.59252|-0.02%|1.717|0.290|0.772|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9ea38ef63)|0.58990|0.59510|0.00120|0.20%|0.59096|-0.30%|0.59061|-0.34%|2.510|7.221|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9ea38ef63)|0.51873|0.52264|0.00071|0.14%|0.51955|-12.35%|0.51945|-12.35%|2.854|8.614|0.000|26.37 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44349|0.44593|0.00051|0.12%|0.44458|0.00%|0.44446|0.00%|0.482|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a17dcadd4c)|0.45183|0.45411|0.00047|0.10%|0.45298|1.89%|0.45299|1.92%|0.320|-8.614|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/b9ea38ef63)|0.45149|0.45399|0.00051|0.11%|0.45292|1.88%|0.45297|1.91%|-0.380|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b9ea38ef63)|0.14404|0.14825|0.00076|0.52%|0.14461|-67.47%|0.14449|-67.49%|4.092|8.614|0.000|26.37 MB|
