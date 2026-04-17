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
| Time          |2026-04-17 01:07:02 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24542352295 ([Artifacts](https://github.com/php/php-src/actions/runs/24542352295/artifacts/6487328679))|
| Changeset  |https://github.com/php/php-src/compare/f437b8b0e9..60314974f9|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39809|0.40055|0.00073|0.18%|0.39885|0.00%|0.39856|0.00%|1.171|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f437b8b0e9)|0.38952|0.39191|0.00042|0.11%|0.38983|-2.26%|0.38970|-2.22%|3.143|8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/60314974f9)|0.39040|0.39311|0.00056|0.14%|0.39098|-1.97%|0.39078|-1.95%|2.375|8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60314974f9)|0.36327|0.36564|0.00050|0.14%|0.36387|-8.77%|0.36379|-8.73%|1.937|8.614|0.000|25.33 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67140|0.67370|0.00051|0.08%|0.67210|0.00%|0.67198|0.00%|1.209|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f437b8b0e9)|0.67277|0.67944|0.00125|0.19%|0.67445|0.35%|0.67430|0.35%|2.130|-8.428|0.000|25.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/60314974f9)|0.67169|0.67760|0.00086|0.13%|0.67235|0.04%|0.67219|0.03%|4.929|-2.554|0.011|25.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60314974f9)|0.63341|0.65650|0.00321|0.51%|0.63446|-5.60%|0.63392|-5.66%|6.897|8.614|0.000|25.25 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59121|0.59554|0.00109|0.18%|0.59330|0.00%|0.59313|0.00%|0.234|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f437b8b0e9)|0.58950|0.59270|0.00055|0.09%|0.59103|-0.38%|0.59098|-0.36%|0.320|8.248|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/60314974f9)|0.58945|0.59246|0.00063|0.11%|0.59048|-0.48%|0.59032|-0.47%|1.697|8.366|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60314974f9)|0.52016|0.52419|0.00075|0.14%|0.52110|-12.17%|0.52092|-12.17%|2.639|8.614|0.000|25.32 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44203|0.44418|0.00053|0.12%|0.44300|0.00%|0.44300|0.00%|0.159|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f437b8b0e9)|0.44523|0.44719|0.00042|0.09%|0.44627|0.74%|0.44623|0.73%|-0.174|-8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/60314974f9)|0.44534|0.44740|0.00051|0.12%|0.44643|0.78%|0.44646|0.78%|-0.164|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60314974f9)|0.14336|0.14415|0.00019|0.13%|0.14369|-67.56%|0.14367|-67.57%|0.429|8.614|0.000|25.32 MB|
