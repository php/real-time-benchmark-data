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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250107|
| GCC           |11.4.1|
| Time          |2025-01-13 00:49:44 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43879|0.44062|0.00038|0.43947|0.00%|0.43941|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6f42c1ed0)|0.43755|0.44530|0.00111|0.43878|-0.16%|0.43858|-0.19%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99d62013b)|0.43827|0.44626|0.00166|0.43956|0.02%|0.43910|-0.07%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99d62013b)|0.42475|0.42646|0.00041|0.42559|-3.16%|0.42555|-3.15%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71334|0.71686|0.00065|0.71477|0.00%|0.71468|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6f42c1ed0)|0.71280|0.71601|0.00069|0.71379|-0.14%|0.71375|-0.13%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99d62013b)|0.71211|0.71524|0.00066|0.71350|-0.18%|0.71349|-0.17%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99d62013b)|0.68361|0.68726|0.00073|0.68453|-4.23%|0.68450|-4.22%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58082|0.58362|0.00058|0.58236|0.00%|0.58229|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6f42c1ed0)|0.57819|0.58084|0.00063|0.57944|-0.50%|0.57933|-0.51%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99d62013b)|0.57828|0.58145|0.00063|0.57974|-0.45%|0.57971|-0.44%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99d62013b)|0.51850|0.52606|0.00101|0.52160|-10.43%|0.52160|-10.42%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21618|0.22091|0.00106|0.21776|0.00%|0.21765|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6f42c1ed0)|0.21590|0.22019|0.00088|0.21767|-0.04%|0.21753|-0.05%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99d62013b)|0.21494|0.21998|0.00113|0.21694|-0.37%|0.21682|-0.38%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99d62013b)|0.07411|0.07783|0.00074|0.07595|-65.12%|0.07584|-65.15%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33923|1.36708|0.00543|1.35524|0.00%|1.35509|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6f42c1ed0)|1.29413|1.30919|0.00377|1.30188|-3.94%|1.30210|-3.91%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/f99d62013b)|1.28857|1.31416|0.00574|1.30299|-3.86%|1.30328|-3.82%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/f99d62013b)|0.53334|0.55328|0.00479|0.54308|-59.93%|0.54387|-59.86%|21.72 MB|