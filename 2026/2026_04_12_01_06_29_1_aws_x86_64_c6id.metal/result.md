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
| Time          |2026-04-12 01:06:29 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24295535114 ([Artifacts](https://github.com/php/php-src/actions/runs/24295535114/artifacts/6389504311))|
| Changeset  |https://github.com/php/php-src/compare/555e65242f..3afd2cbbb8|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39444|0.39752|0.00068|0.17%|0.39508|0.00%|0.39487|0.00%|1.938|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/555e65242f)|0.38786|0.38928|0.00029|0.07%|0.38831|-1.71%|0.38826|-1.67%|1.189|8.614|0.000|24.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/3afd2cbbb8)|0.38857|0.39185|0.00079|0.20%|0.38918|-1.49%|0.38890|-1.51%|2.490|8.614|0.000|24.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3afd2cbbb8)|0.36080|0.36288|0.00042|0.12%|0.36157|-8.48%|0.36148|-8.46%|0.852|8.614|0.000|25.41 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66679|0.66943|0.00058|0.09%|0.66760|0.00%|0.66741|0.00%|1.150|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/555e65242f)|0.66253|0.66593|0.00054|0.08%|0.66319|-0.66%|0.66305|-0.65%|2.866|8.614|0.000|25.20 MB|
|[PHP - master](https://github.com/php/php-src/commit/3afd2cbbb8)|0.66265|0.66469|0.00039|0.06%|0.66315|-0.67%|0.66301|-0.66%|1.765|8.614|0.000|25.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3afd2cbbb8)|0.63323|0.63459|0.00031|0.05%|0.63371|-5.08%|0.63365|-5.06%|1.100|8.614|0.000|25.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58738|0.59127|0.00083|0.14%|0.58930|0.00%|0.58951|0.00%|-0.039|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/555e65242f)|0.58455|0.59221|0.00109|0.19%|0.58524|-0.69%|0.58496|-0.77%|5.617|8.269|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/3afd2cbbb8)|0.58411|0.58749|0.00082|0.14%|0.58494|-0.74%|0.58467|-0.82%|2.265|8.593|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3afd2cbbb8)|0.51455|0.51828|0.00086|0.17%|0.51562|-12.50%|0.51534|-12.58%|2.144|8.614|0.000|25.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44175|0.44417|0.00060|0.14%|0.44285|0.00%|0.44274|0.00%|0.383|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/555e65242f)|0.44474|0.44681|0.00054|0.12%|0.44574|0.65%|0.44575|0.68%|0.106|-8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/3afd2cbbb8)|0.44482|0.44723|0.00050|0.11%|0.44579|0.66%|0.44575|0.68%|0.485|-8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3afd2cbbb8)|0.14337|0.14451|0.00024|0.17%|0.14377|-67.53%|0.14373|-67.54%|1.036|8.614|0.000|25.26 MB|
