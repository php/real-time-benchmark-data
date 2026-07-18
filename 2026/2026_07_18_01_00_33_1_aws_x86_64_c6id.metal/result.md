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
| Time          |2026-07-18 01:00:33 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29624293651 ([Artifacts](https://github.com/php/php-src/actions/runs/29624293651/artifacts/8423897646))|
| Changeset  |https://github.com/php/php-src/compare/51300b7f59..e3de8edbae|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39456|0.39629|0.00026|0.07%|0.39503|0.00%|0.39503|0.00%|2.402|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51300b7f59)|0.38644|0.38836|0.00040|0.10%|0.38701|-2.03%|0.38690|-2.06%|1.848|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3de8edbae)|0.38809|0.39221|0.00067|0.17%|0.38872|-1.60%|0.38854|-1.64%|3.625|8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3de8edbae)|0.36165|0.36348|0.00044|0.12%|0.36232|-8.28%|0.36220|-8.31%|1.247|8.614|0.000|25.80 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67267|0.67558|0.00060|0.09%|0.67342|0.00%|0.67333|0.00%|1.135|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51300b7f59)|0.66535|0.66752|0.00051|0.08%|0.66619|-1.07%|0.66604|-1.08%|0.872|8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3de8edbae)|0.66403|0.66552|0.00034|0.05%|0.66451|-1.32%|0.66443|-1.32%|1.233|8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3de8edbae)|0.63665|0.63819|0.00030|0.05%|0.63712|-5.39%|0.63704|-5.39%|1.327|8.614|0.000|26.33 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58839|0.59242|0.00092|0.16%|0.59060|0.00%|0.59062|0.00%|-0.067|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51300b7f59)|0.58296|0.58727|0.00065|0.11%|0.58351|-1.20%|0.58339|-1.22%|4.086|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3de8edbae)|0.58531|0.59011|0.00104|0.18%|0.58718|-0.58%|0.58715|-0.59%|0.734|8.400|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3de8edbae)|0.51511|0.51944|0.00107|0.21%|0.51634|-12.57%|0.51604|-12.63%|1.517|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44294|0.44579|0.00061|0.14%|0.44443|0.00%|0.44441|0.00%|-0.109|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51300b7f59)|0.44952|0.45191|0.00063|0.14%|0.45055|1.38%|0.45048|1.37%|0.336|-8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/e3de8edbae)|0.44835|0.45206|0.00069|0.15%|0.44899|1.03%|0.44886|1.00%|3.342|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e3de8edbae)|0.14397|0.14499|0.00021|0.14%|0.14436|-67.52%|0.14434|-67.52%|0.665|8.614|0.000|26.28 MB|
