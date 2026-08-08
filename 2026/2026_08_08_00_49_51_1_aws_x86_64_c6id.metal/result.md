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
| Time          |2026-08-08 00:49:51 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/31231110659 ([Artifacts](https://github.com/php/php-src/actions/runs/31231110659/artifacts/9014533571))|
| Changeset  |https://github.com/php/php-src/compare/bf2ba7a800..bf5141c5e6|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39829|0.40302|0.00060|0.15%|0.40232|0.00%|0.40235|0.00%|-6.258|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf2ba7a800)|0.39135|0.39252|0.00025|0.06%|0.39190|-2.59%|0.39188|-2.60%|0.475|8.614|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5141c5e6)|0.39164|0.39316|0.00033|0.08%|0.39201|-2.56%|0.39197|-2.58%|1.907|8.614|0.000|25.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5141c5e6)|0.37066|0.37353|0.00044|0.12%|0.37107|-7.77%|0.37099|-7.79%|3.828|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68152|0.68504|0.00077|0.11%|0.68340|0.00%|0.68340|0.00%|0.027|0.000|1.000|26.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf2ba7a800)|0.67893|0.68086|0.00044|0.06%|0.67969|-0.54%|0.67954|-0.56%|0.815|8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5141c5e6)|0.67528|0.67883|0.00079|0.12%|0.67600|-1.08%|0.67573|-1.12%|1.958|8.614|0.000|25.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5141c5e6)|0.64811|0.64976|0.00035|0.05%|0.64866|-5.08%|0.64860|-5.09%|1.401|8.614|0.000|25.92 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59389|0.59915|0.00093|0.16%|0.59623|0.00%|0.59623|0.00%|0.250|0.000|1.000|26.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf2ba7a800)|0.59206|0.59526|0.00078|0.13%|0.59303|-0.54%|0.59281|-0.57%|1.445|8.476|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5141c5e6)|0.59227|0.59648|0.00099|0.17%|0.59300|-0.54%|0.59265|-0.60%|2.519|8.035|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5141c5e6)|0.52341|0.52758|0.00075|0.14%|0.52444|-12.04%|0.52431|-12.06%|2.631|8.614|0.000|26.34 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44361|0.45221|0.00116|0.26%|0.44504|0.00%|0.44489|0.00%|4.903|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/bf2ba7a800)|0.44930|0.45131|0.00042|0.09%|0.45044|1.21%|0.45050|1.26%|-0.451|-8.269|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/bf5141c5e6)|0.44971|0.45504|0.00083|0.18%|0.45091|1.32%|0.45085|1.34%|2.635|-8.283|0.000|26.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bf5141c5e6)|0.14435|0.14602|0.00027|0.18%|0.14476|-67.47%|0.14474|-67.47%|2.051|8.614|0.000|26.36 MB|
