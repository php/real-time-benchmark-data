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
| Time          |2026-04-24 01:09:26 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/24866976341 ([Artifacts](https://github.com/php/php-src/actions/runs/24866976341/artifacts/6615823815))|
| Changeset  |https://github.com/php/php-src/compare/a935460721..3291dea478|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39452|0.39666|0.00066|0.17%|0.39516|0.00%|0.39490|0.00%|1.339|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a935460721)|0.38692|0.38846|0.00030|0.08%|0.38747|-1.95%|0.38739|-1.90%|1.463|8.614|0.000|25.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/3291dea478)|0.38732|0.38875|0.00037|0.09%|0.38792|-1.83%|0.38783|-1.79%|0.732|8.614|0.000|25.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3291dea478)|0.36079|0.36451|0.00056|0.15%|0.36138|-8.55%|0.36124|-8.53%|3.805|8.614|0.000|25.31 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66696|0.66853|0.00048|0.07%|0.66753|0.00%|0.66735|0.00%|0.756|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a935460721)|0.66337|0.67151|0.00172|0.26%|0.66486|-0.40%|0.66407|-0.49%|1.967|6.704|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/3291dea478)|0.66773|0.67593|0.00118|0.18%|0.66866|0.17%|0.66840|0.16%|5.022|-7.118|0.000|25.30 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3291dea478)|0.63336|0.63539|0.00032|0.05%|0.63373|-5.06%|0.63369|-5.04%|2.946|8.614|0.000|25.29 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58816|0.59293|0.00104|0.18%|0.58975|0.00%|0.58965|0.00%|0.842|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a935460721)|0.58398|0.58655|0.00051|0.09%|0.58470|-0.86%|0.58456|-0.86%|2.053|8.614|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/3291dea478)|0.58451|0.58774|0.00058|0.10%|0.58548|-0.72%|0.58536|-0.73%|1.648|8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3291dea478)|0.51459|0.51795|0.00062|0.12%|0.51539|-12.61%|0.51524|-12.62%|2.704|8.614|0.000|25.69 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44147|0.44508|0.00066|0.15%|0.44294|0.00%|0.44299|0.00%|0.396|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a935460721)|0.44564|0.44735|0.00044|0.10%|0.44662|0.83%|0.44670|0.84%|-0.323|-8.614|0.000|25.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/3291dea478)|0.44543|0.44756|0.00047|0.10%|0.44652|0.81%|0.44652|0.80%|-0.117|-8.614|0.000|25.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3291dea478)|0.14298|0.14372|0.00019|0.13%|0.14340|-67.63%|0.14339|-67.63%|-0.208|8.614|0.000|25.69 MB|
