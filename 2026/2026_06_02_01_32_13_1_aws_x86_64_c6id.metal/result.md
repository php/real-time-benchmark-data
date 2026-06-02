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
| Time          |2026-06-02 01:32:13 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26792777726 ([Artifacts](https://github.com/php/php-src/actions/runs/26792777726/artifacts/7347606988))|
| Changeset  |https://github.com/php/php-src/compare/61e679dd89..a22c56c969|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39656|0.39881|0.00075|0.19%|0.39732|0.00%|0.39694|0.00%|0.983|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61e679dd89)|0.38843|0.38975|0.00030|0.08%|0.38892|-2.11%|0.38884|-2.04%|0.779|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/a22c56c969)|0.38761|0.39091|0.00050|0.13%|0.38823|-2.29%|0.38814|-2.22%|3.650|8.614|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a22c56c969)|0.35946|0.36148|0.00042|0.12%|0.36024|-9.33%|0.36014|-9.27%|1.102|8.614|0.000|25.82 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67496|0.67681|0.00040|0.06%|0.67558|0.00%|0.67552|0.00%|0.841|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61e679dd89)|0.67490|0.67815|0.00062|0.09%|0.67580|0.03%|0.67564|0.02%|1.445|-1.885|0.059|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/a22c56c969)|0.66840|0.67024|0.00046|0.07%|0.66900|-0.97%|0.66885|-0.99%|0.996|8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a22c56c969)|0.64308|0.64777|0.00067|0.10%|0.64382|-4.70%|0.64374|-4.70%|4.283|8.614|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59037|0.59676|0.00113|0.19%|0.59253|0.00%|0.59252|0.00%|1.054|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61e679dd89)|0.58873|0.59737|0.00119|0.20%|0.58962|-0.49%|0.58937|-0.53%|5.783|8.262|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/a22c56c969)|0.58775|0.59163|0.00087|0.15%|0.58873|-0.64%|0.58850|-0.68%|2.038|8.421|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a22c56c969)|0.51824|0.52246|0.00086|0.17%|0.51921|-12.37%|0.51903|-12.40%|2.420|8.614|0.000|26.25 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44339|0.44808|0.00081|0.18%|0.44453|0.00%|0.44436|0.00%|1.788|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/61e679dd89)|0.45006|0.45247|0.00063|0.14%|0.45134|1.53%|0.45151|1.61%|-0.496|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/a22c56c969)|0.44971|0.45451|0.00077|0.17%|0.45131|1.53%|0.45134|1.57%|1.284|-8.614|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a22c56c969)|0.14549|0.14938|0.00090|0.62%|0.14610|-67.13%|0.14586|-67.17%|3.032|8.614|0.000|26.26 MB|
