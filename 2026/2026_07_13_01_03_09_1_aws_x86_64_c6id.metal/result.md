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
| Time          |2026-07-13 01:03:09 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29216568760 ([Artifacts](https://github.com/php/php-src/actions/runs/29216568760/artifacts/8267364640))|
| Changeset  |https://github.com/php/php-src/compare/1fd15d4254..75cdbcd40b|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40014|0.40263|0.00071|0.18%|0.40074|0.00%|0.40046|0.00%|1.265|0.000|1.000|26.70 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fd15d4254)|0.39073|0.39251|0.00033|0.09%|0.39115|-2.39%|0.39105|-2.35%|2.136|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/75cdbcd40b)|0.39074|0.39330|0.00047|0.12%|0.39126|-2.37%|0.39110|-2.34%|2.294|8.614|0.000|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/75cdbcd40b)|0.36619|0.36875|0.00051|0.14%|0.36681|-8.47%|0.36663|-8.45%|2.154|8.614|0.000|25.72 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67955|0.68203|0.00055|0.08%|0.68041|0.00%|0.68027|0.00%|0.886|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fd15d4254)|0.67006|0.67407|0.00062|0.09%|0.67086|-1.40%|0.67077|-1.40%|3.170|8.614|0.000|25.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/75cdbcd40b)|0.67309|0.67576|0.00050|0.07%|0.67386|-0.96%|0.67375|-0.96%|1.528|8.614|0.000|25.68 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/75cdbcd40b)|0.64344|0.64647|0.00060|0.09%|0.64421|-5.32%|0.64413|-5.31%|2.055|8.614|0.000|26.20 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59316|0.59684|0.00073|0.12%|0.59537|0.00%|0.59547|0.00%|-0.656|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fd15d4254)|0.59029|0.59617|0.00104|0.18%|0.59125|-0.69%|0.59099|-0.75%|3.357|8.183|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/75cdbcd40b)|0.59036|0.59382|0.00049|0.08%|0.59104|-0.73%|0.59099|-0.75%|3.918|8.600|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/75cdbcd40b)|0.52262|0.53441|0.00192|0.37%|0.52384|-12.02%|0.52309|-12.15%|3.774|8.614|0.000|26.29 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44341|0.44892|0.00088|0.20%|0.44485|0.00%|0.44482|0.00%|2.034|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1fd15d4254)|0.44945|0.45197|0.00050|0.11%|0.45090|1.36%|0.45099|1.39%|-0.812|-8.614|0.000|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/75cdbcd40b)|0.44967|0.45197|0.00053|0.12%|0.45089|1.36%|0.45093|1.37%|0.158|-8.614|0.000|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/75cdbcd40b)|0.14417|0.14502|0.00020|0.14%|0.14466|-67.48%|0.14468|-67.47%|-0.224|8.614|0.000|26.29 MB|
