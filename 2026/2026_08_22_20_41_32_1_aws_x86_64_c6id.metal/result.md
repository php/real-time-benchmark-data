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
| Time          |2026-08-22 20:41:32 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/32541503950 ([Artifacts](https://github.com/php/php-src/actions/runs/32541503950/artifacts/9482303596))|
| Changeset  |https://github.com/php/php-src/compare/a95a6192f5..271f689482|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39912|0.40025|0.00021|0.05%|0.39945|0.00%|0.39941|0.00%|1.588|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a95a6192f5)|0.37415|0.37534|0.00025|0.07%|0.37453|-6.24%|0.37448|-6.24%|1.022|8.614|0.000|25.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/271f689482)|0.37413|0.37571|0.00040|0.11%|0.37457|-6.23%|0.37443|-6.25%|1.471|8.614|0.000|25.69 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67949|0.68371|0.00082|0.12%|0.68137|0.00%|0.68132|0.00%|0.218|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a95a6192f5)|0.67128|0.67351|0.00045|0.07%|0.67200|-1.37%|0.67190|-1.38%|1.399|8.614|0.000|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/271f689482)|0.67234|0.67388|0.00034|0.05%|0.67297|-1.23%|0.67292|-1.23%|0.584|8.614|0.000|26.22 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59112|0.59449|0.00080|0.13%|0.59268|0.00%|0.59267|0.00%|0.245|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a95a6192f5)|0.59159|0.59565|0.00108|0.18%|0.59253|-0.03%|0.59210|-0.10%|1.915|2.161|0.031|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/271f689482)|0.59028|0.59391|0.00071|0.12%|0.59152|-0.20%|0.59153|-0.19%|1.257|6.460|0.000|26.26 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44296|0.44691|0.00068|0.15%|0.44486|0.00%|0.44487|0.00%|0.151|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a95a6192f5)|0.44962|0.45429|0.00086|0.19%|0.45136|1.46%|0.45130|1.44%|0.817|-8.614|0.000|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/271f689482)|0.45052|0.45440|0.00083|0.18%|0.45240|1.70%|0.45243|1.70%|0.037|-8.614|0.000|26.26 MB|
