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
| Time          |2026-09-17 01:07:51 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/35169323793 ([Artifacts](https://github.com/php/php-src/actions/runs/35169323793/artifacts/10477235125))|
| Changeset  |https://github.com/php/php-src/compare/38956a3f3e..ad4cb0ebd0|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39590|0.39722|0.00022|0.05%|0.39633|0.00%|0.39629|0.00%|1.679|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/38956a3f3e)|0.37097|0.37309|0.00034|0.09%|0.37144|-6.28%|0.37136|-6.29%|3.095|8.614|0.000|25.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cb0ebd0)|0.37139|0.37291|0.00035|0.09%|0.37189|-6.17%|0.37180|-6.18%|1.584|8.614|0.000|25.90 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67628|0.68267|0.00090|0.13%|0.67758|0.00%|0.67749|0.00%|3.740|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/38956a3f3e)|0.67359|0.67737|0.00066|0.10%|0.67440|-0.47%|0.67424|-0.48%|3.174|8.414|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cb0ebd0)|0.66851|0.67008|0.00036|0.05%|0.66907|-1.26%|0.66899|-1.25%|1.241|8.614|0.000|26.28 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58859|0.59289|0.00098|0.17%|0.59046|0.00%|0.59031|0.00%|0.699|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/38956a3f3e)|0.58674|0.59071|0.00086|0.15%|0.58825|-0.37%|0.58812|-0.37%|0.885|7.787|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cb0ebd0)|0.58747|0.59067|0.00071|0.12%|0.58852|-0.33%|0.58840|-0.32%|0.935|7.814|0.000|26.19 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44341|0.45202|0.00157|0.35%|0.44488|0.00%|0.44447|0.00%|3.831|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/38956a3f3e)|0.45086|0.45313|0.00051|0.11%|0.45193|1.58%|0.45187|1.66%|0.086|-8.248|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/ad4cb0ebd0)|0.45099|0.45356|0.00048|0.11%|0.45208|1.62%|0.45215|1.73%|0.183|-8.335|0.000|26.19 MB|
