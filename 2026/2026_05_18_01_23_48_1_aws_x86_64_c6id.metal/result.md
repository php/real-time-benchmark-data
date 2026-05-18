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
| Time          |2026-05-18 01:23:48 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26008553189 ([Artifacts](https://github.com/php/php-src/actions/runs/26008553189/artifacts/7048372817))|
| Changeset  |https://github.com/php/php-src/compare/51911cc1c6..7827754207|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39470|0.39645|0.00031|0.08%|0.39523|0.00%|0.39517|0.00%|2.014|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51911cc1c6)|0.38683|0.38887|0.00035|0.09%|0.38744|-1.97%|0.38734|-1.98%|1.588|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/7827754207)|0.38687|0.38916|0.00055|0.14%|0.38755|-1.94%|0.38736|-1.98%|1.704|8.614|0.000|25.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7827754207)|0.35903|0.36214|0.00048|0.13%|0.35959|-9.02%|0.35946|-9.04%|3.460|8.614|0.000|25.51 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67360|0.67630|0.00062|0.09%|0.67438|0.00%|0.67429|0.00%|1.074|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51911cc1c6)|0.66844|0.67034|0.00044|0.07%|0.66890|-0.81%|0.66878|-0.82%|1.410|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/7827754207)|0.66809|0.66943|0.00036|0.05%|0.66865|-0.85%|0.66852|-0.85%|0.534|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7827754207)|0.63541|0.66411|0.00425|0.67%|0.63700|-5.54%|0.63594|-5.69%|5.671|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58770|0.59324|0.00097|0.16%|0.58989|0.00%|0.58988|0.00%|0.559|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51911cc1c6)|0.58487|0.58721|0.00048|0.08%|0.58559|-0.73%|0.58553|-0.74%|1.917|8.614|0.000|25.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/7827754207)|0.58504|0.58756|0.00054|0.09%|0.58565|-0.72%|0.58551|-0.74%|1.828|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7827754207)|0.51569|0.51933|0.00072|0.14%|0.51650|-12.44%|0.51632|-12.47%|2.248|8.614|0.000|25.83 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44175|0.44957|0.00132|0.30%|0.44318|0.00%|0.44298|0.00%|3.212|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/51911cc1c6)|0.44623|0.45008|0.00067|0.15%|0.44736|0.94%|0.44728|0.97%|1.710|-8.021|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/7827754207)|0.44655|0.45006|0.00057|0.13%|0.44731|0.93%|0.44725|0.96%|2.398|-8.014|0.000|25.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/7827754207)|0.14350|0.14565|0.00031|0.22%|0.14383|-67.55%|0.14379|-67.54%|4.327|8.614|0.000|25.85 MB|
