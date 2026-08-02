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
| Time          |2026-08-02 01:04:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30726359747 ([Artifacts](https://github.com/php/php-src/actions/runs/30726359747/artifacts/8827001798))|
| Changeset  |https://github.com/php/php-src/compare/949fdc41d9..b74e0f749d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40041|0.40362|0.00046|0.11%|0.40085|0.00%|0.40076|0.00%|4.825|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/949fdc41d9)|0.39329|0.39514|0.00039|0.10%|0.39383|-1.75%|0.39372|-1.76%|1.422|8.614|0.000|25.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/b74e0f749d)|0.39211|0.39391|0.00038|0.10%|0.39256|-2.07%|0.39247|-2.07%|1.730|8.614|0.000|25.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b74e0f749d)|0.36361|0.36545|0.00043|0.12%|0.36421|-9.14%|0.36410|-9.15%|0.915|8.614|0.000|25.76 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67995|0.68312|0.00079|0.12%|0.68147|0.00%|0.68151|0.00%|0.142|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/949fdc41d9)|0.67147|0.67738|0.00100|0.15%|0.67229|-1.35%|0.67205|-1.39%|3.987|8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/b74e0f749d)|0.66919|0.67259|0.00061|0.09%|0.66970|-1.73%|0.66954|-1.76%|3.119|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b74e0f749d)|0.63659|0.64886|0.00169|0.27%|0.63744|-6.46%|0.63716|-6.51%|6.514|8.614|0.000|26.16 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59180|0.59584|0.00103|0.17%|0.59395|0.00%|0.59375|0.00%|0.051|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/949fdc41d9)|0.58961|0.59321|0.00079|0.13%|0.59068|-0.55%|0.59048|-0.55%|1.374|8.414|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/b74e0f749d)|0.58929|0.59330|0.00109|0.18%|0.59070|-0.55%|0.59045|-0.56%|1.162|8.166|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b74e0f749d)|0.52069|0.52559|0.00086|0.17%|0.52174|-12.16%|0.52167|-12.14%|2.490|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44361|0.44842|0.00081|0.18%|0.44478|0.00%|0.44462|0.00%|1.966|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/949fdc41d9)|0.44949|0.45280|0.00047|0.10%|0.45014|1.20%|0.45007|1.23%|3.869|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/b74e0f749d)|0.44910|0.45054|0.00030|0.07%|0.44978|1.12%|0.44976|1.16%|0.240|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b74e0f749d)|0.14420|0.14504|0.00019|0.13%|0.14461|-67.49%|0.14461|-67.48%|0.199|8.614|0.000|26.26 MB|
