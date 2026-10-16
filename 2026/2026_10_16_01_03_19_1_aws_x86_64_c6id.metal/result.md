### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.38-76.139.amzn2023.x86_64|
| OS            |Amazon Linux 2023.12.20260727|
| GCC           |14.2.1|
| Binary layout strategy |none|
| Time          |2026-10-16 01:03:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/38832958234 ([Artifacts](https://github.com/php/php-src/actions/runs/38832958234/artifacts/12019141797))|
| Changeset  |https://github.com/php/php-src/compare/eec8328398..de6f052c36|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39904|0.39992|0.00019|0.05%|0.39942|0.00%|0.39942|0.00%|0.346|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eec8328398)|0.37675|0.37787|0.00023|0.06%|0.37715|-5.58%|0.37709|-5.59%|1.196|8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/de6f052c36)|0.37659|0.37812|0.00023|0.06%|0.37698|-5.62%|0.37694|-5.63%|2.658|8.614|0.000|26.18 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de6f052c36)|0.35306|0.35468|0.00031|0.09%|0.35375|-11.43%|0.35376|-11.43%|0.755|8.614|0.000|26.21 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68087|0.68642|0.00089|0.13%|0.68184|0.00%|0.68166|0.00%|2.984|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eec8328398)|0.67216|0.67771|0.00112|0.17%|0.67341|-1.24%|0.67306|-1.26%|2.510|8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/de6f052c36)|0.67203|0.67383|0.00049|0.07%|0.67269|-1.34%|0.67258|-1.33%|0.779|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de6f052c36)|0.63831|0.63975|0.00029|0.04%|0.63900|-6.28%|0.63896|-6.26%|0.159|8.614|0.000|26.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59061|0.59374|0.00073|0.12%|0.59231|0.00%|0.59226|0.00%|0.091|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eec8328398)|0.59166|0.59473|0.00074|0.12%|0.59254|0.04%|0.59234|0.01%|1.575|-1.155|0.248|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/de6f052c36)|0.59188|0.59556|0.00088|0.15%|0.59271|0.07%|0.59244|0.03%|2.154|-2.044|0.041|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de6f052c36)|0.51862|0.53022|0.00170|0.33%|0.51980|-12.24%|0.51936|-12.31%|5.004|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44331|0.44867|0.00076|0.17%|0.44462|0.00%|0.44459|0.00%|3.114|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/eec8328398)|0.45063|0.45334|0.00047|0.10%|0.45184|1.62%|0.45182|1.63%|0.331|-8.614|0.000|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/de6f052c36)|0.45064|0.45837|0.00104|0.23%|0.45201|1.66%|0.45194|1.65%|4.686|-8.614|0.000|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de6f052c36)|0.14352|0.14460|0.00021|0.15%|0.14421|-67.57%|0.14422|-67.56%|-0.576|8.614|0.000|26.24 MB|
