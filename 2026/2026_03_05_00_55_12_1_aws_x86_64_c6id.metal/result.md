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
| Time          |2026-03-05 00:55:12 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22696965406 ([Artifacts](https://github.com/php/php-src/actions/runs/22696965406/artifacts/5771574199))|
| Changeset  |https://github.com/php/php-src/compare/7a1c2612c0..11a95749b1|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39642|0.39736|0.00018|0.05%|0.39676|0.00%|0.39675|0.00%|0.940|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7a1c2612c0)|0.39038|0.39380|0.00053|0.13%|0.39085|-1.49%|0.39074|-1.51%|4.068|8.614|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/11a95749b1)|0.39053|0.39343|0.00046|0.12%|0.39095|-1.46%|0.39082|-1.49%|3.559|8.614|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11a95749b1)|0.36273|0.36636|0.00056|0.15%|0.36355|-8.37%|0.36343|-8.40%|2.978|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66914|0.67246|0.00066|0.10%|0.67001|0.00%|0.66978|0.00%|1.790|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7a1c2612c0)|0.66641|0.66985|0.00067|0.10%|0.66705|-0.44%|0.66682|-0.44%|2.623|8.400|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/11a95749b1)|0.66621|0.66831|0.00038|0.06%|0.66683|-0.47%|0.66673|-0.45%|1.842|8.614|0.000|25.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11a95749b1)|0.63469|0.63819|0.00054|0.09%|0.63542|-5.16%|0.63534|-5.14%|3.141|8.614|0.000|25.33 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59009|0.59412|0.00093|0.16%|0.59164|0.00%|0.59160|0.00%|0.560|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7a1c2612c0)|0.58760|0.59059|0.00066|0.11%|0.58822|-0.58%|0.58800|-0.61%|2.374|8.531|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/11a95749b1)|0.58754|0.59098|0.00073|0.12%|0.58817|-0.59%|0.58799|-0.61%|3.038|8.400|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11a95749b1)|0.51786|0.52139|0.00076|0.15%|0.51851|-12.36%|0.51828|-12.39%|2.755|8.614|0.000|25.60 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44152|0.44489|0.00061|0.14%|0.44286|0.00%|0.44282|0.00%|0.680|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7a1c2612c0)|0.44480|0.44705|0.00050|0.11%|0.44588|0.68%|0.44591|0.70%|0.004|-8.607|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/11a95749b1)|0.44448|0.44706|0.00052|0.12%|0.44583|0.67%|0.44593|0.70%|-0.235|-8.600|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/11a95749b1)|0.14336|0.14470|0.00026|0.18%|0.14386|-67.52%|0.14382|-67.52%|1.096|8.614|0.000|25.65 MB|
