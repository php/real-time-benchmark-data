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
| Time          |2026-06-29 01:29:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28343000757 ([Artifacts](https://github.com/php/php-src/actions/runs/28343000757/artifacts/7941307713))|
| Changeset  |https://github.com/php/php-src/compare/08c6ecac52..eaa6325959|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40020|0.40242|0.00072|0.18%|0.40095|0.00%|0.40066|0.00%|1.232|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/08c6ecac52)|0.39202|0.39365|0.00033|0.08%|0.39269|-2.06%|0.39268|-1.99%|0.460|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/eaa6325959)|0.39244|0.39382|0.00029|0.07%|0.39285|-2.02%|0.39277|-1.97%|1.537|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eaa6325959)|0.36468|0.36753|0.00050|0.14%|0.36523|-8.91%|0.36510|-8.88%|2.560|8.614|0.000|25.73 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68069|0.68630|0.00095|0.14%|0.68145|0.00%|0.68127|0.00%|3.603|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/08c6ecac52)|0.67746|0.68231|0.00105|0.16%|0.67901|-0.36%|0.67873|-0.37%|1.415|7.835|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/eaa6325959)|0.67378|0.68005|0.00090|0.13%|0.67449|-1.02%|0.67434|-1.02%|4.988|8.614|0.000|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eaa6325959)|0.64181|0.64528|0.00056|0.09%|0.64260|-5.70%|0.64247|-5.69%|2.398|8.614|0.000|26.19 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59407|0.59890|0.00097|0.16%|0.59598|0.00%|0.59600|0.00%|0.152|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/08c6ecac52)|0.58933|0.59240|0.00061|0.10%|0.59023|-0.96%|0.59020|-0.97%|1.644|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/eaa6325959)|0.59162|0.59546|0.00090|0.15%|0.59247|-0.59%|0.59219|-0.64%|2.220|8.324|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eaa6325959)|0.52204|0.52607|0.00079|0.15%|0.52295|-12.25%|0.52273|-12.29%|2.486|8.614|0.000|26.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44349|0.44570|0.00055|0.12%|0.44465|0.00%|0.44462|0.00%|-0.078|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/08c6ecac52)|0.44942|0.45165|0.00050|0.11%|0.45069|1.36%|0.45068|1.36%|-0.288|-8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/eaa6325959)|0.44983|0.45217|0.00054|0.12%|0.45081|1.39%|0.45082|1.40%|0.166|-8.614|0.000|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eaa6325959)|0.14439|0.14539|0.00019|0.13%|0.14481|-67.43%|0.14481|-67.43%|0.387|8.614|0.000|26.26 MB|
