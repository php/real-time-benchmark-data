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
| Time          |2026-01-27 00:50:26 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21380040316 ([Artifacts](https://github.com/php/php-src/actions/runs/21380040316/artifacts/5266062514))|
| Changeset  |https://github.com/php/php-src/compare/9f774e3a85..74b8fdb95b|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45127|0.45866|0.00119|0.26%|0.45189|0.00%|0.45166|0.00%|5.247|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9f774e3a85)|0.44645|0.44786|0.00027|0.06%|0.44710|-1.06%|0.44708|-1.01%|0.800|12.216|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/74b8fdb95b)|0.44753|0.44927|0.00029|0.06%|0.44806|-0.85%|0.44802|-0.81%|1.012|12.216|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/74b8fdb95b)|0.42778|0.42898|0.00026|0.06%|0.42819|-5.24%|0.42813|-5.21%|1.109|12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.76955|0.77589|0.00084|0.11%|0.77405|0.00%|0.77388|0.00%|-0.940|0.000|1.000|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9f774e3a85)|0.77172|0.78518|0.00150|0.19%|0.77281|-0.16%|0.77244|-0.19%|6.023|9.224|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/74b8fdb95b)|0.76530|0.77961|0.00194|0.25%|0.76968|-0.56%|0.76964|-0.55%|1.640|11.204|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/74b8fdb95b)|0.91474|1.17504|0.04067|3.53%|1.15334|49.00%|1.16389|50.40%|-4.561|-12.216|0.000|27.00 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65862|0.67994|0.00286|0.43%|0.66017|0.00%|0.65975|0.00%|6.647|0.000|1.000|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9f774e3a85)|0.66480|0.68504|0.00196|0.29%|0.66611|0.90%|0.66591|0.93%|9.248|-11.732|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/74b8fdb95b)|0.66450|0.68516|0.00205|0.31%|0.66594|0.87%|0.66571|0.90%|8.597|-11.732|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/74b8fdb95b)|0.59235|0.59434|0.00044|0.07%|0.59345|-10.11%|0.59347|-10.05%|-0.219|12.216|0.000|27.00 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42557|0.43158|0.00133|0.31%|0.42820|0.00%|0.42804|0.00%|0.443|0.000|1.000|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/9f774e3a85)|0.42372|0.43045|0.00146|0.34%|0.42701|-0.28%|0.42691|-0.26%|0.119|5.449|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/74b8fdb95b)|0.42378|0.43209|0.00180|0.42%|0.42704|-0.27%|0.42697|-0.25%|0.370|4.799|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/74b8fdb95b)|0.13785|0.14446|0.00132|0.94%|0.14086|-67.10%|0.14070|-67.13%|0.557|12.216|0.000|27.00 MB|
