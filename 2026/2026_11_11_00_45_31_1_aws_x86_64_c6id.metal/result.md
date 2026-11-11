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
| Time          |2026-11-11 00:45:31 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/42933792753 ([Artifacts](https://github.com/php/php-src/actions/runs/42933792753/artifacts/13819058635))|
| Changeset  |https://github.com/php/php-src/compare/ac9b9c225d..2545a971f9|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39729|0.39912|0.00029|0.07%|0.39781|0.00%|0.39775|0.00%|2.173|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9b9c225d)|0.38121|0.38246|0.00023|0.06%|0.38168|-4.05%|0.38168|-4.04%|0.584|8.614|0.000|25.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/2545a971f9)|0.37903|0.38030|0.00024|0.06%|0.37941|-4.62%|0.37940|-4.61%|1.620|8.614|0.000|25.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2545a971f9)|0.35229|0.35344|0.00023|0.07%|0.35272|-11.33%|0.35266|-11.33%|1.095|8.614|0.000|25.92 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67672|0.68945|0.00179|0.26%|0.67787|0.00%|0.67744|0.00%|5.779|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9b9c225d)|0.68389|0.68586|0.00037|0.05%|0.68443|0.97%|0.68439|1.03%|1.558|-8.269|0.000|26.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/2545a971f9)|0.67681|0.67889|0.00041|0.06%|0.67754|-0.05%|0.67746|0.00%|1.206|0.128|0.899|26.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2545a971f9)|0.64958|0.65154|0.00038|0.06%|0.65018|-4.09%|0.65011|-4.03%|1.381|8.614|0.000|26.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59065|0.59409|0.00075|0.13%|0.59246|0.00%|0.59240|0.00%|0.029|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9b9c225d)|0.58917|0.59751|0.00125|0.21%|0.59001|-0.41%|0.58968|-0.46%|4.772|8.042|0.000|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/2545a971f9)|0.58881|0.59166|0.00067|0.11%|0.58949|-0.50%|0.58931|-0.52%|2.193|8.483|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2545a971f9)|0.51581|0.51967|0.00075|0.14%|0.51654|-12.81%|0.51636|-12.84%|2.792|8.614|0.000|26.43 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44337|0.44705|0.00079|0.18%|0.44475|0.00%|0.44459|0.00%|0.677|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac9b9c225d)|0.45280|0.45532|0.00061|0.13%|0.45409|2.10%|0.45409|2.13%|-0.105|-8.614|0.000|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/2545a971f9)|0.45280|0.45518|0.00066|0.14%|0.45404|2.09%|0.45400|2.11%|0.063|-8.614|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2545a971f9)|0.14466|0.15371|0.00133|0.91%|0.14551|-67.28%|0.14517|-67.35%|5.159|8.614|0.000|26.43 MB|
