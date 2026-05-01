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
| Time          |2026-05-01 01:19:09 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/25197609447 ([Artifacts](https://github.com/php/php-src/actions/runs/25197609447/artifacts/6743942103))|
| Changeset  |https://github.com/php/php-src/compare/14624997bb..dc807bca6d|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39305|0.39557|0.00078|0.20%|0.39384|0.00%|0.39346|0.00%|1.106|0.000|1.000|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/14624997bb)|0.38704|0.38929|0.00040|0.10%|0.38771|-1.56%|0.38762|-1.49%|2.152|8.614|0.000|25.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc807bca6d)|0.38474|0.38722|0.00056|0.15%|0.38529|-2.17%|0.38514|-2.11%|2.259|8.614|0.000|25.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc807bca6d)|0.35865|0.36045|0.00038|0.11%|0.35936|-8.76%|0.35934|-8.67%|0.806|8.614|0.000|25.30 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.66787|0.67026|0.00056|0.08%|0.66855|0.00%|0.66836|0.00%|1.275|0.000|1.000|26.74 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/14624997bb)|0.67368|0.67645|0.00060|0.09%|0.67473|0.92%|0.67469|0.95%|0.866|-8.614|0.000|25.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc807bca6d)|0.66530|0.66801|0.00049|0.07%|0.66621|-0.35%|0.66619|-0.32%|1.461|8.579|0.000|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc807bca6d)|0.63251|0.63443|0.00040|0.06%|0.63315|-5.30%|0.63307|-5.28%|1.037|8.614|0.000|25.26 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.58816|0.59245|0.00097|0.16%|0.59002|0.00%|0.58994|0.00%|0.415|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/14624997bb)|0.58487|0.58826|0.00072|0.12%|0.58564|-0.74%|0.58545|-0.76%|2.814|8.593|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc807bca6d)|0.58580|0.58917|0.00059|0.10%|0.58677|-0.55%|0.58664|-0.56%|1.742|8.538|0.000|25.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc807bca6d)|0.51651|0.51976|0.00062|0.12%|0.51742|-12.30%|0.51726|-12.32%|2.309|8.614|0.000|25.29 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44174|0.44957|0.00111|0.25%|0.44284|0.00%|0.44266|0.00%|4.716|0.000|1.000|26.73 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/14624997bb)|0.44541|0.44774|0.00050|0.11%|0.44633|0.79%|0.44638|0.84%|0.402|-8.269|0.000|25.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/dc807bca6d)|0.44505|0.45074|0.00101|0.23%|0.44682|0.90%|0.44676|0.93%|1.357|-8.276|0.000|25.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/dc807bca6d)|0.14311|0.14388|0.00018|0.13%|0.14352|-67.59%|0.14352|-67.58%|-0.199|8.614|0.000|25.29 MB|
