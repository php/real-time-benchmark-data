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
| Time          |2026-03-15 01:02:23 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23100204036 ([Artifacts](https://github.com/php/php-src/actions/runs/23100204036/artifacts/5928382700))|
| Changeset  |https://github.com/php/php-src/compare/92ba1e4ea0..4561e92fa1|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39630|0.40149|0.00071|0.18%|0.39670|0.00%|0.39661|0.00%|6.496|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92ba1e4ea0)|0.39029|0.39245|0.00053|0.14%|0.39098|-1.44%|0.39089|-1.44%|1.600|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/4561e92fa1)|0.39174|0.39395|0.00041|0.10%|0.39228|-1.11%|0.39216|-1.12%|1.740|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4561e92fa1)|0.36551|0.36689|0.00032|0.09%|0.36613|-7.71%|0.36611|-7.69%|0.447|8.614|0.000|25.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67009|0.67169|0.00045|0.07%|0.67071|0.00%|0.67055|0.00%|0.700|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92ba1e4ea0)|0.66669|0.67382|0.00136|0.20%|0.66779|-0.44%|0.66749|-0.46%|2.820|7.621|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/4561e92fa1)|0.66668|0.66881|0.00044|0.07%|0.66735|-0.50%|0.66726|-0.49%|1.022|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4561e92fa1)|0.63726|0.65162|0.00200|0.31%|0.63806|-4.87%|0.63771|-4.90%|6.668|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58903|0.59462|0.00108|0.18%|0.59151|0.00%|0.59152|0.00%|0.088|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92ba1e4ea0)|0.58699|0.59112|0.00090|0.15%|0.58807|-0.58%|0.58786|-0.62%|2.233|8.300|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/4561e92fa1)|0.58714|0.59083|0.00090|0.15%|0.58823|-0.55%|0.58794|-0.61%|1.839|8.310|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4561e92fa1)|0.51696|0.52179|0.00085|0.16%|0.51831|-12.38%|0.51811|-12.41%|2.594|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44164|0.45061|0.00139|0.31%|0.44307|0.00%|0.44283|0.00%|3.793|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92ba1e4ea0)|0.44473|0.44674|0.00050|0.11%|0.44567|0.59%|0.44563|0.63%|0.113|-7.766|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/4561e92fa1)|0.44350|0.44782|0.00085|0.19%|0.44526|0.49%|0.44538|0.58%|0.230|-7.600|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4561e92fa1)|0.14362|0.14542|0.00026|0.18%|0.14391|-67.52%|0.14388|-67.51%|4.314|8.614|0.000|25.35 MB|
