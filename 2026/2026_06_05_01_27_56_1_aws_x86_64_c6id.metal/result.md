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
| Time          |2026-06-05 01:27:56 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26989762523 ([Artifacts](https://github.com/php/php-src/actions/runs/26989762523/artifacts/7427465574))|
| Changeset  |https://github.com/php/php-src/compare/425cd3d6a1..95b5b48799|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39852|0.39931|0.00021|0.05%|0.39886|0.00%|0.39880|0.00%|0.473|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/425cd3d6a1)|0.38908|0.39031|0.00027|0.07%|0.38955|-2.33%|0.38951|-2.33%|0.811|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/95b5b48799)|0.38726|0.39025|0.00053|0.14%|0.38772|-2.79%|0.38754|-2.82%|2.869|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95b5b48799)|0.36306|0.36566|0.00047|0.13%|0.36371|-8.81%|0.36369|-8.81%|2.628|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67747|0.68072|0.00063|0.09%|0.67839|0.00%|0.67824|0.00%|1.297|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/425cd3d6a1)|0.67419|0.67739|0.00058|0.09%|0.67492|-0.51%|0.67478|-0.51%|2.358|8.614|0.000|25.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/95b5b48799)|0.67074|0.67597|0.00118|0.18%|0.67367|-0.70%|0.67369|-0.67%|-0.223|8.614|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95b5b48799)|0.63971|0.64674|0.00125|0.19%|0.64174|-5.40%|0.64167|-5.39%|1.658|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59215|0.59603|0.00100|0.17%|0.59394|0.00%|0.59383|0.00%|0.232|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/425cd3d6a1)|0.59021|0.59380|0.00078|0.13%|0.59095|-0.50%|0.59071|-0.52%|2.683|8.159|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/95b5b48799)|0.58884|0.59302|0.00101|0.17%|0.58977|-0.70%|0.58940|-0.74%|2.215|8.469|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95b5b48799)|0.52020|0.53144|0.00169|0.32%|0.52135|-12.22%|0.52089|-12.28%|4.744|8.614|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44304|0.44604|0.00052|0.12%|0.44463|0.00%|0.44464|0.00%|-0.342|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/425cd3d6a1)|0.45087|0.45554|0.00088|0.20%|0.45204|1.67%|0.45192|1.64%|1.829|-8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/95b5b48799)|0.45016|0.45259|0.00058|0.13%|0.45151|1.55%|0.45156|1.56%|-0.255|-8.614|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95b5b48799)|0.14550|0.14954|0.00068|0.47%|0.14612|-67.14%|0.14599|-67.17%|4.290|8.614|0.000|26.19 MB|
