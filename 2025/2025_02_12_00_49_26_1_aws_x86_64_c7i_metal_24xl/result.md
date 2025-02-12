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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250203|
| GCC           |11.4.1|
| Time          |2025-02-12 00:49:26 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43869|0.45165|0.00173|0.44001|0.00%|0.43979|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c570a22f)|0.43627|0.43832|0.00050|0.43725|-0.63%|0.43711|-0.61%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/5acff0e61d)|0.43840|0.44013|0.00042|0.43915|-0.20%|0.43909|-0.16%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5acff0e61d)|0.42509|0.42718|0.00040|0.42570|-3.25%|0.42571|-3.20%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71237|0.71537|0.00072|0.71362|0.00%|0.71349|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c570a22f)|0.70754|0.71072|0.00086|0.70873|-0.69%|0.70844|-0.71%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/5acff0e61d)|0.70982|0.72612|0.00220|0.71173|-0.26%|0.71136|-0.30%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5acff0e61d)|0.68080|0.68465|0.00075|0.68266|-4.34%|0.68260|-4.33%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58142|0.58494|0.00067|0.58237|0.00%|0.58233|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c570a22f)|0.57711|0.58095|0.00080|0.57853|-0.66%|0.57836|-0.68%|42.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/5acff0e61d)|0.57606|0.58208|0.00132|0.57774|-0.79%|0.57738|-0.85%|42.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5acff0e61d)|0.52010|0.52328|0.00057|0.52137|-10.47%|0.52134|-10.47%|61.94 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21514|0.22068|0.00093|0.21650|0.00%|0.21637|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c570a22f)|0.21542|0.21914|0.00084|0.21664|0.07%|0.21640|0.01%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/5acff0e61d)|0.21129|0.21592|0.00108|0.21311|-1.56%|0.21287|-1.61%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5acff0e61d)|0.07486|0.07701|0.00053|0.07562|-65.07%|0.07554|-65.09%|27.33 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34061|1.36348|0.00547|1.35093|0.00%|1.34996|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e6c570a22f)|1.27212|1.29901|0.00496|1.28181|-5.12%|1.28169|-5.06%|20.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/5acff0e61d)|1.25946|1.27791|0.00434|1.26780|-6.15%|1.26749|-6.11%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5acff0e61d)|0.54297|0.57349|0.00696|0.55627|-58.82%|0.55570|-58.84%|21.76 MB|
