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
| Time          |2026-03-16 01:01:37 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23123576691 ([Artifacts](https://github.com/php/php-src/actions/runs/23123576691/artifacts/5936005119))|
| Changeset  |https://github.com/php/php-src/compare/4561e92fa1..3927630e62|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39647|0.39829|0.00031|0.08%|0.39684|0.00%|0.39680|0.00%|2.699|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4561e92fa1)|0.39174|0.39395|0.00044|0.11%|0.39232|-1.14%|0.39226|-1.15%|2.301|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/3927630e62)|0.39188|0.39418|0.00042|0.11%|0.39244|-1.11%|0.39231|-1.13%|2.084|8.614|0.000|25.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3927630e62)|0.36550|0.36752|0.00041|0.11%|0.36623|-7.71%|0.36616|-7.72%|1.438|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67057|0.67246|0.00051|0.08%|0.67132|0.00%|0.67123|0.00%|0.682|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4561e92fa1)|0.66669|0.66842|0.00042|0.06%|0.66745|-0.58%|0.66736|-0.58%|0.545|8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/3927630e62)|0.66674|0.66892|0.00038|0.06%|0.66740|-0.58%|0.66732|-0.58%|1.403|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3927630e62)|0.63755|0.64659|0.00147|0.23%|0.63843|-4.90%|0.63801|-4.95%|4.224|8.614|0.000|25.27 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59002|0.59434|0.00107|0.18%|0.59154|0.00%|0.59139|0.00%|0.592|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4561e92fa1)|0.58677|0.59083|0.00071|0.12%|0.58775|-0.64%|0.58763|-0.64%|3.010|8.448|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/3927630e62)|0.58649|0.59101|0.00088|0.15%|0.58807|-0.59%|0.58788|-0.59%|2.021|8.310|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3927630e62)|0.51682|0.52041|0.00048|0.09%|0.51790|-12.45%|0.51785|-12.44%|2.846|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44174|0.44405|0.00058|0.13%|0.44288|0.00%|0.44295|0.00%|0.053|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4561e92fa1)|0.44243|0.44905|0.00101|0.23%|0.44520|0.52%|0.44510|0.48%|0.762|-8.242|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/3927630e62)|0.44340|0.44637|0.00073|0.16%|0.44522|0.53%|0.44519|0.51%|-0.564|-8.448|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3927630e62)|0.14350|0.14429|0.00019|0.13%|0.14392|-67.50%|0.14391|-67.51%|-0.054|8.614|0.000|25.27 MB|
