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
| Time          |2024-10-02 00:49:22 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43744|0.44024|0.00059|0.43844|0.00%|0.43846|0.00%|41.85 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a6d111ff2a)|0.43755|0.43953|0.00046|0.43846|0.00%|0.43840|-0.01%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/f1b41d790d)|0.43868|0.44004|0.00036|0.43945|0.23%|0.43951|0.24%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f1b41d790d)|0.43837|0.44001|0.00040|0.43902|0.13%|0.43893|0.11%|41.78 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71380|0.71774|0.00077|0.71559|0.00%|0.71550|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a6d111ff2a)|0.71392|0.71803|0.00078|0.71579|0.03%|0.71573|0.03%|37.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/f1b41d790d)|0.71595|0.73179|0.00272|0.71738|0.25%|0.71688|0.19%|37.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f1b41d790d)|0.71606|0.73255|0.00280|0.71788|0.32%|0.71728|0.25%|37.37 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58014|0.58258|0.00063|0.58134|0.00%|0.58122|0.00%|42.99 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a6d111ff2a)|0.57702|0.57917|0.00053|0.57809|-0.56%|0.57808|-0.54%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/f1b41d790d)|0.57865|0.58109|0.00053|0.57973|-0.28%|0.57972|-0.26%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f1b41d790d)|0.57831|0.58201|0.00075|0.57949|-0.32%|0.57943|-0.31%|42.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21477|0.21892|0.00102|0.21654|0.00%|0.21657|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a6d111ff2a)|0.21233|0.21618|0.00084|0.21373|-1.30%|0.21370|-1.32%|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/f1b41d790d)|0.21387|0.21730|0.00090|0.21513|-0.65%|0.21501|-0.72%|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f1b41d790d)|0.21358|0.21733|0.00112|0.21538|-0.53%|0.21506|-0.70%|26.16 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34729|1.36637|0.00552|1.35616|0.00%|1.35580|0.00%|20.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/a6d111ff2a)|1.36135|1.39199|0.00780|1.37589|1.45%|1.37602|1.49%|20.41 MB|
|[PHP - master](https://github.com/php/php-src/commit/f1b41d790d)|1.41386|1.44838|0.00690|1.42864|5.34%|1.42752|5.29%|20.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f1b41d790d)|1.41411|1.43662|0.00533|1.42481|5.06%|1.42469|5.08%|20.41 MB|
