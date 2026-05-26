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
| Time          |2026-05-26 01:21:43 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26426888399 ([Artifacts](https://github.com/php/php-src/actions/runs/26426888399/artifacts/7207632812))|
| Changeset  |https://github.com/php/php-src/compare/d8a5aec1cc..9e1b285f65|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39467|0.39640|0.00028|0.07%|0.39503|0.00%|0.39501|0.00%|2.886|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8a5aec1cc)|0.38721|0.38919|0.00047|0.12%|0.38792|-1.80%|0.38781|-1.82%|1.165|8.614|0.000|25.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/9e1b285f65)|0.38714|0.38882|0.00032|0.08%|0.38758|-1.89%|0.38754|-1.89%|1.793|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9e1b285f65)|0.35959|0.36113|0.00032|0.09%|0.36005|-8.85%|0.36001|-8.86%|1.330|8.614|0.000|25.73 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67375|0.67593|0.00053|0.08%|0.67438|0.00%|0.67416|0.00%|1.488|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8a5aec1cc)|0.67362|0.67514|0.00035|0.05%|0.67410|-0.04%|0.67403|-0.02%|1.181|3.213|0.001|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/9e1b285f65)|0.66931|0.67275|0.00049|0.07%|0.66977|-0.68%|0.66967|-0.67%|4.772|8.614|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9e1b285f65)|0.63680|0.63844|0.00035|0.05%|0.63722|-5.51%|0.63717|-5.49%|1.426|8.614|0.000|26.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58838|0.59395|0.00112|0.19%|0.59030|0.00%|0.59033|0.00%|0.724|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8a5aec1cc)|0.58668|0.59445|0.00151|0.26%|0.58819|-0.36%|0.58754|-0.47%|1.906|6.411|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/9e1b285f65)|0.58541|0.58915|0.00086|0.15%|0.58629|-0.68%|0.58601|-0.73%|1.787|8.572|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9e1b285f65)|0.51555|0.52616|0.00154|0.30%|0.51638|-12.52%|0.51605|-12.58%|5.504|8.614|0.000|26.30 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44181|0.44594|0.00068|0.15%|0.44295|0.00%|0.44295|0.00%|1.792|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d8a5aec1cc)|0.44916|0.45170|0.00052|0.12%|0.45020|1.64%|0.45022|1.64%|0.205|-8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/9e1b285f65)|0.45084|0.45258|0.00051|0.11%|0.45172|1.98%|0.45169|1.98%|-0.177|-8.614|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9e1b285f65)|0.14366|0.15202|0.00122|0.85%|0.14434|-67.42%|0.14410|-67.47%|5.539|8.614|0.000|26.30 MB|
