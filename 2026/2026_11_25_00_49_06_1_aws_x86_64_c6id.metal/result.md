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
| Time          |2026-11-25 00:49:06 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/45520936622 ([Artifacts](https://github.com/php/php-src/actions/runs/45520936622/artifacts/14982500689))|
| Changeset  |https://github.com/php/php-src/compare/8904d87f04..a37b948c2a|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39728|0.39958|0.00042|0.10%|0.39787|0.00%|0.39777|0.00%|2.786|0.000|1.000|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8904d87f04)|0.37910|0.37994|0.00019|0.05%|0.37946|-4.63%|0.37945|-4.60%|0.306|8.614|0.000|25.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/a37b948c2a)|0.37761|0.37949|0.00036|0.10%|0.37801|-4.99%|0.37789|-5.00%|2.153|8.614|0.000|25.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a37b948c2a)|0.35201|0.35348|0.00026|0.07%|0.35254|-11.39%|0.35251|-11.38%|0.901|8.614|0.000|26.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67689|0.69316|0.00290|0.43%|0.67845|0.00%|0.67758|0.00%|3.925|0.000|1.000|26.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8904d87f04)|0.68235|0.69115|0.00141|0.21%|0.68429|0.86%|0.68403|0.95%|3.342|-7.607|0.000|26.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/a37b948c2a)|0.68195|0.68479|0.00050|0.07%|0.68329|0.71%|0.68324|0.83%|0.433|-7.580|0.000|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a37b948c2a)|0.65097|0.65601|0.00076|0.12%|0.65209|-3.88%|0.65200|-3.78%|2.899|8.614|0.000|26.36 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59098|0.59410|0.00071|0.12%|0.59221|0.00%|0.59222|0.00%|0.559|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8904d87f04)|0.58916|0.59204|0.00075|0.13%|0.58995|-0.38%|0.58972|-0.42%|1.473|8.097|0.000|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/a37b948c2a)|0.58666|0.58919|0.00057|0.10%|0.58725|-0.84%|0.58709|-0.87%|2.373|8.614|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a37b948c2a)|0.51461|0.51681|0.00042|0.08%|0.51528|-12.99%|0.51520|-13.01%|1.645|8.614|0.000|26.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44346|0.44686|0.00072|0.16%|0.44462|0.00%|0.44448|0.00%|0.714|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8904d87f04)|0.45229|0.45867|0.00094|0.21%|0.45444|2.21%|0.45430|2.21%|1.668|-8.614|0.000|26.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/a37b948c2a)|0.45431|0.45697|0.00063|0.14%|0.45570|2.49%|0.45573|2.53%|-0.226|-8.614|0.000|26.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a37b948c2a)|0.14810|0.16494|0.00334|2.23%|0.14958|-66.36%|0.14857|-66.57%|4.065|8.614|0.000|26.35 MB|
