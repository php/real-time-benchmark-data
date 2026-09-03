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
| Time          |2026-09-03 01:08:18 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/33702401542 ([Artifacts](https://github.com/php/php-src/actions/runs/33702401542/artifacts/9874673931))|
| Changeset  |https://github.com/php/php-src/compare/759829bc2f..ce7896d514|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39604|0.39706|0.00021|0.05%|0.39629|0.00%|0.39625|0.00%|1.406|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/759829bc2f)|0.36968|0.37079|0.00023|0.06%|0.37023|-6.58%|0.37020|-6.58%|0.482|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/ce7896d514)|0.37009|0.37098|0.00018|0.05%|0.37041|-6.53%|0.37038|-6.53%|0.671|8.614|0.000|25.83 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67513|0.67895|0.00082|0.12%|0.67698|0.00%|0.67687|0.00%|0.383|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/759829bc2f)|0.66790|0.67214|0.00070|0.10%|0.66859|-1.24%|0.66840|-1.25%|2.998|8.614|0.000|25.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/ce7896d514)|0.66757|0.67055|0.00060|0.09%|0.66825|-1.29%|0.66810|-1.30%|1.751|8.614|0.000|25.91 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58800|0.59192|0.00094|0.16%|0.58944|0.00%|0.58930|0.00%|0.638|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/759829bc2f)|0.58566|0.59200|0.00155|0.26%|0.58728|-0.37%|0.58674|-0.43%|1.896|6.635|0.000|25.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/ce7896d514)|0.58597|0.59152|0.00099|0.17%|0.58688|-0.43%|0.58663|-0.45%|3.617|7.918|0.000|25.95 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44392|0.44816|0.00073|0.16%|0.44479|0.00%|0.44465|0.00%|2.911|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/759829bc2f)|0.44963|0.45227|0.00066|0.15%|0.45114|1.43%|0.45112|1.46%|-0.291|-8.614|0.000|25.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/ce7896d514)|0.44993|0.45243|0.00054|0.12%|0.45106|1.41%|0.45100|1.43%|0.335|-8.614|0.000|25.95 MB|
