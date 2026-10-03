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
| Binary layout strategy |none|
| Time          |2026-10-03 01:10:15 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/37085023034 ([Artifacts](https://github.com/php/php-src/actions/runs/37085023034/artifacts/11260997124))|
| Changeset  |https://github.com/php/php-src/compare/3254c4e36e..459f8cb22b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39890|0.39978|0.00016|0.04%|0.39924|0.00%|0.39924|0.00%|0.774|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3254c4e36e)|0.37887|0.38012|0.00026|0.07%|0.37924|-5.01%|0.37918|-5.02%|1.489|8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/459f8cb22b)|0.37961|0.38233|0.00041|0.11%|0.38003|-4.81%|0.37994|-4.83%|3.891|8.614|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459f8cb22b)|0.35456|0.35586|0.00027|0.07%|0.35518|-11.04%|0.35520|-11.03%|0.109|8.614|0.000|26.25 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68007|0.68702|0.00112|0.16%|0.68128|0.00%|0.68094|0.00%|2.992|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3254c4e36e)|0.67656|0.67883|0.00049|0.07%|0.67731|-0.58%|0.67719|-0.55%|1.126|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/459f8cb22b)|0.67448|0.68381|0.00141|0.21%|0.67520|-0.89%|0.67481|-0.90%|5.083|8.276|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459f8cb22b)|0.63999|0.65499|0.00299|0.47%|0.64131|-5.87%|0.64050|-5.94%|3.900|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59097|0.59498|0.00077|0.13%|0.59225|0.00%|0.59217|0.00%|1.061|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3254c4e36e)|0.59407|0.60251|0.00126|0.21%|0.59500|0.47%|0.59469|0.43%|4.757|-8.366|0.000|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/459f8cb22b)|0.59447|0.59801|0.00063|0.11%|0.59516|0.49%|0.59502|0.48%|3.405|-8.462|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459f8cb22b)|0.52053|0.52382|0.00057|0.11%|0.52124|-11.99%|0.52111|-12.00%|2.142|8.614|0.000|26.16 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44408|0.44575|0.00042|0.09%|0.44474|0.00%|0.44469|0.00%|0.679|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3254c4e36e)|0.45196|0.45569|0.00081|0.18%|0.45343|1.95%|0.45341|1.96%|0.456|-8.614|0.000|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/459f8cb22b)|0.45107|0.45414|0.00078|0.17%|0.45270|1.79%|0.45268|1.80%|0.087|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459f8cb22b)|0.14342|0.14476|0.00027|0.19%|0.14418|-67.58%|0.14418|-67.58%|-0.029|8.614|0.000|26.16 MB|
