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
| Time          |2026-09-30 01:16:10 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/36654270290 ([Artifacts](https://github.com/php/php-src/actions/runs/36654270290/artifacts/11072152908))|
| Changeset  |https://github.com/php/php-src/compare/810ac6dc4d..c04004b18f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39518|0.39634|0.00022|0.06%|0.39560|0.00%|0.39556|0.00%|1.085|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/810ac6dc4d)|0.37332|0.37457|0.00026|0.07%|0.37368|-5.54%|0.37362|-5.55%|1.532|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/c04004b18f)|0.37533|0.37729|0.00052|0.14%|0.37589|-4.98%|0.37570|-5.02%|1.502|8.614|0.000|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c04004b18f)|0.35119|0.35291|0.00032|0.09%|0.35162|-11.12%|0.35155|-11.13%|1.920|8.614|0.000|26.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67498|0.68441|0.00143|0.21%|0.67645|0.00%|0.67607|0.00%|3.766|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/810ac6dc4d)|0.66562|0.67021|0.00076|0.11%|0.66628|-1.50%|0.66611|-1.47%|3.462|8.614|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/c04004b18f)|0.66575|0.66871|0.00045|0.07%|0.66621|-1.51%|0.66610|-1.48%|3.766|8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c04004b18f)|0.63390|0.64955|0.00218|0.34%|0.63509|-6.11%|0.63466|-6.13%|6.238|8.614|0.000|26.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58689|0.59026|0.00075|0.13%|0.58844|0.00%|0.58838|0.00%|0.201|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/810ac6dc4d)|0.58891|0.59266|0.00071|0.12%|0.58985|0.24%|0.58968|0.22%|2.072|-7.531|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/c04004b18f)|0.58894|0.59175|0.00058|0.10%|0.58964|0.21%|0.58952|0.19%|2.010|-7.021|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c04004b18f)|0.51595|0.51956|0.00066|0.13%|0.51673|-12.19%|0.51657|-12.20%|2.776|8.614|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44353|0.44570|0.00054|0.12%|0.44461|0.00%|0.44461|0.00%|-0.263|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/810ac6dc4d)|0.45132|0.45526|0.00082|0.18%|0.45308|1.91%|0.45298|1.88%|0.509|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/c04004b18f)|0.45096|0.45380|0.00066|0.15%|0.45250|1.77%|0.45244|1.76%|-0.003|-8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c04004b18f)|0.14340|0.14802|0.00061|0.42%|0.14415|-67.58%|0.14407|-67.60%|5.382|8.614|0.000|26.19 MB|
