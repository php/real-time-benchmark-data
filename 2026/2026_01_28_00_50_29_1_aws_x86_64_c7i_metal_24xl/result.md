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
| Time          |2026-01-28 00:50:29 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/21420320576 ([Artifacts](https://github.com/php/php-src/actions/runs/21420320576/artifacts/5281632450))|
| Changeset  |https://github.com/php/php-src/compare/74b8fdb95b..cc50c9e928|

### Laravel 12.11.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.45092|0.45328|0.00034|0.08%|0.45169|0.00%|0.45167|0.00%|1.785|0.000|1.000|27.60 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/74b8fdb95b)|0.44718|0.45140|0.00045|0.10%|0.44785|-0.85%|0.44780|-0.86%|5.111|12.179|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/cc50c9e928)|0.44739|0.45436|0.00071|0.16%|0.44802|-0.81%|0.44792|-0.83%|7.213|11.971|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cc50c9e928)|0.42768|0.42900|0.00026|0.06%|0.42811|-5.22%|0.42806|-5.23%|0.875|12.216|0.000|27.00 MB|

### Symfony 2.8.0 demo app - 100 consecutive runs, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.76787|0.78716|0.00155|0.20%|0.77459|0.00%|0.77438|0.00%|4.759|0.000|1.000|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/74b8fdb95b)|0.76637|0.78571|0.00155|0.20%|0.77491|0.04%|0.77476|0.05%|1.913|-4.540|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/cc50c9e928)|0.76483|0.78150|0.00222|0.29%|0.76968|-0.63%|0.76966|-0.61%|1.570|11.059|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cc50c9e928)|0.93758|1.17979|0.03524|3.06%|1.15018|48.49%|1.15942|49.72%|-4.272|-12.216|0.000|27.00 MB|

### Wordpress 6.9 main page - 100 consecutive runs, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.65897|0.67982|0.00281|0.43%|0.66023|0.00%|0.65983|0.00%|6.805|0.000|1.000|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/74b8fdb95b)|0.66466|0.68481|0.00269|0.40%|0.66599|0.87%|0.66556|0.87%|6.681|-11.737|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/cc50c9e928)|0.66464|0.68459|0.00194|0.29%|0.66601|0.87%|0.66577|0.90%|9.109|-11.732|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cc50c9e928)|0.59283|0.59554|0.00047|0.08%|0.59370|-10.08%|0.59365|-10.03%|1.042|12.216|0.000|27.00 MB|

### bench.php - 100 consecutive runs, 10 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.42548|0.45005|0.00259|0.60%|0.42852|0.00%|0.42828|0.00%|5.948|0.000|1.000|27.61 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/74b8fdb95b)|0.42318|0.43230|0.00184|0.43%|0.42695|-0.37%|0.42694|-0.31%|0.329|5.385|0.000|27.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/cc50c9e928)|0.42314|0.43154|0.00177|0.41%|0.42694|-0.37%|0.42693|-0.32%|0.223|5.628|0.000|27.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cc50c9e928)|0.13818|0.14436|0.00136|0.96%|0.14106|-67.08%|0.14101|-67.08%|0.217|12.216|0.000|27.00 MB|
