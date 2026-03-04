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
| Time          |2026-03-04 00:53:22 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22649922323 ([Artifacts](https://github.com/php/php-src/actions/runs/22649922323/artifacts/5752180241))|
| Changeset  |https://github.com/php/php-src/compare/2fd3433ed0..7a1c2612c0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39424|0.39498|0.00016|0.04%|0.39468|0.00%|0.39467|0.00%|-0.133|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2fd3433ed0)|0.38914|0.39012|0.00022|0.06%|0.38954|-1.30%|0.38951|-1.31%|0.803|8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/7a1c2612c0)|0.38858|0.39089|0.00038|0.10%|0.38895|-1.45%|0.38887|-1.47%|3.297|8.614|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7a1c2612c0)|0.36072|0.36397|0.00059|0.16%|0.36128|-8.46%|0.36105|-8.52%|2.418|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66672|0.66907|0.00057|0.09%|0.66726|0.00%|0.66700|0.00%|1.538|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2fd3433ed0)|0.66435|0.66816|0.00057|0.09%|0.66512|-0.32%|0.66502|-0.30%|3.498|8.317|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/7a1c2612c0)|0.66392|0.66886|0.00085|0.13%|0.66480|-0.37%|0.66459|-0.36%|3.177|8.000|0.000|25.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7a1c2612c0)|0.63238|0.66461|0.00450|0.71%|0.63369|-5.03%|0.63294|-5.11%|6.887|8.614|0.000|25.33 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58773|0.59289|0.00114|0.19%|0.58982|0.00%|0.58993|0.00%|0.087|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2fd3433ed0)|0.58610|0.58994|0.00083|0.14%|0.58700|-0.48%|0.58673|-0.54%|2.257|8.021|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/7a1c2612c0)|0.58542|0.58924|0.00067|0.11%|0.58607|-0.64%|0.58593|-0.68%|3.496|8.435|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7a1c2612c0)|0.51484|0.51828|0.00079|0.15%|0.51562|-12.58%|0.51539|-12.63%|2.605|8.614|0.000|25.60 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44154|0.44473|0.00061|0.14%|0.44268|0.00%|0.44270|0.00%|0.943|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2fd3433ed0)|0.44382|0.44684|0.00062|0.14%|0.44563|0.67%|0.44560|0.66%|-0.442|-8.579|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/7a1c2612c0)|0.44478|0.44759|0.00060|0.14%|0.44580|0.70%|0.44569|0.67%|0.667|-8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7a1c2612c0)|0.14335|0.14428|0.00017|0.12%|0.14379|-67.52%|0.14381|-67.52%|-0.062|8.614|0.000|25.65 MB|
