### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-06-18 01:33:03 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27730853184 ([Artifacts](https://github.com/php/php-src/actions/runs/27730853184/artifacts/7712723765))|
| Changeset  |https://github.com/php/php-src/compare/cbc089a29e..2efafdb11d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39460|0.39715|0.00081|0.20%|0.39534|0.00%|0.39491|0.00%|0.986|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cbc089a29e)|0.38730|0.38857|0.00025|0.06%|0.38769|-1.93%|0.38767|-1.83%|1.396|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/2efafdb11d)|0.38867|0.39039|0.00038|0.10%|0.38919|-1.56%|0.38910|-1.47%|1.634|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2efafdb11d)|0.35820|0.36008|0.00042|0.12%|0.35899|-9.19%|0.35890|-9.12%|0.715|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67251|0.67539|0.00075|0.11%|0.67328|0.00%|0.67302|0.00%|1.437|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cbc089a29e)|0.66520|0.66741|0.00055|0.08%|0.66588|-1.10%|0.66567|-1.09%|1.014|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/2efafdb11d)|0.66553|0.66940|0.00071|0.11%|0.66645|-1.01%|0.66623|-1.01%|2.364|8.614|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2efafdb11d)|0.63221|0.63420|0.00040|0.06%|0.63266|-6.03%|0.63262|-6.00%|1.897|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58900|0.59308|0.00094|0.16%|0.59058|0.00%|0.59045|0.00%|0.700|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cbc089a29e)|0.58600|0.58990|0.00072|0.12%|0.58710|-0.59%|0.58701|-0.58%|2.155|8.510|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/2efafdb11d)|0.58736|0.59120|0.00077|0.13%|0.58816|-0.41%|0.58793|-0.43%|2.436|7.959|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2efafdb11d)|0.51835|0.52275|0.00132|0.25%|0.51967|-12.01%|0.51911|-12.08%|1.648|8.614|0.000|26.22 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44355|0.45172|0.00113|0.26%|0.44460|0.00%|0.44453|0.00%|5.190|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cbc089a29e)|0.44929|0.45151|0.00052|0.12%|0.45033|1.29%|0.45024|1.29%|0.572|-8.269|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/2efafdb11d)|0.44919|0.45193|0.00051|0.11%|0.45044|1.31%|0.45045|1.33%|0.339|-8.283|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2efafdb11d)|0.14431|0.14603|0.00026|0.18%|0.14470|-67.45%|0.14468|-67.45%|2.853|8.614|0.000|26.22 MB|
