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
| Time          |2026-09-06 01:11:58 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34003244755 ([Artifacts](https://github.com/php/php-src/actions/runs/34003244755/artifacts/9980518240))|
| Changeset  |https://github.com/php/php-src/compare/1053403d9a..5be4de10e7|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39604|0.39818|0.00034|0.09%|0.39638|0.00%|0.39630|0.00%|3.352|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1053403d9a)|0.37050|0.37229|0.00035|0.09%|0.37093|-6.42%|0.37084|-6.43%|2.178|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/5be4de10e7)|0.37026|0.37165|0.00034|0.09%|0.37075|-6.47%|0.37067|-6.47%|1.304|8.614|0.000|25.86 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67664|0.68467|0.00112|0.17%|0.67865|0.00%|0.67849|0.00%|3.041|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1053403d9a)|0.66614|0.66839|0.00050|0.08%|0.66683|-1.74%|0.66671|-1.74%|1.342|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/5be4de10e7)|0.66822|0.67674|0.00163|0.24%|0.66979|-1.31%|0.66944|-1.33%|3.162|8.607|0.000|26.19 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58727|0.59169|0.00096|0.16%|0.58904|0.00%|0.58883|0.00%|0.603|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1053403d9a)|0.58742|0.59068|0.00074|0.13%|0.58851|-0.09%|0.58843|-0.07%|0.909|2.926|0.003|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/5be4de10e7)|0.58742|0.59136|0.00102|0.17%|0.58836|-0.12%|0.58801|-0.14%|1.733|4.285|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44326|0.44561|0.00051|0.12%|0.44461|0.00%|0.44468|0.00%|-0.432|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1053403d9a)|0.45020|0.45390|0.00065|0.14%|0.45146|1.54%|0.45137|1.51%|1.079|-8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/5be4de10e7)|0.45030|0.45380|0.00057|0.13%|0.45140|1.53%|0.45130|1.49%|1.563|-8.614|0.000|26.23 MB|
