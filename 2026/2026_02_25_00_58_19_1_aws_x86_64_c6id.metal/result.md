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
| Time          |2026-02-25 00:58:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22377115086 ([Artifacts](https://github.com/php/php-src/actions/runs/22377115086/artifacts/5646257309))|
| Changeset  |https://github.com/php/php-src/compare/b81686a108..5fc9d9d9a7|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39473|0.39667|0.00057|0.14%|0.39525|0.00%|0.39502|0.00%|1.549|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b81686a108)|0.38906|0.39140|0.00036|0.09%|0.38964|-1.42%|0.38955|-1.39%|2.866|8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/5fc9d9d9a7)|0.38975|0.39240|0.00042|0.11%|0.39011|-1.30%|0.38999|-1.27%|3.700|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5fc9d9d9a7)|0.36250|0.36431|0.00036|0.10%|0.36319|-8.11%|0.36316|-8.07%|1.107|8.614|0.000|25.40 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66885|0.67287|0.00072|0.11%|0.66973|0.00%|0.66948|0.00%|2.183|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b81686a108)|0.66089|0.66450|0.00064|0.10%|0.66163|-1.21%|0.66152|-1.19%|2.544|8.614|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/5fc9d9d9a7)|0.66424|0.66927|0.00076|0.11%|0.66577|-0.59%|0.66568|-0.57%|2.077|8.531|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5fc9d9d9a7)|0.63235|0.64005|0.00134|0.21%|0.63312|-5.47%|0.63278|-5.48%|4.371|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58749|0.59281|0.00135|0.23%|0.58989|0.00%|0.58979|0.00%|0.192|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b81686a108)|0.58533|0.58899|0.00066|0.11%|0.58612|-0.64%|0.58596|-0.65%|3.150|8.414|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/5fc9d9d9a7)|0.58707|0.59101|0.00072|0.12%|0.58817|-0.29%|0.58796|-0.31%|2.515|6.453|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5fc9d9d9a7)|0.51683|0.52124|0.00078|0.15%|0.51815|-12.16%|0.51795|-12.18%|2.670|8.614|0.000|25.41 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44143|0.44987|0.00119|0.27%|0.44295|0.00%|0.44276|0.00%|4.256|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b81686a108)|0.44446|0.44682|0.00050|0.11%|0.44567|0.61%|0.44567|0.66%|0.050|-8.200|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/5fc9d9d9a7)|0.44408|0.44677|0.00057|0.13%|0.44553|0.58%|0.44559|0.64%|-0.364|-8.180|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5fc9d9d9a7)|0.14348|0.14432|0.00022|0.15%|0.14383|-67.53%|0.14379|-67.52%|0.526|8.614|0.000|25.41 MB|
