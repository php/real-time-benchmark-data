### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-06-17 01:35:47 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/27659816755 ([Artifacts](https://github.com/php/php-src/actions/runs/27659816755/artifacts/7684621864))|
| Changeset  |https://github.com/php/php-src/compare/dee1317c33..cbc089a29e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39458|0.39565|0.00020|0.05%|0.39493|0.00%|0.39490|0.00%|1.085|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dee1317c33)|0.38599|0.38770|0.00039|0.10%|0.38643|-2.15%|0.38628|-2.18%|1.660|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/cbc089a29e)|0.38814|0.39141|0.00052|0.13%|0.38865|-1.59%|0.38856|-1.61%|3.665|8.614|0.000|25.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cbc089a29e)|0.35974|0.36113|0.00033|0.09%|0.36033|-8.76%|0.36028|-8.77%|0.610|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67245|0.67555|0.00064|0.10%|0.67312|0.00%|0.67288|0.00%|1.704|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dee1317c33)|0.66473|0.66951|0.00098|0.15%|0.66561|-1.12%|0.66536|-1.12%|2.784|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/cbc089a29e)|0.66528|0.66825|0.00066|0.10%|0.66599|-1.06%|0.66580|-1.05%|1.808|8.614|0.000|25.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cbc089a29e)|0.63603|0.63798|0.00047|0.07%|0.63660|-5.43%|0.63647|-5.41%|1.341|8.614|0.000|26.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58896|0.59278|0.00105|0.18%|0.59062|0.00%|0.59052|0.00%|0.367|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dee1317c33)|0.58602|0.58781|0.00049|0.08%|0.58662|-0.68%|0.58647|-0.69%|0.947|8.614|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/cbc089a29e)|0.58613|0.58992|0.00076|0.13%|0.58692|-0.63%|0.58667|-0.65%|2.397|8.469|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cbc089a29e)|0.51759|0.52238|0.00092|0.18%|0.51838|-12.23%|0.51808|-12.27%|2.814|8.614|0.000|26.24 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44336|0.45162|0.00121|0.27%|0.44460|0.00%|0.44460|0.00%|4.136|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/dee1317c33)|0.44832|0.45085|0.00054|0.12%|0.44963|1.13%|0.44955|1.11%|0.087|-8.269|0.000|25.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/cbc089a29e)|0.44911|0.45144|0.00056|0.12%|0.45032|1.29%|0.45027|1.28%|-0.310|-8.269|0.000|25.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cbc089a29e)|0.14390|0.14493|0.00017|0.12%|0.14463|-67.47%|0.14465|-67.46%|-1.315|8.614|0.000|26.24 MB|
