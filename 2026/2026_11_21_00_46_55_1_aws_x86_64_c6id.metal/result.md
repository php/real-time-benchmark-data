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
| Time          |2026-11-21 00:46:55 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/44845989089 ([Artifacts](https://github.com/php/php-src/actions/runs/44845989089/artifacts/14684443759))|
| Changeset  |https://github.com/php/php-src/compare/92e1542d27..95bca157ab|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39400|0.39493|0.00018|0.05%|0.39447|0.00%|0.39447|0.00%|0.156|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92e1542d27)|0.37588|0.37709|0.00025|0.07%|0.37627|-4.61%|0.37620|-4.63%|1.762|8.614|0.000|25.88 MB|
|[PHP - master](https://github.com/php/php-src/commit/95bca157ab)|0.37520|0.37748|0.00035|0.09%|0.37574|-4.75%|0.37567|-4.77%|2.767|8.614|0.000|25.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95bca157ab)|0.34847|0.34949|0.00020|0.06%|0.34885|-11.57%|0.34885|-11.57%|0.749|8.614|0.000|26.25 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67218|0.67978|0.00138|0.21%|0.67313|0.00%|0.67258|0.00%|3.073|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92e1542d27)|0.67621|0.68072|0.00098|0.15%|0.67711|0.59%|0.67675|0.62%|2.337|-8.097|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/95bca157ab)|0.67453|0.67790|0.00059|0.09%|0.67528|0.32%|0.67511|0.38%|2.158|-7.276|0.000|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95bca157ab)|0.64578|0.65427|0.00136|0.21%|0.64661|-3.94%|0.64627|-3.91%|4.442|8.614|0.000|26.37 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58771|0.59144|0.00088|0.15%|0.58923|0.00%|0.58919|0.00%|0.202|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92e1542d27)|0.58627|0.59218|0.00102|0.17%|0.58715|-0.35%|0.58684|-0.40%|3.107|7.531|0.000|26.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/95bca157ab)|0.58719|0.59014|0.00067|0.11%|0.58795|-0.22%|0.58772|-0.25%|1.870|6.690|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95bca157ab)|0.51280|0.51547|0.00060|0.12%|0.51344|-12.86%|0.51331|-12.88%|2.017|8.614|0.000|26.48 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44359|0.44579|0.00055|0.12%|0.44458|0.00%|0.44454|0.00%|0.361|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/92e1542d27)|0.45221|0.45472|0.00058|0.13%|0.45359|2.03%|0.45366|2.05%|-0.126|-8.614|0.000|26.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/95bca157ab)|0.45298|0.45513|0.00053|0.12%|0.45403|2.13%|0.45401|2.13%|0.018|-8.614|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/95bca157ab)|0.14507|0.14912|0.00085|0.58%|0.14572|-67.22%|0.14553|-67.26%|3.312|8.614|0.000|26.48 MB|
