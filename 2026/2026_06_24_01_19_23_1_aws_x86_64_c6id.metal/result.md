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
| Time          |2026-06-24 01:19:23 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/28068468116 ([Artifacts](https://github.com/php/php-src/actions/runs/28068468116/artifacts/7838436057))|
| Changeset  |https://github.com/php/php-src/compare/e0113cd1d6..6f0aa11d23|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39645|0.39734|0.00019|0.05%|0.39688|0.00%|0.39684|0.00%|0.120|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e0113cd1d6)|0.39006|0.39249|0.00041|0.11%|0.39095|-1.49%|0.39092|-1.49%|1.058|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f0aa11d23)|0.39036|0.39415|0.00057|0.15%|0.39084|-1.52%|0.39070|-1.55%|4.334|8.614|0.000|25.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f0aa11d23)|0.36374|0.36688|0.00055|0.15%|0.36449|-8.16%|0.36437|-8.18%|2.271|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67460|0.67727|0.00049|0.07%|0.67524|0.00%|0.67519|0.00%|1.941|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e0113cd1d6)|0.66736|0.67027|0.00057|0.09%|0.66795|-1.08%|0.66779|-1.10%|1.986|8.614|0.000|25.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f0aa11d23)|0.66834|0.67849|0.00157|0.24%|0.66927|-0.88%|0.66884|-0.94%|4.523|8.269|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f0aa11d23)|0.63996|0.64435|0.00070|0.11%|0.64077|-5.10%|0.64060|-5.12%|3.127|8.614|0.000|25.84 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59037|0.59494|0.00101|0.17%|0.59242|0.00%|0.59232|0.00%|0.545|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e0113cd1d6)|0.58865|0.59199|0.00086|0.15%|0.58966|-0.47%|0.58936|-0.50%|1.895|8.035|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f0aa11d23)|0.58725|0.59095|0.00101|0.17%|0.58805|-0.74%|0.58769|-0.78%|1.911|8.566|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f0aa11d23)|0.51966|0.52415|0.00104|0.20%|0.52070|-12.11%|0.52034|-12.15%|2.404|8.614|0.000|26.30 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44303|0.44536|0.00056|0.13%|0.44443|0.00%|0.44449|0.00%|-0.401|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e0113cd1d6)|0.44926|0.45356|0.00071|0.16%|0.45066|1.40%|0.45071|1.40%|1.090|-8.614|0.000|25.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f0aa11d23)|0.44897|0.45166|0.00061|0.14%|0.45025|1.31%|0.45014|1.27%|0.114|-8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f0aa11d23)|0.14429|0.14527|0.00021|0.14%|0.14469|-67.44%|0.14468|-67.45%|0.280|8.614|0.000|26.30 MB|
