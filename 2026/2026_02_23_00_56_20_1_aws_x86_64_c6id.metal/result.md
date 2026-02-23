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
| Time          |2026-02-23 00:56:20 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/22289227870 ([Artifacts](https://github.com/php/php-src/actions/runs/22289227870/artifacts/5610749503))|
| Changeset  |https://github.com/php/php-src/compare/da6d890e00..5f87a6e5b6|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39640|0.39820|0.00035|0.09%|0.39677|0.00%|0.39669|0.00%|3.045|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da6d890e00)|0.39081|0.39333|0.00047|0.12%|0.39154|-1.32%|0.39142|-1.33%|2.264|8.614|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/5f87a6e5b6)|0.39126|0.39395|0.00061|0.16%|0.39182|-1.25%|0.39161|-1.28%|2.012|8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5f87a6e5b6)|0.36301|0.36427|0.00030|0.08%|0.36356|-8.37%|0.36349|-8.37%|0.475|8.614|0.000|25.39 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66903|0.67141|0.00049|0.07%|0.66967|0.00%|0.66957|0.00%|1.334|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da6d890e00)|0.66089|0.66227|0.00034|0.05%|0.66148|-1.22%|0.66142|-1.22%|0.587|8.614|0.000|25.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/5f87a6e5b6)|0.66090|0.66457|0.00067|0.10%|0.66177|-1.18%|0.66157|-1.19%|2.604|8.614|0.000|25.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5f87a6e5b6)|0.63030|0.64014|0.00135|0.21%|0.63101|-5.77%|0.63080|-5.79%|6.595|8.614|0.000|25.36 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58933|0.59446|0.00121|0.20%|0.59181|0.00%|0.59189|0.00%|-0.108|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da6d890e00)|0.58712|0.59036|0.00060|0.10%|0.58788|-0.66%|0.58779|-0.69%|2.483|8.538|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/5f87a6e5b6)|0.58726|0.59057|0.00063|0.11%|0.58807|-0.63%|0.58790|-0.67%|2.590|8.490|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5f87a6e5b6)|0.51901|0.52325|0.00081|0.16%|0.51969|-12.19%|0.51945|-12.24%|3.188|8.614|0.000|25.39 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44160|0.44438|0.00060|0.14%|0.44284|0.00%|0.44273|0.00%|0.396|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da6d890e00)|0.44449|0.44782|0.00055|0.12%|0.44580|0.67%|0.44575|0.68%|0.802|-8.614|0.000|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/5f87a6e5b6)|0.44485|0.44716|0.00052|0.12%|0.44585|0.68%|0.44580|0.69%|0.314|-8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5f87a6e5b6)|0.14348|0.14537|0.00032|0.23%|0.14386|-67.51%|0.14379|-67.52%|2.518|8.614|0.000|25.39 MB|
