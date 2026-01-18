### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8488C, 48 cores @ 2400 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.158-178.288.amzn2023.x86_64|
| OS            |Amazon Linux 2023.9.20251117|
| GCC           |14.2.1|
| Time          |2026-01-18 00:50:43 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21103471507 ([Artifacts](#ARTIFACT_URL#))|
| Changeset  |https://github.com/php/php-src/compare/084e409694..03ca08948d3c5fc6e99182f81640d2b4c8b46276|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.46134|0.46259|0.00027|0.06%|0.46197|0.00%|0.46198|0.00%|0.018|0.999|27.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/084e409694)|0.45785|0.46109|0.00042|0.09%|0.45871|-0.71%|0.45865|-0.72%|2.166|0.000|27.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/03ca08948d)|0.45784|0.45940|0.00028|0.06%|0.45848|-0.76%|0.45843|-0.77%|0.567|0.000|27.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03ca08948d)|0.43948|0.44283|0.00042|0.10%|0.44009|-4.74%|0.44003|-4.75%|3.258|0.000|27.03 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.76068|0.78085|0.00197|0.26%|0.76935|0.00%|0.76935|0.00%|0.622|0.999|27.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/084e409694)|0.76061|0.78017|0.00331|0.43%|0.76767|-0.22%|0.76912|-0.03%|-0.351|0.001|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/03ca08948d)|0.76451|0.78123|0.00196|0.25%|0.76904|-0.04%|0.76886|-0.06%|4.088|0.000|27.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03ca08948d)|0.73906|0.99384|0.09281|11.23%|0.82644|7.42%|0.79662|3.55%|0.729|0.007|27.05 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.65938|0.68068|0.00287|0.43%|0.66082|0.00%|0.66039|0.00%|6.596|0.999|27.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/084e409694)|0.66277|0.68352|0.00230|0.35%|0.66416|0.51%|0.66368|0.50%|6.595|0.000|27.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/03ca08948d)|0.66219|0.68283|0.00213|0.32%|0.66339|0.39%|0.66308|0.41%|7.889|0.000|27.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03ca08948d)|0.59380|0.59696|0.00063|0.11%|0.59478|-9.99%|0.59463|-9.96%|1.653|0.000|27.05 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % |   Skew  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.42594|0.43265|0.00127|0.30%|0.42839|0.00%|0.42857|0.00%|0.499|0.999|7.94 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/084e409694)|0.44074|0.44826|0.00147|0.33%|0.44416|3.68%|0.44409|3.62%|0.164|0.000|7.95 MB|
|[PHP - master](https://github.com/php/php-src/commit/03ca08948d)|0.44087|0.44841|0.00173|0.39%|0.44426|3.71%|0.44415|3.63%|0.354|0.000|7.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/03ca08948d)|0.13802|0.14393|0.00128|0.91%|0.14086|-67.12%|0.14092|-67.12%|0.022|0.000|7.95 MB|
