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
| Time          |2026-11-14 00:43:35 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/43536048327 ([Artifacts](https://github.com/php/php-src/actions/runs/43536048327/artifacts/14092095050))|
| Changeset  |https://github.com/php/php-src/compare/4f3d9508be..4aba862339|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39734|0.39969|0.00067|0.17%|0.39792|0.00%|0.39764|0.00%|1.454|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3d9508be)|0.37933|0.38028|0.00018|0.05%|0.37962|-4.60%|0.37962|-4.53%|1.476|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/4aba862339)|0.37896|0.38059|0.00037|0.10%|0.37938|-4.66%|0.37924|-4.63%|1.658|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4aba862339)|0.35287|0.35478|0.00035|0.10%|0.35332|-11.21%|0.35324|-11.16%|1.837|8.614|0.000|26.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67585|0.69967|0.00401|0.59%|0.67747|0.00%|0.67661|0.00%|4.939|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3d9508be)|0.67614|0.68276|0.00093|0.14%|0.67687|-0.09%|0.67664|0.00%|5.438|-0.596|0.551|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/4aba862339)|0.67524|0.68130|0.00093|0.14%|0.67602|-0.21%|0.67580|-0.12%|4.296|6.780|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4aba862339)|0.64717|0.65911|0.00202|0.31%|0.64813|-4.33%|0.64768|-4.28%|4.668|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59141|0.59449|0.00077|0.13%|0.59274|0.00%|0.59265|0.00%|0.308|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3d9508be)|0.58911|0.59219|0.00077|0.13%|0.58986|-0.48%|0.58961|-0.51%|1.835|8.359|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/4aba862339)|0.58861|0.59123|0.00050|0.08%|0.58938|-0.57%|0.58928|-0.57%|1.577|8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4aba862339)|0.51477|0.51775|0.00051|0.10%|0.51570|-13.00%|0.51566|-12.99%|1.798|8.614|0.000|26.36 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44373|0.45193|0.00117|0.26%|0.44483|0.00%|0.44468|0.00%|4.729|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4f3d9508be)|0.45261|0.45537|0.00051|0.11%|0.45397|2.05%|0.45394|2.08%|0.042|-8.614|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/4aba862339)|0.45293|0.45561|0.00056|0.12%|0.45435|2.14%|0.45438|2.18%|-0.592|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4aba862339)|0.14499|0.15421|0.00143|0.98%|0.14600|-67.18%|0.14569|-67.24%|4.472|8.614|0.000|26.36 MB|
