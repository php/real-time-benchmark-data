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
| Time          |2026-10-27 01:09:49 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/40430882451 ([Artifacts](https://github.com/php/php-src/actions/runs/40430882451/artifacts/12703580699))|
| Changeset  |https://github.com/php/php-src/compare/a2bf170ee5..3b8e98882e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39729|0.39950|0.00063|0.16%|0.39807|0.00%|0.39778|0.00%|1.413|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a2bf170ee5)|0.38114|0.38235|0.00029|0.08%|0.38149|-4.16%|0.38141|-4.12%|1.245|8.614|0.000|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b8e98882e)|0.38157|0.38300|0.00037|0.10%|0.38207|-4.02%|0.38197|-3.98%|1.263|8.614|0.000|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b8e98882e)|0.35934|0.36101|0.00027|0.07%|0.35988|-9.59%|0.35987|-9.53%|1.639|8.614|0.000|26.33 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67614|0.68231|0.00109|0.16%|0.67713|0.00%|0.67687|0.00%|2.948|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a2bf170ee5)|0.67711|0.67909|0.00042|0.06%|0.67773|0.09%|0.67765|0.12%|1.871|-5.739|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b8e98882e)|0.68037|0.68237|0.00038|0.06%|0.68089|0.56%|0.68082|0.58%|1.712|-8.276|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b8e98882e)|0.65783|0.65963|0.00040|0.06%|0.65834|-2.77%|0.65824|-2.75%|1.664|8.614|0.000|26.36 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59122|0.59524|0.00101|0.17%|0.59272|0.00%|0.59254|0.00%|0.748|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a2bf170ee5)|0.59583|0.59913|0.00059|0.10%|0.59647|0.63%|0.59633|0.64%|2.652|-8.614|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b8e98882e)|0.59505|0.60326|0.00127|0.21%|0.59602|0.56%|0.59569|0.53%|4.244|-8.586|0.000|26.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b8e98882e)|0.52227|0.53265|0.00145|0.28%|0.52312|-11.74%|0.52284|-11.76%|6.028|8.614|0.000|26.50 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44336|0.44573|0.00055|0.12%|0.44449|0.00%|0.44454|0.00%|-0.091|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a2bf170ee5)|0.45186|0.45447|0.00058|0.13%|0.45338|2.00%|0.45345|2.00%|-0.630|-8.614|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b8e98882e)|0.45254|0.45505|0.00059|0.13%|0.45358|2.05%|0.45347|2.01%|0.471|-8.614|0.000|26.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b8e98882e)|0.14397|0.14644|0.00056|0.39%|0.14456|-67.48%|0.14443|-67.51%|2.032|8.614|0.000|26.50 MB|
