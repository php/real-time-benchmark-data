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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-06-02 00:49:54 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43798|0.45210|0.00247|0.43909|0.00%|0.43856|0.00%|41.91 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a156572e8)|0.43879|0.44120|0.00058|0.43943|0.08%|0.43921|0.15%|42.37 MB|
|[PHP - master](https://github.com/php/php-src/commit/910411f2f5)|0.43996|0.44154|0.00045|0.44079|0.39%|0.44082|0.51%|42.37 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/910411f2f5)|0.41666|0.42353|0.00114|0.42245|-3.79%|0.42259|-3.64%|51.28 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71408|0.72967|0.00269|0.71599|0.00%|0.71553|0.00%|37.56 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a156572e8)|0.71112|0.71362|0.00061|0.71229|-0.52%|0.71227|-0.45%|38.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/910411f2f5)|0.71179|0.72339|0.00210|0.71350|-0.35%|0.71306|-0.34%|38.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/910411f2f5)|0.68037|0.68307|0.00075|0.68146|-4.82%|0.68135|-4.78%|45.03 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58001|0.59351|0.00226|0.58166|0.00%|0.58137|0.00%|43.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a156572e8)|0.58030|0.58341|0.00071|0.58146|-0.03%|0.58129|-0.01%|43.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/910411f2f5)|0.58023|0.58271|0.00068|0.58136|-0.05%|0.58133|-0.01%|43.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/910411f2f5)|0.52374|0.52561|0.00046|0.52461|-9.81%|0.52463|-9.76%|61.05 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21557|0.21909|0.00082|0.21705|0.00%|0.21704|0.00%|26.28 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a156572e8)|0.21423|0.21833|0.00098|0.21537|-0.77%|0.21514|-0.88%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/910411f2f5)|0.21308|0.21649|0.00091|0.21426|-1.28%|0.21400|-1.40%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/910411f2f5)|0.07618|0.07913|0.00070|0.07740|-64.34%|0.07723|-64.42%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34042|1.36225|0.00551|1.35032|0.00%|1.35158|0.00%|20.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2a156572e8)|1.29386|1.31285|0.00497|1.30388|-3.44%|1.30244|-3.64%|20.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/910411f2f5)|1.29637|1.32023|0.00602|1.30718|-3.19%|1.30767|-3.25%|20.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/910411f2f5)|0.54007|0.55625|0.00426|0.54781|-59.43%|0.54788|-59.46%|22.20 MB|
