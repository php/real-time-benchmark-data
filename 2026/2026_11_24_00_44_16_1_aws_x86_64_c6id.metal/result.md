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
| Time          |2026-11-24 00:44:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/45299465070 ([Artifacts](https://github.com/php/php-src/actions/runs/45299465070/artifacts/14880780291))|
| Changeset  |https://github.com/php/php-src/compare/96493f5d6f..8904d87f04|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39360|0.39649|0.00082|0.21%|0.39452|0.00%|0.39414|0.00%|0.719|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96493f5d6f)|0.37567|0.37693|0.00027|0.07%|0.37615|-4.66%|0.37610|-4.58%|0.771|8.614|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/8904d87f04)|0.37544|0.37660|0.00022|0.06%|0.37581|-4.74%|0.37578|-4.66%|1.248|8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8904d87f04)|0.34786|0.34890|0.00019|0.05%|0.34840|-11.69%|0.34841|-11.60%|-0.113|8.614|0.000|26.32 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67253|0.68224|0.00172|0.26%|0.67352|0.00%|0.67299|0.00%|4.039|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96493f5d6f)|0.67694|0.68003|0.00056|0.08%|0.67826|0.70%|0.67825|0.78%|0.443|-7.924|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/8904d87f04)|0.67771|0.68252|0.00095|0.14%|0.67955|0.90%|0.67942|0.96%|0.944|-7.993|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8904d87f04)|0.65063|0.65956|0.00126|0.19%|0.65155|-3.26%|0.65133|-3.22%|5.372|8.614|0.000|26.35 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58645|0.59057|0.00091|0.16%|0.58832|0.00%|0.58820|0.00%|0.116|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96493f5d6f)|0.58436|0.59014|0.00084|0.14%|0.58513|-0.54%|0.58495|-0.55%|4.549|8.269|0.000|26.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/8904d87f04)|0.58524|0.58857|0.00059|0.10%|0.58595|-0.40%|0.58578|-0.41%|2.938|8.207|0.000|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8904d87f04)|0.51093|0.51326|0.00057|0.11%|0.51165|-13.03%|0.51149|-13.04%|1.243|8.614|0.000|26.43 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44361|0.44568|0.00050|0.11%|0.44452|0.00%|0.44453|0.00%|0.148|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/96493f5d6f)|0.45308|0.45541|0.00054|0.12%|0.45447|2.24%|0.45452|2.25%|-0.420|-8.614|0.000|26.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/8904d87f04)|0.45339|0.45521|0.00049|0.11%|0.45432|2.20%|0.45433|2.20%|-0.135|-8.614|0.000|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8904d87f04)|0.14655|0.16427|0.00247|1.67%|0.14783|-66.74%|0.14733|-66.86%|6.235|8.614|0.000|26.43 MB|
