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
| Time          |2026-11-23 00:51:04 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/45091118575 ([Artifacts](https://github.com/php/php-src/actions/runs/45091118575/artifacts/14782797949))|
| Changeset  |https://github.com/php/php-src/compare/6e4c78a172..96493f5d6f|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39733|0.39883|0.00027|0.07%|0.39776|0.00%|0.39771|0.00%|1.858|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e4c78a172)|0.37943|0.38140|0.00038|0.10%|0.37988|-4.50%|0.37976|-4.51%|1.838|8.614|0.000|25.81 MB|
|[PHP - master](https://github.com/php/php-src/commit/96493f5d6f)|0.37942|0.38057|0.00019|0.05%|0.37974|-4.53%|0.37973|-4.52%|1.818|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96493f5d6f)|0.35477|0.35582|0.00025|0.07%|0.35523|-10.69%|0.35521|-10.69%|0.421|8.614|0.000|26.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67688|0.68504|0.00129|0.19%|0.67792|0.00%|0.67759|0.00%|3.797|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e4c78a172)|0.67861|0.68624|0.00120|0.18%|0.67941|0.22%|0.67907|0.22%|4.385|-7.504|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/96493f5d6f)|0.68214|0.68651|0.00080|0.12%|0.68348|0.82%|0.68336|0.85%|1.243|-8.276|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96493f5d6f)|0.65227|0.65774|0.00079|0.12%|0.65326|-3.64%|0.65306|-3.62%|3.929|8.614|0.000|26.36 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59093|0.59349|0.00077|0.13%|0.59229|0.00%|0.59245|0.00%|-0.107|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e4c78a172)|0.58972|0.59253|0.00062|0.10%|0.59051|-0.30%|0.59029|-0.37%|1.651|7.873|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/96493f5d6f)|0.58820|0.59199|0.00089|0.15%|0.58940|-0.49%|0.58916|-0.56%|0.905|8.386|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96493f5d6f)|0.51715|0.51945|0.00051|0.10%|0.51773|-12.59%|0.51758|-12.64%|1.947|8.614|0.000|26.42 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44351|0.44901|0.00083|0.19%|0.44457|0.00%|0.44443|0.00%|3.266|0.000|1.000|26.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6e4c78a172)|0.45218|0.45532|0.00061|0.13%|0.45377|2.07%|0.45371|2.09%|0.217|-8.614|0.000|26.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/96493f5d6f)|0.45287|0.45581|0.00070|0.15%|0.45450|2.23%|0.45450|2.27%|-0.056|-8.614|0.000|26.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/96493f5d6f)|0.14687|0.14965|0.00063|0.43%|0.14763|-66.79%|0.14750|-66.81%|2.169|8.614|0.000|26.43 MB|
