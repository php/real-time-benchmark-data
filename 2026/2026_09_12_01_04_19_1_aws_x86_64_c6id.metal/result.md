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
| Time          |2026-09-12 01:04:19 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/34663668846 ([Artifacts](https://github.com/php/php-src/actions/runs/34663668846/artifacts/10288559218))|
| Changeset  |https://github.com/php/php-src/compare/ac53f14223..8b1668d842|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39898|0.40087|0.00028|0.07%|0.39946|0.00%|0.39946|0.00%|2.398|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac53f14223)|0.37460|0.37686|0.00034|0.09%|0.37512|-6.09%|0.37511|-6.10%|2.945|8.614|0.000|25.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b1668d842)|0.37572|0.37740|0.00032|0.09%|0.37625|-5.81%|0.37621|-5.82%|1.664|8.614|0.000|25.85 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.68021|0.69033|0.00145|0.21%|0.68206|0.00%|0.68175|0.00%|4.043|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac53f14223)|0.66844|0.67013|0.00038|0.06%|0.66893|-1.92%|0.66884|-1.89%|1.355|8.614|0.000|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b1668d842)|0.67209|0.67983|0.00114|0.17%|0.67354|-1.25%|0.67335|-1.23%|3.612|8.614|0.000|26.31 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59045|0.59598|0.00115|0.19%|0.59209|0.00%|0.59203|0.00%|1.346|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac53f14223)|0.59163|0.59920|0.00147|0.25%|0.59292|0.14%|0.59244|0.07%|3.119|-3.905|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b1668d842)|0.59224|0.59607|0.00084|0.14%|0.59339|0.22%|0.59330|0.22%|1.306|-6.301|0.000|26.23 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44342|0.44662|0.00060|0.13%|0.44476|0.00%|0.44473|0.00%|0.499|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ac53f14223)|0.44992|0.45308|0.00056|0.12%|0.45117|1.44%|0.45119|1.45%|0.386|-8.614|0.000|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/8b1668d842)|0.45019|0.45331|0.00056|0.12%|0.45139|1.49%|0.45126|1.47%|0.697|-8.614|0.000|26.23 MB|
