### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-02-10 01:02:17 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21847313288 ([Artifacts](https://github.com/php/php-src/actions/runs/21847313288/artifacts/5441745883))|
| Changeset  |https://github.com/php/php-src/compare/96be28cb0e..a760cf73f0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39673|0.39803|0.00028|0.07%|0.39708|0.00%|0.39702|0.00%|1.761|0.000|1.000|26.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96be28cb0e)|0.39078|0.39305|0.00051|0.13%|0.39129|-1.46%|0.39109|-1.49%|1.728|8.614|0.000|25.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/a760cf73f0)|0.39253|0.39442|0.00051|0.13%|0.39314|-0.99%|0.39297|-1.02%|1.076|8.614|0.000|25.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a760cf73f0)|0.36616|0.36974|0.00068|0.19%|0.36685|-7.61%|0.36661|-7.66%|2.534|8.614|0.000|25.59 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67771|0.67996|0.00061|0.09%|0.67852|0.00%|0.67832|0.00%|0.894|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96be28cb0e)|0.67374|0.68026|0.00114|0.17%|0.67515|-0.50%|0.67504|-0.48%|2.813|7.986|0.000|25.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/a760cf73f0)|0.67786|0.68061|0.00061|0.09%|0.67868|0.02%|0.67849|0.03%|1.355|-1.520|0.128|25.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a760cf73f0)|0.64502|0.65460|0.00162|0.25%|0.64602|-4.79%|0.64564|-4.82%|4.508|8.614|0.000|25.67 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58869|0.59374|0.00107|0.18%|0.59079|0.00%|0.59079|0.00%|0.210|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96be28cb0e)|0.58908|0.59396|0.00115|0.19%|0.59025|-0.09%|0.58988|-0.15%|2.246|3.154|0.002|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/a760cf73f0)|0.58893|0.59287|0.00070|0.12%|0.58987|-0.16%|0.58968|-0.19%|2.376|4.429|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a760cf73f0)|0.51850|0.52489|0.00131|0.25%|0.52007|-11.97%|0.51969|-12.04%|1.997|8.614|0.000|25.83 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44099|0.44709|0.00101|0.23%|0.44257|0.00%|0.44240|0.00%|2.163|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96be28cb0e)|0.44231|0.44600|0.00078|0.18%|0.44439|0.41%|0.44445|0.46%|-0.456|-7.435|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/a760cf73f0)|0.44346|0.44686|0.00071|0.16%|0.44485|0.52%|0.44477|0.53%|0.505|-7.938|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a760cf73f0)|0.14281|0.14402|0.00026|0.18%|0.14348|-67.58%|0.14348|-67.57%|-0.262|8.614|0.000|25.83 MB|
