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
| Time          |2026-02-16 00:56:29 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22046507985 ([Artifacts](https://github.com/php/php-src/actions/runs/22046507985/artifacts/5519758869))|
| Changeset  |https://github.com/php/php-src/compare/4fbe41116b..0375697dab|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39634|0.39851|0.00034|0.08%|0.39682|0.00%|0.39676|0.00%|2.890|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4fbe41116b)|0.39040|0.39384|0.00074|0.19%|0.39104|-1.46%|0.39072|-1.52%|2.139|8.614|0.000|25.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/0375697dab)|0.39032|0.39308|0.00057|0.15%|0.39086|-1.50%|0.39071|-1.52%|2.631|8.614|0.000|25.21 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0375697dab)|0.36220|0.36457|0.00047|0.13%|0.36271|-8.59%|0.36257|-8.62%|2.259|8.614|0.000|25.32 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66963|0.67306|0.00070|0.10%|0.67044|0.00%|0.67017|0.00%|1.661|0.000|1.000|26.72 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4fbe41116b)|0.67097|0.67279|0.00045|0.07%|0.67176|0.20%|0.67168|0.23%|0.574|-7.566|0.000|25.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/0375697dab)|0.67081|0.67238|0.00036|0.05%|0.67171|0.19%|0.67174|0.23%|-0.219|-7.463|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0375697dab)|0.63627|0.64653|0.00160|0.25%|0.63725|-4.95%|0.63687|-4.97%|4.770|8.614|0.000|25.35 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58988|0.59424|0.00099|0.17%|0.59154|0.00%|0.59148|0.00%|0.557|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4fbe41116b)|0.58701|0.59061|0.00054|0.09%|0.58764|-0.66%|0.58756|-0.66%|3.624|8.552|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/0375697dab)|0.58694|0.59046|0.00082|0.14%|0.58808|-0.59%|0.58783|-0.62%|1.651|8.497|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0375697dab)|0.51936|0.53010|0.00169|0.32%|0.52045|-12.02%|0.52005|-12.08%|4.239|8.614|0.000|25.38 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44155|0.44418|0.00067|0.15%|0.44288|0.00%|0.44289|0.00%|-0.051|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/4fbe41116b)|0.44529|0.44789|0.00059|0.13%|0.44658|0.84%|0.44656|0.83%|-0.042|-8.614|0.000|25.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/0375697dab)|0.44530|0.44764|0.00052|0.12%|0.44640|0.79%|0.44635|0.78%|0.127|-8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0375697dab)|0.14344|0.14437|0.00021|0.15%|0.14388|-67.51%|0.14387|-67.51%|0.179|8.614|0.000|25.38 MB|
