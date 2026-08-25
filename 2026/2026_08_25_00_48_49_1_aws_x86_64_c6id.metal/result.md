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
| Time          |2026-08-25 00:48:49 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/32795091036 ([Artifacts](https://github.com/php/php-src/actions/runs/32795091036/artifacts/9545172672))|
| Changeset  |https://github.com/php/php-src/compare/c96900ee74..75ad0885c9|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39608|0.39692|0.00019|0.05%|0.39650|0.00%|0.39657|0.00%|-0.361|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c96900ee74)|0.37052|0.37208|0.00025|0.07%|0.37098|-6.44%|0.37094|-6.46%|1.947|8.614|0.000|25.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/75ad0885c9)|0.37029|0.37383|0.00060|0.16%|0.37083|-6.47%|0.37066|-6.53%|3.554|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67617|0.68173|0.00094|0.14%|0.67749|0.00%|0.67737|0.00%|2.032|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c96900ee74)|0.66937|0.67118|0.00037|0.05%|0.66993|-1.12%|0.66986|-1.11%|0.974|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/75ad0885c9)|0.66918|0.67127|0.00049|0.07%|0.66990|-1.12%|0.66977|-1.12%|0.922|8.614|0.000|26.15 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58764|0.59374|0.00107|0.18%|0.58930|0.00%|0.58907|0.00%|1.604|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c96900ee74)|0.58704|0.59372|0.00123|0.21%|0.58864|-0.11%|0.58839|-0.11%|2.248|3.898|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/75ad0885c9)|0.58611|0.58959|0.00067|0.11%|0.58706|-0.38%|0.58693|-0.36%|1.565|8.097|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44313|0.44568|0.00052|0.12%|0.44460|0.00%|0.44456|0.00%|-0.597|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c96900ee74)|0.45073|0.45704|0.00096|0.21%|0.45215|1.70%|0.45209|1.70%|2.658|-8.614|0.000|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/75ad0885c9)|0.45090|0.45529|0.00087|0.19%|0.45215|1.70%|0.45204|1.68%|1.741|-8.614|0.000|26.19 MB|
