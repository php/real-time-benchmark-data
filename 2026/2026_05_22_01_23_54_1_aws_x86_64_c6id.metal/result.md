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
| Time          |2026-05-22 01:23:54 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/26262907183 ([Artifacts](https://github.com/php/php-src/actions/runs/26262907183/artifacts/7151417346))|
| Changeset  |https://github.com/php/php-src/compare/755f4e6df0..c56f5ad729|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39631|0.39728|0.00021|0.05%|0.39676|0.00%|0.39672|0.00%|0.341|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/755f4e6df0)|0.38771|0.39024|0.00038|0.10%|0.38809|-2.18%|0.38804|-2.19%|3.803|8.614|0.000|25.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/c56f5ad729)|0.38748|0.38910|0.00034|0.09%|0.38784|-2.25%|0.38775|-2.26%|2.331|8.614|0.000|25.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c56f5ad729)|0.35996|0.36152|0.00035|0.10%|0.36049|-9.14%|0.36045|-9.14%|1.065|8.614|0.000|25.21 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67604|0.67809|0.00051|0.08%|0.67670|0.00%|0.67661|0.00%|0.918|0.000|1.000|26.79 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/755f4e6df0)|0.67250|0.67540|0.00054|0.08%|0.67315|-0.52%|0.67302|-0.53%|2.318|8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/c56f5ad729)|0.67236|0.67678|0.00066|0.10%|0.67309|-0.53%|0.67294|-0.54%|3.875|8.407|0.000|25.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c56f5ad729)|0.63944|0.64245|0.00052|0.08%|0.64013|-5.40%|0.64001|-5.41%|2.907|8.614|0.000|25.75 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58962|0.59431|0.00118|0.20%|0.59214|0.00%|0.59207|0.00%|0.238|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/755f4e6df0)|0.58646|0.58966|0.00082|0.14%|0.58755|-0.77%|0.58733|-0.80%|1.189|8.600|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/c56f5ad729)|0.58639|0.58944|0.00074|0.13%|0.58725|-0.82%|0.58700|-0.86%|1.762|8.614|0.000|25.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c56f5ad729)|0.51666|0.52755|0.00160|0.31%|0.51779|-12.56%|0.51731|-12.63%|4.912|8.614|0.000|25.77 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44180|0.44707|0.00085|0.19%|0.44312|0.00%|0.44301|0.00%|2.110|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/755f4e6df0)|0.44930|0.45349|0.00067|0.15%|0.45064|1.70%|0.45067|1.73%|1.447|-8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/c56f5ad729)|0.44889|0.45135|0.00056|0.12%|0.45031|1.62%|0.45034|1.66%|-0.258|-8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c56f5ad729)|0.14361|0.14715|0.00073|0.51%|0.14412|-67.48%|0.14390|-67.52%|2.778|8.614|0.000|25.78 MB|
