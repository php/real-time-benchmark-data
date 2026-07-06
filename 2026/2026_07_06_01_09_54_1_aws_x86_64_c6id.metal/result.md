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
| Time          |2026-07-06 01:09:54 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28761492020 ([Artifacts](https://github.com/php/php-src/actions/runs/28761492020/artifacts/8098241475))|
| Changeset  |https://github.com/php/php-src/compare/dcfa40cccf..8613e0ebdb|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39462|0.39803|0.00087|0.22%|0.39569|0.00%|0.39524|0.00%|0.726|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dcfa40cccf)|0.38594|0.38734|0.00032|0.08%|0.38649|-2.32%|0.38648|-2.22%|0.673|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/8613e0ebdb)|0.38684|0.38889|0.00041|0.11%|0.38745|-2.08%|0.38734|-2.00%|1.295|8.614|0.000|25.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8613e0ebdb)|0.36187|0.36449|0.00047|0.13%|0.36250|-8.39%|0.36240|-8.31%|2.357|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67235|0.67513|0.00061|0.09%|0.67317|0.00%|0.67300|0.00%|1.163|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dcfa40cccf)|0.66988|0.67566|0.00092|0.14%|0.67082|-0.35%|0.67061|-0.35%|3.488|8.055|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/8613e0ebdb)|0.66521|0.66720|0.00052|0.08%|0.66582|-1.09%|0.66565|-1.09%|1.337|8.614|0.000|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8613e0ebdb)|0.63317|0.63527|0.00047|0.07%|0.63385|-5.84%|0.63373|-5.84%|1.646|8.614|0.000|26.18 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58860|0.59314|0.00094|0.16%|0.59051|0.00%|0.59058|0.00%|0.309|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dcfa40cccf)|0.58603|0.58950|0.00063|0.11%|0.58671|-0.64%|0.58660|-0.68%|3.327|8.545|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/8613e0ebdb)|0.58559|0.58890|0.00067|0.11%|0.58639|-0.70%|0.58625|-0.73%|2.521|8.590|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8613e0ebdb)|0.51648|0.52007|0.00078|0.15%|0.51731|-12.40%|0.51713|-12.44%|2.235|8.614|0.000|26.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44328|0.44612|0.00068|0.15%|0.44463|0.00%|0.44463|0.00%|0.195|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dcfa40cccf)|0.44933|0.45324|0.00067|0.15%|0.45075|1.38%|0.45081|1.39%|0.625|-8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/8613e0ebdb)|0.44961|0.45258|0.00064|0.14%|0.45070|1.36%|0.45075|1.38%|0.316|-8.614|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8613e0ebdb)|0.14389|0.14506|0.00020|0.14%|0.14438|-67.53%|0.14438|-67.53%|0.469|8.614|0.000|26.26 MB|
