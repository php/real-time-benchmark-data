### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-03 01:54:44 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25266478109 ([Artifacts](https://github.com/php/php-src/actions/runs/25266478109/artifacts/6767496974))|
| Changeset  |https://github.com/php/php-src/compare/1d3a9bc3c4..794a35c705|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39273|0.39505|0.00074|0.19%|0.39353|0.00%|0.39316|0.00%|1.005|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d3a9bc3c4)|0.38408|0.38752|0.00060|0.16%|0.38481|-2.22%|0.38455|-2.19%|2.223|8.614|0.000|25.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/794a35c705)|0.38343|0.38598|0.00052|0.13%|0.38398|-2.43%|0.38383|-2.37%|2.305|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/794a35c705)|0.35718|0.35999|0.00053|0.15%|0.35771|-9.10%|0.35759|-9.05%|2.805|8.614|0.000|25.51 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67090|0.67295|0.00051|0.08%|0.67170|0.00%|0.67157|0.00%|0.825|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d3a9bc3c4)|0.66481|0.66636|0.00039|0.06%|0.66545|-0.93%|0.66537|-0.92%|0.795|8.614|0.000|25.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/794a35c705)|0.66107|0.66306|0.00043|0.06%|0.66160|-1.50%|0.66150|-1.50%|1.420|8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/794a35c705)|0.63167|0.63348|0.00036|0.06%|0.63224|-5.88%|0.63218|-5.87%|1.089|8.614|0.000|25.33 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58577|0.59027|0.00102|0.17%|0.58825|0.00%|0.58819|0.00%|-0.257|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d3a9bc3c4)|0.58380|0.59163|0.00119|0.20%|0.58476|-0.59%|0.58448|-0.63%|4.303|8.207|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/794a35c705)|0.58196|0.58430|0.00050|0.09%|0.58276|-0.93%|0.58265|-0.94%|1.353|8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/794a35c705)|0.51245|0.51539|0.00062|0.12%|0.51332|-12.74%|0.51318|-12.75%|2.042|8.614|0.000|25.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44187|0.44661|0.00089|0.20%|0.44283|0.00%|0.44269|0.00%|3.072|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1d3a9bc3c4)|0.44566|0.44756|0.00054|0.12%|0.44665|0.86%|0.44659|0.88%|0.091|-8.283|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/794a35c705)|0.44551|0.44948|0.00064|0.14%|0.44666|0.87%|0.44661|0.88%|1.624|-8.290|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/794a35c705)|0.14354|0.14644|0.00066|0.46%|0.14407|-67.46%|0.14391|-67.49%|2.785|8.614|0.000|25.35 MB|
