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
| Time          |2026-08-10 00:49:53 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/31345456474 ([Artifacts](https://github.com/php/php-src/actions/runs/31345456474/artifacts/9047900811))|
| Changeset  |https://github.com/php/php-src/compare/b9b44872d7..0b7f50ad2e|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.40024|0.40148|0.00030|0.07%|0.40064|0.00%|0.40060|0.00%|1.173|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b9b44872d7)|0.38968|0.39180|0.00032|0.08%|0.39016|-2.62%|0.39010|-2.62%|3.012|8.614|0.000|25.75 MB|
|[PHP - master](https://github.com/php/php-src/commit/0b7f50ad2e)|0.39017|0.39213|0.00047|0.12%|0.39076|-2.47%|0.39062|-2.49%|1.741|8.614|0.000|25.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0b7f50ad2e)|0.36518|0.36648|0.00022|0.06%|0.36560|-8.75%|0.36557|-8.74%|1.575|8.614|0.000|25.78 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67953|0.68730|0.00120|0.18%|0.68149|0.00%|0.68133|0.00%|2.520|0.000|1.000|26.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b9b44872d7)|0.67347|0.67566|0.00039|0.06%|0.67404|-1.09%|0.67397|-1.08%|2.030|8.614|0.000|25.84 MB|
|[PHP - master](https://github.com/php/php-src/commit/0b7f50ad2e)|0.67583|0.68835|0.00207|0.31%|0.67691|-0.67%|0.67635|-0.73%|4.627|7.931|0.000|25.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0b7f50ad2e)|0.64963|0.65697|0.00162|0.25%|0.65066|-4.53%|0.65005|-4.59%|2.771|8.614|0.000|25.92 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59258|0.59836|0.00115|0.19%|0.59466|0.00%|0.59446|0.00%|1.040|0.000|1.000|26.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b9b44872d7)|0.59035|0.59388|0.00095|0.16%|0.59121|-0.58%|0.59092|-0.60%|2.037|8.248|0.000|26.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/0b7f50ad2e)|0.59049|0.59547|0.00089|0.15%|0.59150|-0.53%|0.59127|-0.54%|2.877|8.090|0.000|26.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0b7f50ad2e)|0.52021|0.52415|0.00072|0.14%|0.52116|-12.36%|0.52098|-12.36%|2.677|8.614|0.000|26.35 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44359|0.44771|0.00078|0.17%|0.44487|0.00%|0.44466|0.00%|1.426|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b9b44872d7)|0.44978|0.45200|0.00057|0.13%|0.45094|1.37%|0.45096|1.42%|-0.222|-8.614|0.000|26.15 MB|
|[PHP - master](https://github.com/php/php-src/commit/0b7f50ad2e)|0.44943|0.45704|0.00112|0.25%|0.45084|1.34%|0.45072|1.36%|3.732|-8.614|0.000|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0b7f50ad2e)|0.14420|0.14497|0.00019|0.13%|0.14460|-67.50%|0.14462|-67.48%|0.037|8.614|0.000|26.11 MB|
