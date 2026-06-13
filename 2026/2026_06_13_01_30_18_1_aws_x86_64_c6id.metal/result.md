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
| Time          |2026-06-13 01:30:18 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27452507898 ([Artifacts](https://github.com/php/php-src/actions/runs/27452507898/artifacts/7606425913))|
| Changeset  |https://github.com/php/php-src/compare/8bbe4b4119..8c63ec400c|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39663|0.39890|0.00071|0.18%|0.39725|0.00%|0.39694|0.00%|1.400|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8bbe4b4119)|0.38530|0.38659|0.00028|0.07%|0.38571|-2.91%|0.38564|-2.85%|1.365|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/8c63ec400c)|0.38733|0.38911|0.00030|0.08%|0.38779|-2.38%|0.38773|-2.32%|2.295|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8c63ec400c)|0.36064|0.36415|0.00049|0.14%|0.36122|-9.07%|0.36118|-9.01%|4.414|8.614|0.000|25.80 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67507|0.67942|0.00075|0.11%|0.67575|0.00%|0.67563|0.00%|2.991|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8bbe4b4119)|0.66890|0.67085|0.00048|0.07%|0.66957|-0.91%|0.66943|-0.92%|1.093|8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/8c63ec400c)|0.67784|0.68298|0.00097|0.14%|0.67866|0.43%|0.67830|0.40%|2.677|-8.324|0.000|25.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8c63ec400c)|0.63667|0.63836|0.00039|0.06%|0.63739|-5.68%|0.63727|-5.68%|0.789|8.614|0.000|26.22 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59035|0.59571|0.00127|0.21%|0.59252|0.00%|0.59235|0.00%|0.473|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8bbe4b4119)|0.58759|0.59105|0.00059|0.10%|0.58826|-0.72%|0.58809|-0.72%|2.693|8.579|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/8c63ec400c)|0.58856|0.59258|0.00099|0.17%|0.58958|-0.50%|0.58921|-0.53%|1.896|7.869|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8c63ec400c)|0.51795|0.52218|0.00099|0.19%|0.51897|-12.41%|0.51873|-12.43%|2.414|8.614|0.000|26.17 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44333|0.44646|0.00053|0.12%|0.44461|0.00%|0.44454|0.00%|0.700|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8bbe4b4119)|0.45039|0.45412|0.00073|0.16%|0.45152|1.55%|0.45151|1.57%|1.103|-8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/8c63ec400c)|0.45034|0.45347|0.00071|0.16%|0.45160|1.57%|0.45151|1.57%|0.523|-8.614|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8c63ec400c)|0.14561|0.14944|0.00103|0.70%|0.14629|-67.10%|0.14598|-67.16%|2.622|8.614|0.000|26.17 MB|
