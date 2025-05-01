### AWS x86_64 (c7i.24xl)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Runner        |host|
| Instance type |c7i.metal-24xl (dedicated)|
| Architecture  |x86_64
| CPU           |48 cores|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |188 GB|
| Kernel        |6.1.132-147.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250414|
| GCC           |11.5.0|
| Time          |2025-05-01 00:49:50 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43564|0.43694|0.00028|0.43638|0.00%|0.43637|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5f3281446)|0.43323|0.43570|0.00058|0.43423|-0.49%|0.43407|-0.53%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/156d034d3d)|0.43746|0.43908|0.00053|0.43816|0.41%|0.43793|0.36%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156d034d3d)|0.42192|0.42378|0.00047|0.42287|-3.10%|0.42272|-3.13%|50.84 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71184|0.72839|0.00368|0.71423|0.00%|0.71307|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5f3281446)|0.70479|0.71866|0.00251|0.70649|-1.08%|0.70585|-1.01%|37.64 MB|
|[PHP - master](https://github.com/php/php-src/commit/156d034d3d)|0.70541|0.70826|0.00072|0.70642|-1.09%|0.70617|-0.97%|37.64 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156d034d3d)|0.67305|0.68173|0.00138|0.67970|-4.84%|0.67986|-4.66%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57861|0.58249|0.00074|0.58004|0.00%|0.57995|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5f3281446)|0.58016|0.58371|0.00082|0.58114|0.19%|0.58099|0.18%|43.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/156d034d3d)|0.58189|0.58415|0.00068|0.58287|0.49%|0.58277|0.49%|43.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156d034d3d)|0.51878|0.52164|0.00068|0.52009|-10.34%|0.52026|-10.29%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21496|0.21929|0.00101|0.21663|0.00%|0.21634|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5f3281446)|0.21824|0.22172|0.00091|0.21992|1.52%|0.22001|1.70%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/156d034d3d)|0.21492|0.21863|0.00080|0.21602|-0.28%|0.21587|-0.22%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156d034d3d)|0.07572|0.07847|0.00064|0.07665|-64.62%|0.07654|-64.62%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33794|1.36574|0.00558|1.35205|0.00%|1.35216|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c5f3281446)|1.29801|1.30941|0.00348|1.30281|-3.64%|1.30282|-3.65%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/156d034d3d)|1.27869|1.30375|0.00526|1.29267|-4.39%|1.29303|-4.37%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/156d034d3d)|0.54567|0.56253|0.00460|0.55293|-59.10%|0.55153|-59.21%|21.82 MB|
