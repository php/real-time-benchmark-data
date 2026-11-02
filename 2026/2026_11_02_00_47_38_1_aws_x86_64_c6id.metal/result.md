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
| Time          |2026-11-02 00:47:38 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/41369025803 ([Artifacts](https://github.com/php/php-src/actions/runs/41369025803/artifacts/13109108832))|
| Changeset  |https://github.com/php/php-src/compare/ea7f02e25d..f4d80ce83e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39428|0.39498|0.00017|0.04%|0.39460|0.00%|0.39461|0.00%|0.025|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea7f02e25d)|0.37658|0.37753|0.00018|0.05%|0.37692|-4.48%|0.37689|-4.49%|0.943|8.614|0.000|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4d80ce83e)|0.37737|0.37835|0.00023|0.06%|0.37769|-4.28%|0.37765|-4.30%|1.359|8.614|0.000|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4d80ce83e)|0.35233|0.35515|0.00046|0.13%|0.35300|-10.54%|0.35290|-10.57%|2.224|8.614|0.000|26.33 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67246|0.68538|0.00182|0.27%|0.67349|0.00%|0.67307|0.00%|5.894|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea7f02e25d)|0.67463|0.68365|0.00314|0.46%|0.67797|0.66%|0.67619|0.46%|0.551|-8.138|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4d80ce83e)|0.68265|0.68761|0.00088|0.13%|0.68348|1.48%|0.68323|1.51%|3.161|-8.283|0.000|26.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4d80ce83e)|0.64704|0.65242|0.00117|0.18%|0.64801|-3.78%|0.64775|-3.76%|2.634|8.614|0.000|26.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58721|0.59241|0.00090|0.15%|0.58912|0.00%|0.58912|0.00%|0.780|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea7f02e25d)|0.59313|0.59626|0.00078|0.13%|0.59389|0.81%|0.59361|0.76%|1.978|-8.614|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4d80ce83e)|0.59311|0.59605|0.00056|0.10%|0.59367|0.77%|0.59351|0.75%|2.823|-8.614|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4d80ce83e)|0.52054|0.52378|0.00072|0.14%|0.52124|-11.52%|0.52110|-11.55%|2.644|8.614|0.000|26.43 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44327|0.44904|0.00085|0.19%|0.44455|0.00%|0.44444|0.00%|3.044|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea7f02e25d)|0.45293|0.45549|0.00065|0.14%|0.45444|2.23%|0.45448|2.26%|-0.576|-8.614|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/f4d80ce83e)|0.45261|0.45634|0.00079|0.17%|0.45443|2.22%|0.45450|2.26%|-0.040|-8.614|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f4d80ce83e)|0.14427|0.14529|0.00024|0.17%|0.14490|-67.40%|0.14493|-67.39%|-0.706|8.614|0.000|26.43 MB|
