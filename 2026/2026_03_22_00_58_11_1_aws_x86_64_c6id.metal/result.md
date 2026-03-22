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
| Time          |2026-03-22 00:58:11 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/23392543625 ([Artifacts](https://github.com/php/php-src/actions/runs/23392543625/artifacts/6043266837))|
| Changeset  |https://github.com/php/php-src/compare/30b2d77cd3..61c83f8af5|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39652|0.39835|0.00037|0.09%|0.39684|0.00%|0.39674|0.00%|2.966|0.000|1.000|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30b2d77cd3)|0.38937|0.39096|0.00031|0.08%|0.38976|-1.78%|0.38972|-1.77%|2.351|8.614|0.000|25.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/61c83f8af5)|0.39007|0.39252|0.00048|0.12%|0.39061|-1.57%|0.39051|-1.57%|2.658|8.614|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61c83f8af5)|0.36454|0.36808|0.00054|0.15%|0.36524|-7.96%|0.36514|-7.96%|3.312|8.614|0.000|25.32 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67022|0.67319|0.00057|0.09%|0.67099|0.00%|0.67082|0.00%|1.541|0.000|1.000|26.72 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30b2d77cd3)|0.66508|0.66792|0.00058|0.09%|0.66574|-0.78%|0.66559|-0.78%|1.715|8.614|0.000|25.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/61c83f8af5)|0.66876|0.67450|0.00099|0.15%|0.66964|-0.20%|0.66931|-0.23%|2.929|6.821|0.000|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61c83f8af5)|0.63757|0.63953|0.00044|0.07%|0.63820|-4.89%|0.63810|-4.88%|1.296|8.614|0.000|25.32 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58912|0.59392|0.00114|0.19%|0.59161|0.00%|0.59131|0.00%|0.154|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30b2d77cd3)|0.58633|0.59018|0.00068|0.12%|0.58728|-0.73%|0.58714|-0.71%|3.072|8.566|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/61c83f8af5)|0.58711|0.59063|0.00077|0.13%|0.58801|-0.61%|0.58778|-0.60%|2.239|8.483|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61c83f8af5)|0.51664|0.52052|0.00068|0.13%|0.51755|-12.52%|0.51740|-12.50%|3.226|8.614|0.000|25.40 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44194|0.44597|0.00067|0.15%|0.44292|0.00%|0.44282|0.00%|1.997|0.000|1.000|26.78 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30b2d77cd3)|0.44452|0.44714|0.00056|0.13%|0.44606|0.71%|0.44596|0.71%|-0.205|-8.435|0.000|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/61c83f8af5)|0.44206|0.44666|0.00091|0.20%|0.44477|0.42%|0.44494|0.48%|-0.661|-7.469|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/61c83f8af5)|0.14346|0.14446|0.00023|0.16%|0.14395|-67.50%|0.14394|-67.49%|0.079|8.614|0.000|25.28 MB|
