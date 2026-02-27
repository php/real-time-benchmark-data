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
| Time          |2026-02-27 00:54:30 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22467940564 ([Artifacts](https://github.com/php/php-src/actions/runs/22467940564/artifacts/5683502867))|
| Changeset  |https://github.com/php/php-src/compare/031b4c66c4..f46bc8e3a7|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39974|0.40299|0.00057|0.14%|0.40025|0.00%|0.40009|0.00%|3.140|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/031b4c66c4)|0.39461|0.39654|0.00034|0.09%|0.39519|-1.26%|0.39510|-1.25%|2.211|8.614|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/f46bc8e3a7)|0.39499|0.39645|0.00028|0.07%|0.39543|-1.20%|0.39538|-1.18%|1.860|8.614|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f46bc8e3a7)|0.36804|0.36909|0.00025|0.07%|0.36838|-7.96%|0.36834|-7.94%|1.166|8.614|0.000|25.38 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67361|0.67536|0.00051|0.08%|0.67417|0.00%|0.67395|0.00%|1.130|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/031b4c66c4)|0.66852|0.67196|0.00070|0.11%|0.67019|-0.59%|0.67009|-0.57%|0.183|8.614|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/f46bc8e3a7)|0.66821|0.67139|0.00050|0.07%|0.66892|-0.78%|0.66884|-0.76%|2.587|8.614|0.000|25.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f46bc8e3a7)|0.63622|0.64482|0.00131|0.21%|0.63705|-5.51%|0.63678|-5.52%|4.677|8.614|0.000|25.36 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59288|0.59723|0.00105|0.18%|0.59474|0.00%|0.59477|0.00%|0.082|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/031b4c66c4)|0.59228|0.59603|0.00073|0.12%|0.59317|-0.26%|0.59295|-0.31%|2.763|6.849|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/f46bc8e3a7)|0.59160|0.59469|0.00050|0.08%|0.59227|-0.42%|0.59216|-0.44%|2.612|8.345|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f46bc8e3a7)|0.52277|0.52659|0.00052|0.10%|0.52339|-12.00%|0.52337|-12.00%|4.722|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44197|0.44382|0.00047|0.10%|0.44303|0.00%|0.44308|0.00%|-0.324|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/031b4c66c4)|0.44447|0.44749|0.00054|0.12%|0.44570|0.60%|0.44564|0.58%|0.680|-8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/f46bc8e3a7)|0.44445|0.44929|0.00071|0.16%|0.44584|0.63%|0.44576|0.60%|2.307|-8.614|0.000|25.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f46bc8e3a7)|0.14342|0.14540|0.00028|0.20%|0.14402|-67.49%|0.14401|-67.50%|2.166|8.614|0.000|25.39 MB|
