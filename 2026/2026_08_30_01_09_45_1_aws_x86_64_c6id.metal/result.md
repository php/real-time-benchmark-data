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
| Time          |2026-08-30 01:09:45 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33285010474 ([Artifacts](https://github.com/php/php-src/actions/runs/33285010474/artifacts/9724497277))|
| Changeset  |https://github.com/php/php-src/compare/ec93b0b941..278d290410|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40075|0.40257|0.00031|0.08%|0.40126|0.00%|0.40124|0.00%|1.748|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ec93b0b941)|0.37640|0.37855|0.00049|0.13%|0.37713|-6.01%|0.37700|-6.04%|1.016|8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/278d290410)|0.37664|0.37770|0.00027|0.07%|0.37708|-6.03%|0.37703|-6.03%|0.501|8.614|0.000|25.87 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68370|0.68791|0.00072|0.11%|0.68507|0.00%|0.68502|0.00%|1.153|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ec93b0b941)|0.67420|0.67693|0.00054|0.08%|0.67488|-1.49%|0.67478|-1.50%|1.454|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/278d290410)|0.67396|0.67712|0.00051|0.07%|0.67462|-1.53%|0.67448|-1.54%|2.659|8.614|0.000|25.83 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59264|0.59683|0.00087|0.15%|0.59414|0.00%|0.59405|0.00%|0.420|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ec93b0b941)|0.59349|0.59927|0.00150|0.25%|0.59449|0.06%|0.59399|-0.01%|2.532|-0.162|0.871|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/278d290410)|0.59319|0.60008|0.00146|0.25%|0.59463|0.08%|0.59430|0.04%|2.754|-1.355|0.176|26.20 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44329|0.44587|0.00048|0.11%|0.44471|0.00%|0.44470|0.00%|-0.307|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ec93b0b941)|0.45091|0.45483|0.00082|0.18%|0.45207|1.65%|0.45189|1.62%|1.691|-8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/278d290410)|0.45067|0.45440|0.00075|0.17%|0.45188|1.61%|0.45172|1.58%|1.265|-8.614|0.000|26.20 MB|
