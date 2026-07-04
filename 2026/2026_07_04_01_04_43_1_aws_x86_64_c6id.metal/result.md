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
| Time          |2026-07-04 01:04:43 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28690164396 ([Artifacts](https://github.com/php/php-src/actions/runs/28690164396/artifacts/8077257946))|
| Changeset  |https://github.com/php/php-src/compare/092de40341..19f94430d5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39806|0.40054|0.00077|0.19%|0.39882|0.00%|0.39848|0.00%|1.248|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/092de40341)|0.39008|0.39222|0.00037|0.09%|0.39052|-2.08%|0.39043|-2.02%|2.404|8.614|0.000|25.67 MB|
|[PHP - master](https://github.com/php/php-src/commit/19f94430d5)|0.38991|0.39148|0.00038|0.10%|0.39049|-2.09%|0.39043|-2.02%|0.633|8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/19f94430d5)|0.36419|0.36595|0.00043|0.12%|0.36484|-8.52%|0.36478|-8.46%|0.743|8.614|0.000|25.86 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67714|0.67995|0.00059|0.09%|0.67788|0.00%|0.67769|0.00%|1.649|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/092de40341)|0.66767|0.67144|0.00068|0.10%|0.66843|-1.40%|0.66821|-1.40%|2.183|8.614|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/19f94430d5)|0.67423|0.67705|0.00060|0.09%|0.67506|-0.42%|0.67492|-0.41%|1.771|8.614|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/19f94430d5)|0.64237|0.64892|0.00120|0.19%|0.64344|-5.08%|0.64307|-5.11%|2.932|8.614|0.000|26.19 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59174|0.59630|0.00095|0.16%|0.59398|0.00%|0.59408|0.00%|0.052|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/092de40341)|0.58965|0.59251|0.00053|0.09%|0.59042|-0.60%|0.59028|-0.64%|1.451|8.600|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/19f94430d5)|0.58974|0.59372|0.00078|0.13%|0.59068|-0.56%|0.59053|-0.60%|2.141|8.428|0.000|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/19f94430d5)|0.52111|0.52607|0.00091|0.17%|0.52207|-12.11%|0.52181|-12.17%|2.923|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44342|0.45270|0.00173|0.39%|0.44504|0.00%|0.44460|0.00%|3.645|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/092de40341)|0.45005|0.45281|0.00062|0.14%|0.45125|1.40%|0.45111|1.46%|0.520|-7.938|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/19f94430d5)|0.45000|0.45469|0.00081|0.18%|0.45130|1.41%|0.45119|1.48%|1.886|-7.952|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/19f94430d5)|0.14405|0.14589|0.00028|0.19%|0.14447|-67.54%|0.14446|-67.51%|2.616|8.614|0.000|26.24 MB|
