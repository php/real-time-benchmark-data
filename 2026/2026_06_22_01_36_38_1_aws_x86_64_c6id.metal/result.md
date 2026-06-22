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
| Time          |2026-06-22 01:36:38 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27924266829 ([Artifacts](https://github.com/php/php-src/actions/runs/27924266829/artifacts/7781988134))|
| Changeset  |https://github.com/php/php-src/compare/0fff3ccce2..a7a3a5f1d2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39824|0.39944|0.00025|0.06%|0.39862|0.00%|0.39856|0.00%|1.592|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0fff3ccce2)|0.39172|0.39311|0.00030|0.08%|0.39213|-1.63%|0.39205|-1.63%|1.307|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.39268|0.39634|0.00061|0.15%|0.39331|-1.33%|0.39309|-1.37%|2.852|8.614|0.000|25.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.36569|0.36945|0.00076|0.21%|0.36661|-8.03%|0.36644|-8.06%|2.437|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67722|0.68104|0.00080|0.12%|0.67804|0.00%|0.67781|0.00%|1.924|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0fff3ccce2)|0.66944|0.68692|0.00245|0.37%|0.67040|-1.13%|0.66989|-1.17%|6.484|8.269|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.66944|0.67184|0.00048|0.07%|0.67005|-1.18%|0.66988|-1.17%|1.883|8.614|0.000|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.64355|0.64545|0.00040|0.06%|0.64422|-4.99%|0.64422|-4.96%|0.848|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59208|0.59646|0.00102|0.17%|0.59392|0.00%|0.59392|0.00%|0.248|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0fff3ccce2)|0.59052|0.59504|0.00097|0.16%|0.59147|-0.41%|0.59122|-0.45%|2.507|7.690|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.59032|0.59387|0.00076|0.13%|0.59122|-0.45%|0.59106|-0.48%|1.918|8.166|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.52159|0.52643|0.00097|0.19%|0.52239|-12.04%|0.52213|-12.09%|3.178|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44341|0.44755|0.00067|0.15%|0.44445|0.00%|0.44433|0.00%|1.957|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0fff3ccce2)|0.44970|0.45252|0.00053|0.12%|0.45074|1.41%|0.45068|1.43%|0.824|-8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.44943|0.45312|0.00071|0.16%|0.45072|1.41%|0.45074|1.44%|0.920|-8.614|0.000|25.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7a3a5f1d2)|0.14428|0.14543|0.00022|0.15%|0.14473|-67.44%|0.14476|-67.42%|0.401|8.614|0.000|26.24 MB|
