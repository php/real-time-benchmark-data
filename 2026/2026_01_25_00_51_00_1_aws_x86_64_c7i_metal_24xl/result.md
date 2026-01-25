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
| Time          |2026-01-25 00:51:00 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21324335427 ([Artifacts](https://github.com/php/php-src/actions/runs/21324335427/artifacts/5246510260))|
| Changeset  |https://github.com/php/php-src/compare/fb5d4784fe..5f367b8a01|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45348|0.45512|0.00034|0.07%|0.45421|0.00%|0.45422|0.00%|-0.108|0.001|0.999|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fb5d4784fe)|0.44866|0.45604|0.00075|0.17%|0.44952|-1.03%|0.44944|-1.05%|6.601|-11.971|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/5f367b8a01)|0.44776|0.45467|0.00079|0.17%|0.44933|-1.08%|0.44924|-1.09%|4.134|-11.986|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5f367b8a01)|0.42832|0.43259|0.00061|0.14%|0.43132|-5.04%|0.43133|-5.04%|-2.196|-12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.76829|0.78783|0.00154|0.20%|0.77549|0.00%|0.77539|0.00%|4.285|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fb5d4784fe)|0.76908|0.77708|0.00097|0.12%|0.77461|-0.11%|0.77447|-0.12%|-1.024|-8.177|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/5f367b8a01)|0.76527|0.77487|0.00138|0.18%|0.77044|-0.65%|0.77045|-0.64%|-0.076|-11.949|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5f367b8a01)|0.90678|1.17885|0.03493|3.01%|1.16066|49.67%|1.16909|50.77%|-5.406|-12.216|0.000|27.01 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65885|0.66161|0.00047|0.07%|0.66005|0.00%|0.65999|0.00%|0.476|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fb5d4784fe)|0.66543|0.68593|0.00268|0.40%|0.66675|1.02%|0.66639|0.97%|6.690|-12.216|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/5f367b8a01)|0.66587|0.66869|0.00052|0.08%|0.66682|1.03%|0.66678|1.03%|0.839|-12.216|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5f367b8a01)|0.59257|0.59506|0.00046|0.08%|0.59335|-10.11%|0.59322|-10.12%|1.101|-12.216|0.000|27.01 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42539|0.45064|0.00277|0.65%|0.42835|0.00%|0.42786|0.00%|5.598|0.001|0.999|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fb5d4784fe)|0.42319|0.44327|0.00217|0.51%|0.42669|-0.39%|0.42651|-0.31%|4.645|-6.931|0.000|27.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/5f367b8a01)|0.42390|0.43068|0.00132|0.31%|0.42670|-0.39%|0.42661|-0.29%|0.444|-6.600|0.000|27.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5f367b8a01)|0.13804|0.14516|0.00139|0.99%|0.14073|-67.15%|0.14057|-67.14%|0.627|-12.216|0.000|27.01 MB|
