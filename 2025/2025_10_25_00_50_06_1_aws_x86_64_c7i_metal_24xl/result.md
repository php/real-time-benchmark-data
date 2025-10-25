### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250818|
| GCC           |14.2.1|
| Time          |2025-10-25 00:50:06 UTC|

### Laravel 12.2.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47300|0.47955|0.00083|0.18%|0.47649|0.00%|0.47642|0.00%|0.342|0.999|180946315|43.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27948dcee7)|0.46720|0.47298|0.00094|0.20%|0.46855|-1.67%|0.46833|-1.70%|1.970|0.000|176310472|44.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/7455f6a5b0)|0.46716|0.47127|0.00069|0.15%|0.46845|-1.69%|0.46836|-1.69%|1.276|0.000|176383432|44.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7455f6a5b0)|0.44404|0.45113|0.00074|0.17%|0.44996|-5.57%|0.44998|-5.55%|-5.011|0.000|147852086|53.39 MB|

### Symfony 2.7.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74024|0.74550|0.00114|0.15%|0.74227|0.00%|0.74223|0.00%|0.475|0.999|291621398|40.27 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27948dcee7)|0.73543|0.75034|0.00226|0.31%|0.73849|-0.51%|0.73778|-0.60%|2.184|0.000|287324422|40.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/7455f6a5b0)|0.73587|0.75020|0.00215|0.29%|0.73853|-0.50%|0.73798|-0.57%|2.418|0.000|287324424|40.67 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7455f6a5b0)|0.70631|0.71209|0.00116|0.16%|0.70850|-4.55%|0.70835|-4.56%|0.394|0.000|267687716|47.78 MB|

### Wordpress 6.2 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58144|0.58635|0.00096|0.16%|0.58268|0.00%|0.58249|0.00%|1.522|0.999|1123344623|43.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27948dcee7)|0.58384|0.58777|0.00073|0.13%|0.58529|0.45%|0.58524|0.47%|0.699|0.000|1120073893|44.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/7455f6a5b0)|0.58405|0.58750|0.00078|0.13%|0.58558|0.50%|0.58552|0.52%|0.544|0.000|1120082964|44.07 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7455f6a5b0)|0.51652|0.51993|0.00054|0.10%|0.51819|-11.07%|0.51820|-11.04%|0.043|0.000|866131002|61.50 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |  Instr count  |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42934|0.44204|0.00209|0.48%|0.43374|0.00%|0.43362|0.00%|0.640|0.999|2020638207|26.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/27948dcee7)|0.42382|0.43725|0.00246|0.58%|0.42695|-1.57%|0.42622|-1.71%|2.091|0.000|2020586598|26.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/7455f6a5b0)|0.42367|0.43841|0.00268|0.63%|0.42699|-1.56%|0.42631|-1.68%|2.238|0.000|2020586635|26.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7455f6a5b0)|0.14441|0.15131|0.00134|0.92%|0.14680|-66.16%|0.14687|-66.13%|0.534|0.000|536605656|27.67 MB|
