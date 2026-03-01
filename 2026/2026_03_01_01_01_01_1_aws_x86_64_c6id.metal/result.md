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
| Time          |2026-03-01 01:01:01 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22532790687 ([Artifacts](https://github.com/php/php-src/actions/runs/22532790687/artifacts/5706913370))|
| Changeset  |https://github.com/php/php-src/compare/c68ede953a..2fd3433ed0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39675|0.39758|0.00017|0.04%|0.39710|0.00%|0.39710|0.00%|0.583|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c68ede953a)|0.39149|0.39338|0.00041|0.10%|0.39211|-1.26%|0.39198|-1.29%|1.406|8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/2fd3433ed0)|0.39173|0.39461|0.00056|0.14%|0.39238|-1.19%|0.39219|-1.24%|1.989|8.614|0.000|25.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2fd3433ed0)|0.36382|0.36542|0.00035|0.09%|0.36456|-8.19%|0.36449|-8.21%|0.803|8.614|0.000|25.40 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67086|0.67327|0.00057|0.08%|0.67166|0.00%|0.67147|0.00%|0.997|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c68ede953a)|0.66755|0.67471|0.00105|0.16%|0.66838|-0.49%|0.66816|-0.49%|4.852|8.269|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/2fd3433ed0)|0.66750|0.66963|0.00041|0.06%|0.66796|-0.55%|0.66785|-0.54%|1.949|8.614|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2fd3433ed0)|0.63743|0.64084|0.00057|0.09%|0.63799|-5.01%|0.63790|-5.00%|3.205|8.614|0.000|25.37 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58899|0.59513|0.00122|0.21%|0.59171|0.00%|0.59180|0.00%|0.060|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c68ede953a)|0.58809|0.59635|0.00122|0.21%|0.58901|-0.46%|0.58870|-0.52%|4.882|7.959|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/2fd3433ed0)|0.58827|0.59164|0.00078|0.13%|0.58921|-0.42%|0.58897|-0.48%|2.026|7.835|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2fd3433ed0)|0.51905|0.53004|0.00152|0.29%|0.52002|-12.12%|0.51980|-12.17%|6.134|8.614|0.000|25.33 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44128|0.44975|0.00112|0.25%|0.44300|0.00%|0.44294|0.00%|4.563|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c68ede953a)|0.44450|0.44705|0.00062|0.14%|0.44566|0.60%|0.44566|0.61%|0.372|-8.269|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/2fd3433ed0)|0.44418|0.44875|0.00068|0.15%|0.44574|0.62%|0.44564|0.61%|1.467|-8.269|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2fd3433ed0)|0.14356|0.14470|0.00026|0.18%|0.14396|-67.50%|0.14393|-67.50%|0.689|8.614|0.000|25.33 MB|
