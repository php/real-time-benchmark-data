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
| Time          |2026-06-14 01:34:31 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27484831256 ([Artifacts](https://github.com/php/php-src/actions/runs/27484831256/artifacts/7616636716))|
| Changeset  |https://github.com/php/php-src/compare/8c63ec400c..a15155100d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39693|0.39830|0.00023|0.06%|0.39728|0.00%|0.39723|0.00%|1.965|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8c63ec400c)|0.38794|0.38898|0.00021|0.05%|0.38824|-2.28%|0.38822|-2.27%|1.227|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/a15155100d)|0.38694|0.38997|0.00070|0.18%|0.38889|-2.11%|0.38899|-2.07%|-1.541|8.614|0.000|25.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a15155100d)|0.36416|0.36736|0.00063|0.17%|0.36496|-8.14%|0.36488|-8.14%|2.562|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67633|0.67871|0.00053|0.08%|0.67701|0.00%|0.67681|0.00%|1.080|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8c63ec400c)|0.67886|0.68198|0.00063|0.09%|0.67955|0.38%|0.67932|0.37%|1.843|-8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/a15155100d)|0.66847|0.67661|0.00148|0.22%|0.66984|-1.06%|0.66928|-1.11%|2.632|8.538|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a15155100d)|0.63617|0.65083|0.00261|0.41%|0.63728|-5.87%|0.63659|-5.94%|4.660|8.614|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59056|0.59505|0.00094|0.16%|0.59247|0.00%|0.59259|0.00%|0.256|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8c63ec400c)|0.58866|0.59306|0.00092|0.16%|0.58932|-0.53%|0.58905|-0.60%|2.848|8.055|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/a15155100d)|0.58810|0.59281|0.00103|0.17%|0.58907|-0.57%|0.58881|-0.64%|2.163|8.173|0.000|25.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a15155100d)|0.51756|0.52138|0.00056|0.11%|0.51835|-12.51%|0.51824|-12.55%|3.470|8.614|0.000|26.20 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44303|0.44569|0.00060|0.14%|0.44445|0.00%|0.44456|0.00%|-0.433|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8c63ec400c)|0.45021|0.45407|0.00069|0.15%|0.45167|1.62%|0.45161|1.59%|0.662|-8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/a15155100d)|0.45011|0.45238|0.00054|0.12%|0.45136|1.55%|0.45133|1.52%|-0.011|-8.614|0.000|25.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a15155100d)|0.14555|0.14923|0.00079|0.54%|0.14614|-67.12%|0.14597|-67.17%|3.475|8.614|0.000|26.20 MB|
