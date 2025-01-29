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
| Kernel        |6.1.124-134.200.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250128|
| GCC           |11.4.1|
| Time          |2025-01-29 00:49:27 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43891|0.45444|0.00211|0.44039|0.00%|0.44008|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06c41ec6c5)|0.43695|0.43992|0.00077|0.43831|-0.47%|0.43830|-0.40%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f4579af85)|0.43994|0.44591|0.00094|0.44136|0.22%|0.44124|0.26%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f4579af85)|0.42673|0.43046|0.00081|0.42879|-2.64%|0.42896|-2.53%|50.79 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71366|0.71787|0.00100|0.71532|0.00%|0.71534|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06c41ec6c5)|0.71372|0.73198|0.00262|0.71604|0.10%|0.71554|0.03%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f4579af85)|0.71477|0.71956|0.00096|0.71687|0.22%|0.71679|0.20%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f4579af85)|0.68090|0.69046|0.00142|0.68788|-3.83%|0.68793|-3.83%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58101|0.58448|0.00072|0.58210|0.00%|0.58198|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06c41ec6c5)|0.57950|0.58299|0.00081|0.58093|-0.20%|0.58086|-0.19%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f4579af85)|0.58374|0.59329|0.00130|0.58500|0.50%|0.58478|0.48%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f4579af85)|0.52231|0.52584|0.00084|0.52372|-10.03%|0.52358|-10.03%|62.47 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21474|0.21889|0.00093|0.21600|0.00%|0.21580|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06c41ec6c5)|0.21652|0.22114|0.00100|0.21865|1.23%|0.21853|1.26%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f4579af85)|0.21168|0.21545|0.00085|0.21326|-1.27%|0.21318|-1.21%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f4579af85)|0.07537|0.07770|0.00058|0.07652|-64.57%|0.07653|-64.54%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34165|1.36503|0.00479|1.35065|0.00%|1.35036|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/06c41ec6c5)|1.31329|1.34403|0.00561|1.32458|-1.93%|1.32477|-1.89%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f4579af85)|1.28223|1.30260|0.00422|1.29030|-4.47%|1.28993|-4.47%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f4579af85)|0.58519|0.61385|0.00700|0.60074|-55.52%|0.60044|-55.53%|21.71 MB|
