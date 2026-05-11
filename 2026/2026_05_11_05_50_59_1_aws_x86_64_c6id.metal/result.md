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
| Time          |2026-05-11 05:50:59 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25645335302 ([Artifacts](https://github.com/php/php-src/actions/runs/25645335302/artifacts/6911871964))|
| Changeset  |https://github.com/php/php-src/compare/fe52e5b64b..eb3204252e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39354|0.39470|0.00018|0.05%|0.39393|0.00%|0.39391|0.00%|1.583|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe52e5b64b)|0.38708|0.39026|0.00077|0.20%|0.38884|-1.29%|0.38907|-1.23%|-1.065|8.614|0.000|25.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/eb3204252e)|0.38667|0.38930|0.00046|0.12%|0.38713|-1.73%|0.38701|-1.75%|3.299|8.614|0.000|25.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eb3204252e)|0.35722|0.36009|0.00050|0.14%|0.35820|-9.07%|0.35810|-9.09%|1.779|8.614|0.000|25.52 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67242|0.67637|0.00069|0.10%|0.67345|0.00%|0.67330|0.00%|1.798|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe52e5b64b)|0.66698|0.67058|0.00064|0.10%|0.66771|-0.85%|0.66748|-0.86%|2.277|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/eb3204252e)|0.66529|0.66812|0.00056|0.08%|0.66624|-1.07%|0.66610|-1.07%|1.552|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eb3204252e)|0.63274|0.64703|0.00268|0.42%|0.63400|-5.86%|0.63329|-5.94%|3.910|8.614|0.000|25.38 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58771|0.59213|0.00098|0.17%|0.58935|0.00%|0.58928|0.00%|0.641|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe52e5b64b)|0.58398|0.58819|0.00066|0.11%|0.58478|-0.78%|0.58466|-0.78%|3.073|8.572|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/eb3204252e)|0.58442|0.58763|0.00059|0.10%|0.58523|-0.70%|0.58517|-0.70%|1.694|8.614|0.000|25.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eb3204252e)|0.51524|0.51849|0.00058|0.11%|0.51595|-12.45%|0.51584|-12.46%|2.411|8.614|0.000|25.41 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44107|0.44430|0.00065|0.15%|0.44283|0.00%|0.44284|0.00%|0.097|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fe52e5b64b)|0.44528|0.44747|0.00053|0.12%|0.44667|0.87%|0.44674|0.88%|-0.795|-8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/eb3204252e)|0.44711|0.44996|0.00060|0.13%|0.44856|1.29%|0.44847|1.27%|0.280|-8.614|0.000|25.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/eb3204252e)|0.14361|0.14546|0.00032|0.22%|0.14410|-67.46%|0.14406|-67.47%|2.461|8.614|0.000|25.41 MB|
