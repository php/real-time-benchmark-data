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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-20 00:49:45 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44040|0.44379|0.00065|0.44134|0.00%|0.44123|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f129586459)|0.44013|0.44250|0.00050|0.44083|-0.12%|0.44078|-0.10%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/be70f42de7)|0.43824|0.44131|0.00059|0.43904|-0.52%|0.43893|-0.52%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be70f42de7)|0.42316|0.42467|0.00036|0.42401|-3.93%|0.42401|-3.90%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71430|0.71846|0.00091|0.71571|0.00%|0.71562|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f129586459)|0.70950|0.71284|0.00077|0.71051|-0.73%|0.71027|-0.75%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/be70f42de7)|0.71000|0.71212|0.00062|0.71086|-0.68%|0.71063|-0.70%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be70f42de7)|0.67758|0.68087|0.00085|0.67858|-5.19%|0.67821|-5.23%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58152|0.58399|0.00064|0.58241|0.00%|0.58229|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f129586459)|0.57516|0.58127|0.00151|0.57720|-0.89%|0.57693|-0.92%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/be70f42de7)|0.57901|0.58086|0.00049|0.57997|-0.42%|0.57996|-0.40%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be70f42de7)|0.52487|0.52659|0.00040|0.52562|-9.75%|0.52559|-9.74%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21636|0.21916|0.00079|0.21764|0.00%|0.21754|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f129586459)|0.29320|0.30785|0.00292|0.29552|35.78%|0.29465|35.45%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/be70f42de7)|0.21717|0.22166|0.00105|0.21886|0.56%|0.21867|0.52%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be70f42de7)|0.07552|0.07805|0.00065|0.07649|-64.86%|0.07637|-64.89%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34260|1.37009|0.00685|1.35501|0.00%|1.35550|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f129586459)|1.31027|1.33489|0.00551|1.32033|-2.56%|1.31934|-2.67%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/be70f42de7)|1.28352|1.30183|0.00480|1.29262|-4.60%|1.29400|-4.54%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/be70f42de7)|0.55085|0.57405|0.00540|0.56082|-58.61%|0.56024|-58.67%|22.23 MB|
