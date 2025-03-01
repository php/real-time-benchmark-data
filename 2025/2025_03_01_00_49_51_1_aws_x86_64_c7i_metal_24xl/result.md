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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-03-01 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43928|0.44095|0.00040|0.44003|0.00%|0.44002|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da1e254652)|0.43814|0.44066|0.00051|0.43883|-0.27%|0.43869|-0.30%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|0.43775|0.44044|0.00061|0.43848|-0.35%|0.43844|-0.36%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.42596|0.42923|0.00061|0.42680|-3.01%|0.42656|-3.06%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70690|0.71587|0.00148|0.71403|0.00%|0.71434|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da1e254652)|0.70768|0.71122|0.00078|0.70957|-0.62%|0.70965|-0.66%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|0.70794|0.71091|0.00066|0.70913|-0.69%|0.70909|-0.73%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.68152|0.68532|0.00085|0.68280|-4.37%|0.68278|-4.42%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58059|0.58335|0.00058|0.58206|0.00%|0.58198|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da1e254652)|0.57664|0.57937|0.00060|0.57773|-0.74%|0.57776|-0.73%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|0.57731|0.57963|0.00045|0.57801|-0.69%|0.57791|-0.70%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.52098|0.52382|0.00058|0.52215|-10.29%|0.52211|-10.29%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21445|0.21684|0.00060|0.21566|0.00%|0.21563|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da1e254652)|0.21671|0.21966|0.00074|0.21803|1.10%|0.21794|1.07%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|0.21537|0.21946|0.00100|0.21736|0.79%|0.21738|0.81%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.07516|0.07735|0.00059|0.07620|-64.66%|0.07617|-64.68%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34406|1.36179|0.00437|1.35171|0.00%|1.35191|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/da1e254652)|1.36009|1.38372|0.00575|1.37169|1.48%|1.37304|1.56%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/3677871347)|1.36102|1.38080|0.00483|1.37268|1.55%|1.37235|1.51%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3677871347)|0.54042|0.56599|0.00656|0.55041|-59.28%|0.54764|-59.49%|21.79 MB|
