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
| Time          |2026-06-03 01:37:09 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26858416872 ([Artifacts](https://github.com/php/php-src/actions/runs/26858416872/artifacts/7374499635))|
| Changeset  |https://github.com/php/php-src/compare/a22c56c969..b5c17e76a2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39545|0.39756|0.00072|0.18%|0.39607|0.00%|0.39571|0.00%|1.081|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a22c56c969)|0.38635|0.38964|0.00050|0.13%|0.38684|-2.33%|0.38673|-2.27%|3.863|8.614|0.000|25.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/b5c17e76a2)|0.38711|0.38872|0.00039|0.10%|0.38765|-2.13%|0.38756|-2.06%|1.528|8.614|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b5c17e76a2)|0.35812|0.36173|0.00057|0.16%|0.35907|-9.34%|0.35900|-9.28%|2.399|8.614|0.000|25.82 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67412|0.67824|0.00073|0.11%|0.67496|0.00%|0.67477|0.00%|2.249|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a22c56c969)|0.66728|0.66872|0.00036|0.05%|0.66793|-1.04%|0.66786|-1.02%|0.535|8.614|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/b5c17e76a2)|0.66653|0.67477|0.00125|0.19%|0.66739|-1.12%|0.66707|-1.14%|4.899|8.441|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b5c17e76a2)|0.63436|0.65918|0.00349|0.55%|0.63573|-5.81%|0.63505|-5.89%|6.495|8.614|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58929|0.59456|0.00098|0.17%|0.59108|0.00%|0.59089|0.00%|1.342|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a22c56c969)|0.58621|0.59004|0.00080|0.14%|0.58719|-0.66%|0.58700|-0.66%|2.407|8.566|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/b5c17e76a2)|0.58651|0.59053|0.00080|0.14%|0.58731|-0.64%|0.58715|-0.63%|2.343|8.497|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b5c17e76a2)|0.51699|0.52097|0.00082|0.16%|0.51776|-12.40%|0.51753|-12.42%|2.708|8.614|0.000|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44312|0.44574|0.00056|0.13%|0.44430|0.00%|0.44429|0.00%|0.326|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a22c56c969)|0.45034|0.45472|0.00091|0.20%|0.45160|1.64%|0.45150|1.62%|1.287|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/b5c17e76a2)|0.44935|0.45333|0.00073|0.16%|0.45115|1.54%|0.45114|1.54%|0.087|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b5c17e76a2)|0.14550|0.14937|0.00081|0.55%|0.14607|-67.12%|0.14590|-67.16%|3.513|8.614|0.000|26.25 MB|
