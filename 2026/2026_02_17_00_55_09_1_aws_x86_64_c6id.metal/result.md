### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.12.66-88.122.amzn2023.x86_64|
| OS            |Amazon Linux 2023.10.20260202|
| GCC           |14.2.1|
| Time          |2026-02-17 00:55:09 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22082147787 ([Artifacts](https://github.com/php/php-src/actions/runs/22082147787/artifacts/5532873566))|
| Changeset  |https://github.com/php/php-src/compare/0375697dab..115ea486ac|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39526|0.39735|0.00063|0.16%|0.39591|0.00%|0.39564|0.00%|1.365|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0375697dab)|0.38930|0.39049|0.00029|0.07%|0.38965|-1.58%|0.38955|-1.54%|1.421|8.614|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/115ea486ac)|0.38966|0.39304|0.00068|0.17%|0.39049|-1.37%|0.39022|-1.37%|1.832|8.614|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/115ea486ac)|0.36351|0.36607|0.00047|0.13%|0.36418|-8.01%|0.36407|-7.98%|2.248|8.614|0.000|25.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66899|0.67213|0.00061|0.09%|0.66971|0.00%|0.66959|0.00%|1.664|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0375697dab)|0.67006|0.67166|0.00041|0.06%|0.67078|0.16%|0.67074|0.17%|0.339|-7.297|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/115ea486ac)|0.66544|0.66742|0.00042|0.06%|0.66603|-0.55%|0.66597|-0.54%|1.747|8.614|0.000|25.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/115ea486ac)|0.63436|0.63851|0.00079|0.13%|0.63495|-5.19%|0.63477|-5.20%|3.781|8.614|0.000|25.30 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58798|0.59397|0.00119|0.20%|0.59068|0.00%|0.59065|0.00%|0.161|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0375697dab)|0.58583|0.58959|0.00062|0.11%|0.58664|-0.68%|0.58649|-0.70%|3.341|8.538|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/115ea486ac)|0.58666|0.59397|0.00110|0.19%|0.58771|-0.50%|0.58742|-0.55%|4.149|8.059|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/115ea486ac)|0.51700|0.52063|0.00089|0.17%|0.51783|-12.33%|0.51758|-12.37%|2.169|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44114|0.44658|0.00085|0.19%|0.44281|0.00%|0.44279|0.00%|1.727|0.000|1.000|26.77 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0375697dab)|0.44529|0.44799|0.00058|0.13%|0.44653|0.84%|0.44646|0.83%|0.215|-8.414|0.000|25.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/115ea486ac)|0.44300|0.44654|0.00069|0.15%|0.44512|0.52%|0.44514|0.53%|-0.616|-8.104|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/115ea486ac)|0.14326|0.14465|0.00028|0.20%|0.14389|-67.50%|0.14384|-67.51%|0.981|8.614|0.000|25.44 MB|
