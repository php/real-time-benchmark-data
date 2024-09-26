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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20240916|
| GCC           |11.4.1|
| Time          |2024-09-26 00:49:34 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43775|0.43950|0.00050|0.43849|0.00%|0.43839|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a3dae18ed)|0.43753|0.43994|0.00061|0.43850|0.00%|0.43842|0.01%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/531b94359e)|0.43857|0.44069|0.00049|0.43946|0.22%|0.43934|0.22%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/531b94359e)|0.43816|0.44120|0.00059|0.43924|0.17%|0.43911|0.16%|41.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71464|0.71717|0.00061|0.71550|0.00%|0.71533|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a3dae18ed)|0.71302|0.71587|0.00054|0.71396|-0.22%|0.71394|-0.19%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/531b94359e)|0.70522|0.71703|0.00197|0.71429|-0.17%|0.71439|-0.13%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/531b94359e)|0.71255|0.71618|0.00098|0.71429|-0.17%|0.71412|-0.17%|37.38 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58020|0.58264|0.00064|0.58120|0.00%|0.58110|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a3dae18ed)|0.57942|0.58264|0.00071|0.58058|-0.11%|0.58062|-0.08%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/531b94359e)|0.57824|0.58058|0.00059|0.57959|-0.28%|0.57968|-0.24%|43.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/531b94359e)|0.57867|0.58159|0.00060|0.57980|-0.24%|0.57968|-0.24%|43.00 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21531|0.21824|0.00070|0.21629|0.00%|0.21614|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a3dae18ed)|0.21625|0.21905|0.00063|0.21711|0.38%|0.21703|0.41%|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/531b94359e)|0.21323|0.21720|0.00094|0.21518|-0.52%|0.21488|-0.58%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/531b94359e)|0.21424|0.21963|0.00111|0.21626|-0.01%|0.21618|0.02%|26.23 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34457|1.35943|0.00403|1.35109|0.00%|1.35126|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a3dae18ed)|1.34471|1.36238|0.00429|1.35278|0.13%|1.35349|0.16%|20.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/531b94359e)|1.41244|1.43701|0.00641|1.42387|5.39%|1.42289|5.30%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/531b94359e)|1.41617|1.43599|0.00466|1.42255|5.29%|1.42136|5.19%|20.49 MB|
