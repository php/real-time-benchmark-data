### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.56-125.164.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20261026|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-10-30 00:53:54 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/40982513790 ([Artifacts](https://github.com/php/php-src/actions/runs/40982513790/artifacts/12946747276))|
| Changeset  |https://github.com/php/php-src/compare/17cfa007d5..ff24cc82ea|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39343|0.39540|0.00031|0.08%|0.39374|0.00%|0.39369|0.00%|3.540|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17cfa007d5)|0.37660|0.37998|0.00048|0.13%|0.37703|-4.24%|0.37695|-4.25%|5.078|8.614|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff24cc82ea)|0.37482|0.37728|0.00068|0.18%|0.37559|-4.61%|0.37527|-4.68%|1.253|8.614|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff24cc82ea)|0.35054|0.35159|0.00024|0.07%|0.35105|-10.84%|0.35108|-10.82%|0.259|8.614|0.000|26.37 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67109|0.67500|0.00077|0.12%|0.67177|0.00%|0.67152|0.00%|2.425|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17cfa007d5)|0.68067|0.69007|0.00132|0.19%|0.68173|1.48%|0.68146|1.48%|5.488|-8.614|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff24cc82ea)|0.67596|0.67834|0.00039|0.06%|0.67664|0.72%|0.67660|0.76%|1.805|-8.614|0.000|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff24cc82ea)|0.64945|0.65591|0.00090|0.14%|0.65022|-3.21%|0.65008|-3.19%|5.447|8.614|0.000|26.34 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58709|0.59088|0.00085|0.14%|0.58858|0.00%|0.58855|0.00%|0.665|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17cfa007d5)|0.59080|0.59300|0.00046|0.08%|0.59152|0.50%|0.59143|0.49%|1.317|-8.600|0.000|26.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff24cc82ea)|0.59226|0.59613|0.00078|0.13%|0.59313|0.77%|0.59287|0.73%|2.148|-8.614|0.000|26.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff24cc82ea)|0.51815|0.52129|0.00059|0.11%|0.51887|-11.84%|0.51874|-11.86%|2.202|8.614|0.000|26.47 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44347|0.44647|0.00065|0.15%|0.44464|0.00%|0.44459|0.00%|0.428|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17cfa007d5)|0.45268|0.45570|0.00061|0.13%|0.45404|2.11%|0.45395|2.11%|0.310|-8.614|0.000|26.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/ff24cc82ea)|0.45342|0.45611|0.00061|0.14%|0.45471|2.26%|0.45472|2.28%|0.221|-8.614|0.000|26.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ff24cc82ea)|0.14368|0.14668|0.00051|0.35%|0.14443|-67.52%|0.14438|-67.53%|3.432|8.614|0.000|26.47 MB|
