### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-11-12 00:46:48 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/43129750125 ([Artifacts](https://github.com/php/php-src/actions/runs/43129750125/artifacts/13906009066))|
| Changeset  |https://github.com/php/php-src/compare/2545a971f9..8eb02dbaa3|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39742|0.39905|0.00027|0.07%|0.39777|0.00%|0.39773|0.00%|2.406|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2545a971f9)|0.37898|0.37986|0.00021|0.06%|0.37932|-4.64%|0.37927|-4.64%|0.699|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/8eb02dbaa3)|0.37952|0.38213|0.00040|0.10%|0.37989|-4.49%|0.37981|-4.51%|4.044|8.614|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8eb02dbaa3)|0.35357|0.35460|0.00024|0.07%|0.35394|-11.02%|0.35393|-11.01%|0.708|8.614|0.000|26.27 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67717|0.70814|0.00447|0.66%|0.67886|0.00%|0.67778|0.00%|6.079|0.000|1.000|26.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2545a971f9)|0.67837|0.67984|0.00041|0.06%|0.67895|0.01%|0.67891|0.17%|0.527|-5.794|0.000|26.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/8eb02dbaa3)|0.67781|0.67924|0.00032|0.05%|0.67833|-0.08%|0.67825|0.07%|0.971|-3.798|0.000|26.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8eb02dbaa3)|0.64999|0.65245|0.00041|0.06%|0.65050|-4.18%|0.65046|-4.03%|2.412|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59094|0.59440|0.00081|0.14%|0.59239|0.00%|0.59219|0.00%|0.633|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2545a971f9)|0.58906|0.59160|0.00049|0.08%|0.58976|-0.44%|0.58972|-0.42%|1.743|8.545|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/8eb02dbaa3)|0.58829|0.59173|0.00056|0.10%|0.58917|-0.54%|0.58907|-0.53%|2.552|8.545|0.000|26.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8eb02dbaa3)|0.51543|0.52617|0.00147|0.29%|0.51633|-12.84%|0.51607|-12.85%|6.296|8.614|0.000|26.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44384|0.44654|0.00056|0.13%|0.44481|0.00%|0.44476|0.00%|0.841|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2545a971f9)|0.45281|0.45563|0.00065|0.14%|0.45418|2.11%|0.45422|2.13%|0.007|-8.614|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/8eb02dbaa3)|0.45298|0.45604|0.00069|0.15%|0.45444|2.17%|0.45438|2.16%|0.110|-8.614|0.000|26.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8eb02dbaa3)|0.14671|0.14946|0.00054|0.37%|0.14737|-66.87%|0.14726|-66.89%|2.822|8.614|0.000|26.39 MB|
