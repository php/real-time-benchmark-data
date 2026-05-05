### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-05-05 01:09:18 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25352400473 ([Artifacts](https://github.com/php/php-src/actions/runs/25352400473/artifacts/6797381506))|
| Changeset  |https://github.com/php/php-src/compare/87258eb267..c94cb02667|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39778|0.39978|0.00028|0.07%|0.39831|0.00%|0.39827|0.00%|2.986|0.000|1.000|26.72 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87258eb267)|0.38924|0.39101|0.00038|0.10%|0.38965|-2.17%|0.38957|-2.19%|1.859|8.614|0.000|25.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/c94cb02667)|0.38941|0.39127|0.00036|0.09%|0.38993|-2.10%|0.38982|-2.12%|1.720|8.614|0.000|25.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c94cb02667)|0.36336|0.36566|0.00054|0.15%|0.36402|-8.61%|0.36387|-8.64%|1.782|8.614|0.000|25.29 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67763|0.68041|0.00062|0.09%|0.67852|0.00%|0.67830|0.00%|1.222|0.000|1.000|26.80 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87258eb267)|0.66737|0.66927|0.00039|0.06%|0.66789|-1.57%|0.66781|-1.55%|1.461|8.614|0.000|25.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/c94cb02667)|0.67284|0.67527|0.00041|0.06%|0.67337|-0.76%|0.67328|-0.74%|2.478|8.614|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c94cb02667)|0.64057|0.67414|0.00518|0.81%|0.64240|-5.32%|0.64122|-5.47%|5.406|8.614|0.000|25.40 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59511|0.59986|0.00100|0.17%|0.59724|0.00%|0.59735|0.00%|0.364|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87258eb267)|0.58541|0.59944|0.00198|0.33%|0.59219|-0.84%|0.59212|-0.88%|-0.669|8.283|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/c94cb02667)|0.59274|0.59569|0.00056|0.09%|0.59333|-0.66%|0.59326|-0.68%|2.260|8.593|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c94cb02667)|0.52377|0.53426|0.00153|0.29%|0.52466|-12.15%|0.52424|-12.24%|5.306|8.614|0.000|25.41 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44182|0.44541|0.00072|0.16%|0.44306|0.00%|0.44300|0.00%|1.048|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/87258eb267)|0.44573|0.44817|0.00061|0.14%|0.44677|0.84%|0.44671|0.84%|0.357|-8.614|0.000|25.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/c94cb02667)|0.44640|0.45025|0.00080|0.18%|0.44728|0.95%|0.44718|0.94%|2.363|-8.614|0.000|25.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c94cb02667)|0.14391|0.14582|0.00032|0.23%|0.14437|-67.42%|0.14435|-67.42%|2.997|8.614|0.000|25.41 MB|
