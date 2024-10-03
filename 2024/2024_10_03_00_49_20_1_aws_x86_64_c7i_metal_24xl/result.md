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
| Time          |2024-10-03 00:49:20 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43751|0.45256|0.00260|0.43866|0.00%|0.43812|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f1b41d790d)|0.43834|0.44039|0.00045|0.43926|0.14%|0.43925|0.26%|41.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/524f6dfb19)|0.43638|0.43804|0.00044|0.43709|-0.36%|0.43715|-0.22%|41.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/524f6dfb19)|0.42832|0.43083|0.00050|0.42968|-2.05%|0.42969|-1.92%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71314|0.71679|0.00084|0.71519|0.00%|0.71501|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f1b41d790d)|0.71559|0.71791|0.00060|0.71674|0.22%|0.71665|0.23%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/524f6dfb19)|0.70827|0.71454|0.00123|0.70972|-0.77%|0.70947|-0.78%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/524f6dfb19)|0.68363|0.68661|0.00069|0.68464|-4.27%|0.68458|-4.26%|44.52 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57960|0.58286|0.00070|0.58059|0.00%|0.58044|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f1b41d790d)|0.57815|0.58029|0.00043|0.57888|-0.30%|0.57877|-0.29%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/524f6dfb19)|0.57754|0.57937|0.00047|0.57853|-0.36%|0.57849|-0.34%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/524f6dfb19)|0.51974|0.52156|0.00043|0.52050|-10.35%|0.52047|-10.33%|61.86 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21484|0.21914|0.00107|0.21646|0.00%|0.21630|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f1b41d790d)|0.21320|0.21776|0.00111|0.21487|-0.73%|0.21450|-0.83%|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/524f6dfb19)|0.21458|0.21705|0.00058|0.21574|-0.33%|0.21576|-0.25%|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/524f6dfb19)|0.07423|0.07715|0.00070|0.07535|-65.19%|0.07518|-65.24%|27.28 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34357|1.36801|0.00527|1.35503|0.00%|1.35543|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f1b41d790d)|1.41156|1.43841|0.00643|1.42586|5.23%|1.42597|5.20%|20.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/524f6dfb19)|1.33695|1.36249|0.00632|1.35026|-0.35%|1.35066|-0.35%|20.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/524f6dfb19)|0.63679|0.65791|0.00524|0.64432|-52.45%|0.64392|-52.49%|21.69 MB|
