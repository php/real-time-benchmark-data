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
| Time          |2026-10-29 00:52:59 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/40796881787 ([Artifacts](https://github.com/php/php-src/actions/runs/40796881787/artifacts/12866370249))|
| Changeset  |https://github.com/php/php-src/compare/780f4e8217..17cfa007d5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39459|0.39642|0.00033|0.08%|0.39495|0.00%|0.39490|0.00%|2.848|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/780f4e8217)|0.37763|0.37892|0.00031|0.08%|0.37808|-4.27%|0.37796|-4.29%|1.171|8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/17cfa007d5)|0.37786|0.38018|0.00043|0.11%|0.37832|-4.21%|0.37821|-4.23%|2.406|8.614|0.000|25.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17cfa007d5)|0.35328|0.35521|0.00037|0.11%|0.35387|-10.40%|0.35381|-10.40%|1.212|8.614|0.000|26.35 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67380|0.67949|0.00093|0.14%|0.67455|0.00%|0.67428|0.00%|3.526|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/780f4e8217)|0.68171|0.68394|0.00040|0.06%|0.68253|1.18%|0.68251|1.22%|0.797|-8.614|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/17cfa007d5)|0.68349|0.68783|0.00084|0.12%|0.68421|1.43%|0.68395|1.43%|2.591|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17cfa007d5)|0.65965|0.66272|0.00054|0.08%|0.66048|-2.09%|0.66034|-2.07%|1.784|8.614|0.000|26.37 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58815|0.59139|0.00075|0.13%|0.58983|0.00%|0.58990|0.00%|0.014|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/780f4e8217)|0.59217|0.59510|0.00062|0.11%|0.59300|0.54%|0.59283|0.50%|1.932|-8.614|0.000|26.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/17cfa007d5)|0.59194|0.59464|0.00053|0.09%|0.59304|0.54%|0.59293|0.51%|0.666|-8.614|0.000|26.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17cfa007d5)|0.51838|0.52147|0.00064|0.12%|0.51929|-11.96%|0.51917|-11.99%|1.854|8.614|0.000|26.44 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44366|0.44910|0.00083|0.19%|0.44463|0.00%|0.44448|0.00%|3.337|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/780f4e8217)|0.45151|0.45435|0.00061|0.14%|0.45292|1.86%|0.45286|1.89%|-0.039|-8.614|0.000|26.43 MB|
|[PHP - master](https://github.com/php/php-src/commit/17cfa007d5)|0.45247|0.45553|0.00074|0.16%|0.45393|2.09%|0.45391|2.12%|0.126|-8.614|0.000|26.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/17cfa007d5)|0.14395|0.14632|0.00054|0.37%|0.14457|-67.49%|0.14447|-67.50%|2.222|8.614|0.000|26.44 MB|
