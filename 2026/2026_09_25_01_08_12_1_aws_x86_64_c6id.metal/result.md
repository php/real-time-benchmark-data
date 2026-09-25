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
| Time          |2026-09-25 01:08:12 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/36080646576 ([Artifacts](https://github.com/php/php-src/actions/runs/36080646576/artifacts/10843171907))|
| Changeset  |https://github.com/php/php-src/compare/42c147ab67..c45a9f95f5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39608|0.39753|0.00027|0.07%|0.39644|0.00%|0.39642|0.00%|1.645|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42c147ab67)|0.37326|0.37634|0.00054|0.14%|0.37386|-5.69%|0.37372|-5.72%|2.716|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/c45a9f95f5)|0.37413|0.37580|0.00042|0.11%|0.37475|-5.47%|0.37461|-5.50%|1.102|8.614|0.000|25.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c45a9f95f5)|0.35245|0.35353|0.00020|0.06%|0.35275|-11.02%|0.35274|-11.02%|1.370|8.614|0.000|26.28 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67618|0.67973|0.00080|0.12%|0.67768|0.00%|0.67755|0.00%|0.497|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42c147ab67)|0.66832|0.66982|0.00036|0.05%|0.66875|-1.32%|0.66864|-1.31%|1.329|8.614|0.000|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/c45a9f95f5)|0.67201|0.67497|0.00051|0.08%|0.67251|-0.76%|0.67240|-0.76%|2.638|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c45a9f95f5)|0.63719|0.63863|0.00033|0.05%|0.63767|-5.90%|0.63758|-5.90%|1.006|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58742|0.59310|0.00103|0.18%|0.58935|0.00%|0.58942|0.00%|0.808|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42c147ab67)|0.58965|0.59272|0.00074|0.12%|0.59061|0.21%|0.59038|0.16%|1.259|-6.301|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/c45a9f95f5)|0.59074|0.59464|0.00080|0.14%|0.59183|0.42%|0.59167|0.38%|2.066|-8.248|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c45a9f95f5)|0.51955|0.52374|0.00089|0.17%|0.52045|-11.69%|0.52030|-11.73%|2.519|8.614|0.000|26.27 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44351|0.44534|0.00046|0.10%|0.44463|0.00%|0.44465|0.00%|-0.330|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/42c147ab67)|0.45178|0.45566|0.00076|0.17%|0.45307|1.90%|0.45297|1.87%|0.954|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/c45a9f95f5)|0.45175|0.45505|0.00070|0.16%|0.45325|1.94%|0.45310|1.90%|0.284|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c45a9f95f5)|0.14435|0.14517|0.00020|0.13%|0.14486|-67.42%|0.14489|-67.41%|-0.683|8.614|0.000|26.27 MB|
