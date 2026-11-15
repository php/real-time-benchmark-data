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
| Time          |2026-11-15 00:49:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/43660022312 ([Artifacts](https://github.com/php/php-src/actions/runs/43660022312/artifacts/14140469066))|
| Changeset  |https://github.com/php/php-src/compare/4aba862339..39ee018ae2|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39754|0.39959|0.00029|0.07%|0.39798|0.00%|0.39794|0.00%|3.622|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4aba862339)|0.37904|0.38105|0.00032|0.09%|0.37937|-4.68%|0.37931|-4.68%|3.442|8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ee018ae2)|0.37890|0.38053|0.00034|0.09%|0.37950|-4.64%|0.37941|-4.66%|1.415|8.614|0.000|26.22 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ee018ae2)|0.35294|0.35417|0.00026|0.07%|0.35332|-11.22%|0.35324|-11.23%|1.453|8.614|0.000|26.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67768|0.71309|0.00749|1.10%|0.68116|0.00%|0.67841|0.00%|2.888|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4aba862339)|0.67666|0.67892|0.00053|0.08%|0.67728|-0.57%|0.67710|-0.19%|1.703|7.580|0.000|26.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ee018ae2)|0.68073|0.68816|0.00120|0.18%|0.68157|0.06%|0.68131|0.43%|4.669|-5.905|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ee018ae2)|0.64935|0.65105|0.00034|0.05%|0.65001|-4.57%|0.64998|-4.19%|0.581|8.614|0.000|26.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59090|0.59593|0.00096|0.16%|0.59249|0.00%|0.59246|0.00%|0.896|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4aba862339)|0.58809|0.59155|0.00072|0.12%|0.58897|-0.59%|0.58880|-0.62%|1.766|8.566|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ee018ae2)|0.58911|0.59201|0.00050|0.09%|0.58987|-0.44%|0.58978|-0.45%|2.990|8.379|0.000|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ee018ae2)|0.51597|0.52000|0.00084|0.16%|0.51679|-12.78%|0.51659|-12.81%|2.449|8.614|0.000|26.37 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44308|0.45235|0.00143|0.32%|0.44490|0.00%|0.44474|0.00%|3.373|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4aba862339)|0.45286|0.45559|0.00055|0.12%|0.45433|2.12%|0.45431|2.15%|0.131|-8.614|0.000|26.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ee018ae2)|0.45254|0.45563|0.00076|0.17%|0.45414|2.08%|0.45418|2.12%|-0.072|-8.614|0.000|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ee018ae2)|0.14498|0.14941|0.00094|0.65%|0.14587|-67.21%|0.14562|-67.26%|2.907|8.614|0.000|26.37 MB|
