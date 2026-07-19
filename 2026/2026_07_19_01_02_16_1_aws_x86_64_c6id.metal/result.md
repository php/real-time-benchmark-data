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
| Time          |2026-07-19 01:02:16 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29667919269 ([Artifacts](https://github.com/php/php-src/actions/runs/29667919269/artifacts/8436773890))|
| Changeset  |https://github.com/php/php-src/compare/e3de8edbae..c9bead8acb|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39434|0.39525|0.00018|0.05%|0.39473|0.00%|0.39472|0.00%|0.749|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3de8edbae)|0.38708|0.38806|0.00023|0.06%|0.38743|-1.85%|0.38742|-1.85%|0.978|8.614|0.000|25.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/c9bead8acb)|0.38799|0.38955|0.00036|0.09%|0.38847|-1.59%|0.38837|-1.61%|1.670|8.614|0.000|25.73 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c9bead8acb)|0.36122|0.36313|0.00045|0.13%|0.36197|-8.30%|0.36187|-8.32%|1.007|8.614|0.000|25.79 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67283|0.67520|0.00055|0.08%|0.67349|0.00%|0.67328|0.00%|1.019|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3de8edbae)|0.66459|0.66633|0.00038|0.06%|0.66512|-1.24%|0.66504|-1.22%|1.168|8.614|0.000|26.22 MB|
|[PHP - master](https://github.com/php/php-src/commit/c9bead8acb)|0.66437|0.66647|0.00037|0.05%|0.66502|-1.26%|0.66496|-1.24%|1.645|8.614|0.000|26.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c9bead8acb)|0.63690|0.63890|0.00038|0.06%|0.63749|-5.34%|0.63746|-5.32%|1.864|8.614|0.000|26.33 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58828|0.59218|0.00106|0.18%|0.58997|0.00%|0.59002|0.00%|0.313|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3de8edbae)|0.58539|0.59001|0.00119|0.20%|0.58707|-0.49%|0.58677|-0.55%|0.927|7.793|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/c9bead8acb)|0.58508|0.58853|0.00075|0.13%|0.58632|-0.62%|0.58625|-0.64%|0.717|8.572|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c9bead8acb)|0.51428|0.52692|0.00174|0.34%|0.51584|-12.56%|0.51557|-12.62%|5.480|8.614|0.000|26.28 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44321|0.45221|0.00125|0.28%|0.44464|0.00%|0.44456|0.00%|4.645|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e3de8edbae)|0.44789|0.44966|0.00039|0.09%|0.44883|0.94%|0.44882|0.96%|-0.161|-8.269|0.000|26.30 MB|
|[PHP - master](https://github.com/php/php-src/commit/c9bead8acb)|0.44795|0.45155|0.00053|0.12%|0.44894|0.97%|0.44897|0.99%|2.120|-8.269|0.000|26.28 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c9bead8acb)|0.14386|0.14477|0.00020|0.14%|0.14436|-67.53%|0.14436|-67.53%|-0.245|8.614|0.000|26.28 MB|
