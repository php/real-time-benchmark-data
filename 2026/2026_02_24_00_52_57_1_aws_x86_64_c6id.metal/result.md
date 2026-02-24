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
| Time          |2026-02-24 00:52:57 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22331709902 ([Artifacts](https://github.com/php/php-src/actions/runs/22331709902/artifacts/5627769603))|
| Changeset  |https://github.com/php/php-src/compare/5f87a6e5b6..b81686a108|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39450|0.39533|0.00015|0.04%|0.39480|0.00%|0.39479|0.00%|1.202|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5f87a6e5b6)|0.38903|0.39131|0.00046|0.12%|0.38953|-1.34%|0.38941|-1.36%|2.368|8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/b81686a108)|0.38912|0.39298|0.00064|0.16%|0.38977|-1.27%|0.38959|-1.32%|2.960|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b81686a108)|0.36050|0.36219|0.00034|0.09%|0.36113|-8.53%|0.36107|-8.54%|0.781|8.614|0.000|25.38 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66633|0.67061|0.00068|0.10%|0.66697|0.00%|0.66677|0.00%|3.326|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5f87a6e5b6)|0.65843|0.66032|0.00041|0.06%|0.65914|-1.17%|0.65901|-1.16%|1.028|8.614|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/b81686a108)|0.65868|0.66015|0.00038|0.06%|0.65925|-1.16%|0.65916|-1.14%|0.838|8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b81686a108)|0.62797|0.62913|0.00024|0.04%|0.62841|-5.78%|0.62839|-5.76%|0.984|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58796|0.59169|0.00094|0.16%|0.58986|0.00%|0.58989|0.00%|0.059|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5f87a6e5b6)|0.58570|0.58897|0.00057|0.10%|0.58618|-0.62%|0.58604|-0.65%|3.710|8.531|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/b81686a108)|0.58549|0.58932|0.00072|0.12%|0.58651|-0.57%|0.58631|-0.61%|2.759|8.393|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b81686a108)|0.51648|0.52031|0.00066|0.13%|0.51746|-12.27%|0.51734|-12.30%|3.017|8.614|0.000|25.41 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44180|0.44398|0.00051|0.12%|0.44280|0.00%|0.44277|0.00%|0.258|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/5f87a6e5b6)|0.44464|0.44658|0.00045|0.10%|0.44569|0.65%|0.44574|0.67%|-0.322|-8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/b81686a108)|0.44447|0.44685|0.00046|0.10%|0.44569|0.65%|0.44574|0.67%|0.027|-8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b81686a108)|0.14344|0.14432|0.00018|0.13%|0.14380|-67.53%|0.14378|-67.53%|0.460|8.614|0.000|25.41 MB|
