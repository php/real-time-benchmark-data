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
| Time          |2026-11-20 00:46:18 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/44648361290 ([Artifacts](https://github.com/php/php-src/actions/runs/44648361290/artifacts/14592390348))|
| Changeset  |https://github.com/php/php-src/compare/e709ba4099..92e1542d27|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39741|0.39850|0.00021|0.05%|0.39774|0.00%|0.39772|0.00%|1.267|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e709ba4099)|0.37860|0.38023|0.00039|0.10%|0.37902|-4.71%|0.37885|-4.75%|1.808|8.614|0.000|25.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/92e1542d27)|0.37907|0.38014|0.00024|0.06%|0.37942|-4.61%|0.37939|-4.61%|1.332|8.614|0.000|26.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92e1542d27)|0.35527|0.35620|0.00022|0.06%|0.35567|-10.58%|0.35562|-10.59%|0.761|8.614|0.000|26.34 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67643|0.68485|0.00140|0.21%|0.67737|0.00%|0.67690|0.00%|3.862|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e709ba4099)|0.68251|0.68860|0.00113|0.17%|0.68349|0.90%|0.68321|0.93%|2.957|-8.283|0.000|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/92e1542d27)|0.68082|0.68633|0.00081|0.12%|0.68154|0.62%|0.68138|0.66%|4.452|-8.242|0.000|26.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92e1542d27)|0.65052|0.65199|0.00034|0.05%|0.65104|-3.89%|0.65098|-3.83%|1.120|8.614|0.000|26.36 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59034|0.59445|0.00087|0.15%|0.59238|0.00%|0.59224|0.00%|0.174|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e709ba4099)|0.58716|0.58982|0.00062|0.10%|0.58801|-0.74%|0.58788|-0.74%|1.738|8.614|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/92e1542d27)|0.58966|0.59241|0.00054|0.09%|0.59023|-0.36%|0.59009|-0.36%|2.694|8.159|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92e1542d27)|0.51719|0.51991|0.00057|0.11%|0.51783|-12.58%|0.51774|-12.58%|2.293|8.614|0.000|26.48 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44321|0.44792|0.00082|0.18%|0.44479|0.00%|0.44464|0.00%|1.047|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e709ba4099)|0.45276|0.45606|0.00070|0.15%|0.45396|2.06%|0.45391|2.08%|0.609|-8.614|0.000|26.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/92e1542d27)|0.45182|0.45592|0.00073|0.16%|0.45398|2.07%|0.45402|2.11%|-0.228|-8.614|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/92e1542d27)|0.14512|0.15417|0.00162|1.11%|0.14623|-67.12%|0.14572|-67.23%|3.114|8.614|0.000|26.48 MB|
