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
| Time          |2026-11-28 00:45:58 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/46089582787 ([Artifacts](https://github.com/php/php-src/actions/runs/46089582787/artifacts/15241977707))|
| Changeset  |https://github.com/php/php-src/compare/8ea2d41052..98fae34958|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39727|0.39959|0.00063|0.16%|0.39795|0.00%|0.39773|0.00%|1.608|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ea2d41052)|0.38171|0.38523|0.00049|0.13%|0.38218|-3.96%|0.38209|-3.93%|5.128|8.614|0.000|25.90 MB|
|[PHP - master](https://github.com/php/php-src/commit/98fae34958)|0.38168|0.38329|0.00028|0.07%|0.38222|-3.95%|0.38217|-3.91%|1.868|8.614|0.000|25.91 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/98fae34958)|0.35227|0.35355|0.00028|0.08%|0.35285|-11.33%|0.35282|-11.29%|0.355|8.614|0.000|26.34 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67639|0.68216|0.00094|0.14%|0.67742|0.00%|0.67721|0.00%|2.970|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ea2d41052)|0.67969|0.68783|0.00160|0.24%|0.68100|0.53%|0.68039|0.47%|2.682|-8.317|0.000|26.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/98fae34958)|0.68528|0.69281|0.00114|0.17%|0.68652|1.34%|0.68639|1.36%|3.780|-8.614|0.000|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/98fae34958)|0.65431|0.65705|0.00047|0.07%|0.65537|-3.26%|0.65533|-3.23%|1.126|8.614|0.000|26.34 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59159|0.59577|0.00092|0.15%|0.59309|0.00%|0.59290|0.00%|0.754|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ea2d41052)|0.59248|0.59533|0.00043|0.07%|0.59327|0.03%|0.59327|0.06%|2.243|-1.858|0.063|26.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/98fae34958)|0.59063|0.59319|0.00059|0.10%|0.59123|-0.31%|0.59108|-0.31%|2.031|7.924|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/98fae34958)|0.51901|0.52186|0.00054|0.10%|0.51982|-12.35%|0.51975|-12.34%|1.717|8.614|0.000|26.42 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44328|0.44609|0.00069|0.16%|0.44463|0.00%|0.44455|0.00%|0.356|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8ea2d41052)|0.45642|0.45849|0.00060|0.13%|0.45741|2.87%|0.45739|2.89%|0.105|-8.614|0.000|26.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/98fae34958)|0.45623|0.46050|0.00070|0.15%|0.45762|2.92%|0.45754|2.92%|1.289|-8.614|0.000|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/98fae34958)|0.14807|0.15273|0.00104|0.70%|0.14894|-66.50%|0.14863|-66.57%|3.062|8.614|0.000|26.42 MB|
