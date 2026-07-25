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
| Time          |2026-07-25 01:02:52 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/30137626485 ([Artifacts](https://github.com/php/php-src/actions/runs/30137626485/artifacts/8613944564))|
| Changeset  |https://github.com/php/php-src/compare/1f4a88c5c3..de5a5820ef|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39464|0.39827|0.00051|0.13%|0.39500|0.00%|0.39491|0.00%|5.642|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1f4a88c5c3)|0.38742|0.38860|0.00020|0.05%|0.38783|-1.81%|0.38781|-1.80%|1.405|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/de5a5820ef)|0.38815|0.39042|0.00053|0.14%|0.38868|-1.60%|0.38851|-1.62%|2.355|8.614|0.000|25.81 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de5a5820ef)|0.36154|0.36324|0.00034|0.09%|0.36206|-8.34%|0.36202|-8.33%|1.576|8.614|0.000|25.75 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67234|0.67722|0.00092|0.14%|0.67321|0.00%|0.67292|0.00%|2.470|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1f4a88c5c3)|0.66845|0.67008|0.00038|0.06%|0.66919|-0.60%|0.66922|-0.55%|0.182|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/de5a5820ef)|0.66925|0.67445|0.00083|0.12%|0.66990|-0.49%|0.66963|-0.49%|3.797|8.310|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de5a5820ef)|0.63559|0.64463|0.00142|0.22%|0.63647|-5.46%|0.63617|-5.46%|4.629|8.614|0.000|26.28 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58882|0.59301|0.00091|0.15%|0.59079|0.00%|0.59079|0.00%|0.330|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1f4a88c5c3)|0.58584|0.59564|0.00167|0.28%|0.58752|-0.55%|0.58708|-0.63%|2.870|7.738|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/de5a5820ef)|0.58562|0.58962|0.00101|0.17%|0.58653|-0.72%|0.58624|-0.77%|2.211|8.531|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de5a5820ef)|0.51407|0.51781|0.00081|0.16%|0.51482|-12.86%|0.51461|-12.89%|2.731|8.614|0.000|26.30 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44260|0.44576|0.00064|0.14%|0.44457|0.00%|0.44458|0.00%|-0.495|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1f4a88c5c3)|0.44849|0.44960|0.00029|0.06%|0.44903|1.00%|0.44908|1.01%|-0.184|-8.614|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/de5a5820ef)|0.44830|0.45003|0.00037|0.08%|0.44902|1.00%|0.44904|1.00%|0.243|-8.614|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/de5a5820ef)|0.14412|0.14493|0.00020|0.14%|0.14452|-67.49%|0.14451|-67.50%|-0.177|8.614|0.000|26.30 MB|
