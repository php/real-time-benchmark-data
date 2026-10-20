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
| Time          |2026-10-20 01:05:59 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/39351491807 ([Artifacts](https://github.com/php/php-src/actions/runs/39351491807/artifacts/12233869636))|
| Changeset  |https://github.com/php/php-src/compare/b7256eee30..a17dcadd4c|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39920|0.40100|0.00032|0.08%|0.39964|0.00%|0.39957|0.00%|1.949|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b7256eee30)|0.37701|0.37893|0.00038|0.10%|0.37763|-5.51%|0.37753|-5.52%|1.796|8.614|0.000|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/a17dcadd4c)|0.37989|0.38144|0.00031|0.08%|0.38039|-4.82%|0.38031|-4.82%|1.892|8.614|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a17dcadd4c)|0.35389|0.35549|0.00036|0.10%|0.35447|-11.30%|0.35433|-11.32%|0.860|8.614|0.000|26.20 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68125|0.68513|0.00076|0.11%|0.68290|0.00%|0.68284|0.00%|0.411|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b7256eee30)|0.67352|0.68526|0.00202|0.30%|0.67470|-1.20%|0.67423|-1.26%|4.382|8.097|0.000|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/a17dcadd4c)|0.67927|0.68564|0.00123|0.18%|0.68062|-0.33%|0.68030|-0.37%|2.392|7.428|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a17dcadd4c)|0.64599|0.64862|0.00049|0.08%|0.64685|-5.28%|0.64681|-5.28%|0.874|8.614|0.000|26.24 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59096|0.59486|0.00098|0.17%|0.59254|0.00%|0.59232|0.00%|0.508|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b7256eee30)|0.59034|0.59393|0.00087|0.15%|0.59129|-0.21%|0.59111|-0.20%|1.496|6.153|0.000|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/a17dcadd4c)|0.59122|0.59577|0.00085|0.14%|0.59206|-0.08%|0.59183|-0.08%|3.040|2.878|0.004|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a17dcadd4c)|0.51927|0.52290|0.00093|0.18%|0.52028|-12.20%|0.51996|-12.22%|1.858|8.614|0.000|26.37 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44369|0.44562|0.00052|0.12%|0.44468|0.00%|0.44473|0.00%|-0.102|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b7256eee30)|0.45301|0.45565|0.00062|0.14%|0.45411|2.12%|0.45410|2.11%|0.246|-8.614|0.000|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/a17dcadd4c)|0.45202|0.45585|0.00066|0.15%|0.45306|1.89%|0.45296|1.85%|1.427|-8.614|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a17dcadd4c)|0.14390|0.14499|0.00023|0.16%|0.14445|-67.52%|0.14443|-67.52%|-0.167|8.614|0.000|26.37 MB|
