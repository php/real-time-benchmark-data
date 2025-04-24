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
| Time          |2025-04-24 00:49:39 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43824|0.44040|0.00051|0.43904|0.00%|0.43895|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ac1b0c917)|0.43794|0.43945|0.00038|0.43866|-0.09%|0.43857|-0.09%|41.98 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3244351d)|0.43743|0.44011|0.00068|0.43838|-0.15%|0.43827|-0.16%|41.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3244351d)|0.42219|0.42394|0.00040|0.42306|-3.64%|0.42310|-3.61%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71540|0.71932|0.00078|0.71680|0.00%|0.71676|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ac1b0c917)|0.70960|0.72374|0.00246|0.71112|-0.79%|0.71058|-0.86%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3244351d)|0.71097|0.72211|0.00188|0.71233|-0.62%|0.71198|-0.67%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3244351d)|0.67919|0.68193|0.00065|0.68028|-5.09%|0.68023|-5.10%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58070|0.58274|0.00047|0.58172|0.00%|0.58178|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ac1b0c917)|0.58056|0.58360|0.00070|0.58155|-0.03%|0.58136|-0.07%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3244351d)|0.58002|0.58263|0.00063|0.58129|-0.07%|0.58133|-0.08%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3244351d)|0.52298|0.52460|0.00047|0.52373|-9.97%|0.52368|-9.99%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21545|0.21982|0.00108|0.21721|0.00%|0.21729|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ac1b0c917)|0.21384|0.21743|0.00090|0.21591|-0.60%|0.21581|-0.68%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3244351d)|0.21714|0.22030|0.00076|0.21889|0.77%|0.21887|0.72%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3244351d)|0.07595|0.07784|0.00057|0.07698|-64.56%|0.07704|-64.55%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34687|1.36830|0.00590|1.35458|0.00%|1.35193|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7ac1b0c917)|1.29198|1.30903|0.00457|1.30122|-3.94%|1.30070|-3.79%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/4f3244351d)|1.31443|1.33293|0.00431|1.32435|-2.23%|1.32418|-2.05%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4f3244351d)|0.55834|0.56691|0.00241|0.56239|-58.48%|0.56260|-58.39%|21.82 MB|
