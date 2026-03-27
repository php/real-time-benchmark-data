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
| Time          |2026-03-27 01:00:07 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23625776708 ([Artifacts](https://github.com/php/php-src/actions/runs/23625776708/artifacts/6136433442))|
| Changeset  |https://github.com/php/php-src/compare/1655d57751..8df516c2cd|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39445|0.39547|0.00020|0.05%|0.39490|0.00%|0.39487|0.00%|0.366|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1655d57751)|0.38745|0.38870|0.00028|0.07%|0.38779|-1.80%|0.38775|-1.80%|1.904|8.614|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/8df516c2cd)|0.38789|0.39389|0.00097|0.25%|0.38975|-1.30%|0.38983|-1.28%|1.515|8.614|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8df516c2cd)|0.36029|0.36507|0.00097|0.27%|0.36152|-8.45%|0.36128|-8.51%|1.410|8.614|0.000|25.35 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66879|0.67038|0.00041|0.06%|0.66942|0.00%|0.66930|0.00%|0.720|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1655d57751)|0.66520|0.66829|0.00049|0.07%|0.66580|-0.54%|0.66565|-0.54%|2.928|8.614|0.000|25.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/8df516c2cd)|0.66439|0.66638|0.00047|0.07%|0.66515|-0.64%|0.66513|-0.62%|0.550|8.614|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8df516c2cd)|0.63454|0.63634|0.00040|0.06%|0.63508|-5.13%|0.63499|-5.13%|1.203|8.614|0.000|25.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58679|0.59226|0.00100|0.17%|0.58977|0.00%|0.58966|0.00%|0.091|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1655d57751)|0.58493|0.58943|0.00102|0.17%|0.58619|-0.61%|0.58589|-0.64%|2.377|8.111|0.000|25.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/8df516c2cd)|0.58463|0.58813|0.00081|0.14%|0.58573|-0.68%|0.58545|-0.71%|1.675|8.566|0.000|25.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8df516c2cd)|0.51351|0.51880|0.00090|0.17%|0.51498|-12.68%|0.51483|-12.69%|2.868|8.614|0.000|25.34 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44189|0.44409|0.00051|0.11%|0.44286|0.00%|0.44284|0.00%|0.353|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1655d57751)|0.44471|0.44792|0.00056|0.13%|0.44580|0.66%|0.44581|0.67%|1.017|-8.614|0.000|25.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/8df516c2cd)|0.44333|0.44635|0.00064|0.14%|0.44516|0.52%|0.44520|0.53%|-0.414|-8.559|0.000|25.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8df516c2cd)|0.14345|0.14523|0.00029|0.20%|0.14404|-67.48%|0.14399|-67.48%|1.411|8.614|0.000|25.34 MB|
