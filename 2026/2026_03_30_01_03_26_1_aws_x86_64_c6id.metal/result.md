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
| Time          |2026-03-30 01:03:26 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23723494164 ([Artifacts](https://github.com/php/php-src/actions/runs/23723494164/artifacts/6170045735))|
| Changeset  |https://github.com/php/php-src/compare/c45b2bec75..73c4690c0e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39448|0.39607|0.00029|0.07%|0.39489|0.00%|0.39484|0.00%|2.063|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c45b2bec75)|0.38783|0.39081|0.00048|0.12%|0.38836|-1.65%|0.38820|-1.68%|3.039|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/73c4690c0e)|0.38798|0.38943|0.00030|0.08%|0.38841|-1.64%|0.38833|-1.65%|1.857|8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/73c4690c0e)|0.36065|0.36186|0.00030|0.08%|0.36114|-8.55%|0.36113|-8.54%|0.370|8.614|0.000|25.40 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66759|0.67348|0.00098|0.15%|0.66859|0.00%|0.66827|0.00%|2.876|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c45b2bec75)|0.66455|0.66909|0.00098|0.15%|0.66546|-0.47%|0.66520|-0.46%|2.465|7.924|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/73c4690c0e)|0.66460|0.66816|0.00087|0.13%|0.66546|-0.47%|0.66506|-0.48%|1.794|8.366|0.000|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/73c4690c0e)|0.63322|0.65118|0.00284|0.45%|0.63440|-5.11%|0.63375|-5.17%|4.960|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58744|0.59410|0.00134|0.23%|0.58972|0.00%|0.58944|0.00%|0.999|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c45b2bec75)|0.58607|0.58946|0.00069|0.12%|0.58687|-0.48%|0.58670|-0.47%|2.291|8.200|0.000|25.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/73c4690c0e)|0.58615|0.58915|0.00066|0.11%|0.58709|-0.44%|0.58693|-0.43%|1.835|8.138|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/73c4690c0e)|0.51448|0.51869|0.00078|0.15%|0.51576|-12.54%|0.51560|-12.53%|2.359|8.614|0.000|25.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44174|0.44642|0.00078|0.18%|0.44286|0.00%|0.44287|0.00%|1.889|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c45b2bec75)|0.44412|0.44672|0.00057|0.13%|0.44549|0.59%|0.44541|0.57%|-0.036|-8.290|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/73c4690c0e)|0.44316|0.44784|0.00074|0.17%|0.44544|0.58%|0.44552|0.60%|-0.149|-8.193|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/73c4690c0e)|0.14332|0.14444|0.00024|0.17%|0.14384|-67.52%|0.14382|-67.52%|0.024|8.614|0.000|25.28 MB|
