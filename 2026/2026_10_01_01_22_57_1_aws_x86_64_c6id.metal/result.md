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
| Time          |2026-10-01 01:22:57 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/36800799807 ([Artifacts](https://github.com/php/php-src/actions/runs/36800799807/artifacts/11135699447))|
| Changeset  |https://github.com/php/php-src/compare/c04004b18f..940ff2098e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39916|0.40084|0.00028|0.07%|0.39954|0.00%|0.39949|0.00%|2.236|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c04004b18f)|0.37945|0.38227|0.00059|0.15%|0.38015|-4.85%|0.37991|-4.90%|1.590|8.614|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ff2098e)|0.37950|0.38256|0.00064|0.17%|0.37997|-4.90%|0.37977|-4.94%|2.987|8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ff2098e)|0.35575|0.35819|0.00040|0.11%|0.35637|-10.80%|0.35630|-10.81%|2.508|8.614|0.000|26.15 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68138|0.68426|0.00079|0.12%|0.68272|0.00%|0.68261|0.00%|0.235|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c04004b18f)|0.67139|0.67482|0.00059|0.09%|0.67215|-1.55%|0.67197|-1.56%|2.537|8.614|0.000|26.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ff2098e)|0.67762|0.67947|0.00042|0.06%|0.67833|-0.64%|0.67830|-0.63%|0.761|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ff2098e)|0.64608|0.65326|0.00122|0.19%|0.64706|-5.22%|0.64673|-5.26%|3.575|8.614|0.000|26.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59118|0.59469|0.00082|0.14%|0.59243|0.00%|0.59231|0.00%|0.952|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c04004b18f)|0.59314|0.59640|0.00086|0.14%|0.59400|0.26%|0.59369|0.23%|1.825|-7.214|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ff2098e)|0.59419|0.59781|0.00096|0.16%|0.59517|0.46%|0.59488|0.43%|1.841|-8.455|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ff2098e)|0.52038|0.52382|0.00053|0.10%|0.52134|-12.00%|0.52127|-11.99%|2.183|8.614|0.000|26.17 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44317|0.44601|0.00064|0.14%|0.44487|0.00%|0.44498|0.00%|-0.495|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c04004b18f)|0.45117|0.45535|0.00089|0.20%|0.45267|1.75%|0.45241|1.67%|1.185|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/940ff2098e)|0.45155|0.45601|0.00075|0.17%|0.45312|1.85%|0.45300|1.80%|1.194|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/940ff2098e)|0.14377|0.14484|0.00023|0.16%|0.14431|-67.56%|0.14434|-67.56%|-0.266|8.614|0.000|26.18 MB|
