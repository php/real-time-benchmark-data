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
| Time          |2026-04-29 01:14:33 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25086014216 ([Artifacts](https://github.com/php/php-src/actions/runs/25086014216/artifacts/6698419667))|
| Changeset  |https://github.com/php/php-src/compare/936f727106..9e529f4eef|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39606|0.39832|0.00070|0.18%|0.39673|0.00%|0.39643|0.00%|1.342|0.000|1.000|26.25 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/936f727106)|0.38807|0.38911|0.00026|0.07%|0.38849|-2.08%|0.38842|-2.02%|0.661|8.614|0.000|25.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/9e529f4eef)|0.45152|0.45405|0.00040|0.09%|0.45191|13.91%|0.45182|13.97%|3.557|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9e529f4eef)|0.41944|0.42230|0.00045|0.11%|0.41998|5.86%|0.41987|5.91%|2.953|-8.614|0.000|25.25 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66828|0.67071|0.00058|0.09%|0.66911|0.00%|0.66894|0.00%|0.794|0.000|1.000|26.72 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/936f727106)|0.66338|0.66778|0.00069|0.10%|0.66403|-0.76%|0.66381|-0.77%|3.583|8.614|0.000|25.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/9e529f4eef)|0.66508|0.67134|0.00095|0.14%|0.66572|-0.51%|0.66555|-0.51%|4.752|8.269|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9e529f4eef)|0.63360|0.63679|0.00057|0.09%|0.63418|-5.22%|0.63397|-5.23%|2.461|8.614|0.000|25.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59315|0.59777|0.00119|0.20%|0.59519|0.00%|0.59518|0.00%|0.246|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/936f727106)|0.59017|0.59148|0.00030|0.05%|0.59074|-0.75%|0.59072|-0.75%|0.392|8.614|0.000|25.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/9e529f4eef)|0.58903|0.59569|0.00099|0.17%|0.58995|-0.88%|0.58975|-0.91%|4.223|8.393|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9e529f4eef)|0.52039|0.52333|0.00051|0.10%|0.52131|-12.41%|0.52120|-12.43%|1.810|8.614|0.000|25.29 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44172|0.44620|0.00070|0.16%|0.44294|0.00%|0.44281|0.00%|2.143|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/936f727106)|0.44521|0.44882|0.00065|0.15%|0.44639|0.78%|0.44637|0.80%|1.045|-8.476|0.000|25.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/9e529f4eef)|0.44549|0.44729|0.00040|0.09%|0.44641|0.78%|0.44637|0.80%|-0.002|-8.524|0.000|25.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9e529f4eef)|0.14310|0.14389|0.00018|0.13%|0.14349|-67.61%|0.14349|-67.60%|-0.142|8.614|0.000|25.29 MB|
