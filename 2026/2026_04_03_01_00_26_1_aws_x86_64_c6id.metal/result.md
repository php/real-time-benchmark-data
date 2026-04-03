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
| Time          |2026-04-03 01:00:26 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23929040446 ([Artifacts](https://github.com/php/php-src/actions/runs/23929040446/artifacts/6253639925))|
| Changeset  |https://github.com/php/php-src/compare/75ed2091bc..660996662a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39794|0.40009|0.00036|0.09%|0.39842|0.00%|0.39836|0.00%|2.592|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75ed2091bc)|0.39126|0.39238|0.00022|0.06%|0.39164|-1.70%|0.39161|-1.69%|1.189|8.614|0.000|25.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/660996662a)|0.39114|0.39458|0.00068|0.17%|0.39203|-1.60%|0.39182|-1.64%|2.348|8.614|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/660996662a)|0.36529|0.36779|0.00051|0.14%|0.36637|-8.04%|0.36631|-8.04%|0.757|8.614|0.000|25.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67114|0.67455|0.00061|0.09%|0.67205|0.00%|0.67188|0.00%|1.674|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75ed2091bc)|0.66916|0.67331|0.00114|0.17%|0.67086|-0.18%|0.67057|-0.20%|0.631|5.484|0.000|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/660996662a)|0.66900|0.67277|0.00078|0.12%|0.67029|-0.26%|0.67011|-0.26%|1.252|7.594|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/660996662a)|0.64238|0.65882|0.00239|0.37%|0.64409|-4.16%|0.64363|-4.21%|5.323|8.614|0.000|25.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59067|0.59609|0.00111|0.19%|0.59307|0.00%|0.59281|0.00%|0.533|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75ed2091bc)|0.58704|0.59030|0.00074|0.13%|0.58792|-0.87%|0.58766|-0.87%|2.087|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/660996662a)|0.58759|0.59099|0.00065|0.11%|0.58846|-0.78%|0.58829|-0.76%|2.302|8.600|0.000|25.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/660996662a)|0.51907|0.52224|0.00081|0.16%|0.51991|-12.34%|0.51971|-12.33%|1.705|8.614|0.000|25.34 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44209|0.44507|0.00051|0.11%|0.44292|0.00%|0.44282|0.00%|1.652|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/75ed2091bc)|0.44395|0.44650|0.00057|0.13%|0.44551|0.59%|0.44563|0.63%|-0.770|-8.538|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/660996662a)|0.44456|0.44702|0.00053|0.12%|0.44580|0.65%|0.44577|0.67%|0.268|-8.600|0.000|25.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/660996662a)|0.14341|0.14539|0.00033|0.23%|0.14385|-67.52%|0.14379|-67.53%|2.689|8.614|0.000|25.34 MB|
