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
| Time          |2026-07-26 01:04:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30182243888 ([Artifacts](https://github.com/php/php-src/actions/runs/30182243888/artifacts/8626366639))|
| Changeset  |https://github.com/php/php-src/compare/de5a5820ef..f465d35334|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39637|0.39721|0.00017|0.04%|0.39673|0.00%|0.39670|0.00%|0.597|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de5a5820ef)|0.38972|0.39076|0.00022|0.06%|0.39002|-1.69%|0.38997|-1.70%|1.530|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/f465d35334)|0.39031|0.39278|0.00061|0.16%|0.39096|-1.45%|0.39076|-1.50%|1.997|8.614|0.000|25.75 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f465d35334)|0.36210|0.36408|0.00050|0.14%|0.36275|-8.57%|0.36258|-8.60%|1.389|8.614|0.000|25.82 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67481|0.67697|0.00057|0.08%|0.67546|0.00%|0.67525|0.00%|0.936|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de5a5820ef)|0.67169|0.67492|0.00057|0.09%|0.67245|-0.45%|0.67230|-0.44%|2.118|8.579|0.000|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/f465d35334)|0.66613|0.67040|0.00077|0.12%|0.66677|-1.29%|0.66656|-1.29%|2.856|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f465d35334)|0.63642|0.63931|0.00049|0.08%|0.63704|-5.69%|0.63692|-5.68%|2.291|8.614|0.000|26.35 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58979|0.59443|0.00107|0.18%|0.59195|0.00%|0.59194|0.00%|0.166|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de5a5820ef)|0.58690|0.59104|0.00092|0.16%|0.58777|-0.71%|0.58750|-0.75%|2.512|8.441|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/f465d35334)|0.58669|0.58889|0.00040|0.07%|0.58730|-0.79%|0.58724|-0.79%|1.297|8.614|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f465d35334)|0.51603|0.51991|0.00086|0.17%|0.51695|-12.67%|0.51671|-12.71%|1.990|8.614|0.000|26.31 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44325|0.45226|0.00163|0.37%|0.44485|0.00%|0.44437|0.00%|3.375|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/de5a5820ef)|0.44845|0.44995|0.00038|0.09%|0.44908|0.95%|0.44901|1.04%|0.418|-7.924|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/f465d35334)|0.44861|0.45122|0.00041|0.09%|0.44929|1.00%|0.44929|1.11%|1.912|-7.931|0.000|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f465d35334)|0.14401|0.14532|0.00023|0.16%|0.14453|-67.51%|0.14452|-67.48%|0.749|8.614|0.000|26.33 MB|
