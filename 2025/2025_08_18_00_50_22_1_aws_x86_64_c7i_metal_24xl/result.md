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
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250808|
| GCC           |11.5.0|
| Time          |2025-08-18 00:50:22 UTC|

### Laravel 12.2.0 demo app - 60 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47101|0.47491|0.00074|0.16%|0.47192|0.00%|0.47178|0.00%|1.000|46.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d92675b6c1)|0.46489|0.46784|0.00054|0.12%|0.46621|-1.21%|0.46624|-1.18%|0.001|47.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/c98b173430)|0.46482|0.47207|0.00093|0.20%|0.46626|-1.20%|0.46613|-1.20%|0.001|47.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c98b173430)|0.44984|0.45259|0.00056|0.12%|0.45124|-4.38%|0.45124|-4.36%|0.001|58.05 MB|

### Symfony 2.7.0 demo app - 60 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74192|0.74745|0.00112|0.15%|0.74371|0.00%|0.74368|0.00%|1.000|28.06 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d92675b6c1)|0.73232|0.74416|0.00228|0.31%|0.73475|-1.21%|0.73422|-1.27%|0.001|27.91 MB|
|[PHP - master](https://github.com/php/php-src/commit/c98b173430)|0.72455|0.74372|0.00231|0.32%|0.73429|-1.27%|0.73417|-1.28%|0.001|27.90 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c98b173430)|0.70110|0.70733|0.00102|0.15%|0.70277|-5.51%|0.70276|-5.50%|0.001|29.26 MB|

### Wordpress 6.2 main page - 60 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58130|0.58537|0.00061|0.10%|0.58336|0.00%|0.58334|0.00%|1.000|43.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d92675b6c1)|0.57913|0.58248|0.00067|0.12%|0.58017|-0.55%|0.58007|-0.56%|0.001|43.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/c98b173430)|0.57904|0.58181|0.00056|0.10%|0.58019|-0.54%|0.58006|-0.56%|0.001|43.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c98b173430)|0.51631|0.51884|0.00054|0.10%|0.51728|-11.33%|0.51719|-11.34%|0.001|61.48 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21551|0.21840|0.00093|0.43%|0.21697|0.00%|0.21694|0.00%|1.000|25.35 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d92675b6c1)|0.21570|0.27129|0.01770|7.90%|0.22398|3.23%|0.21746|0.24%|0.145|25.28 MB|
|[PHP - master](https://github.com/php/php-src/commit/c98b173430)|0.21638|0.26543|0.01237|5.60%|0.22079|1.76%|0.21769|0.35%|0.243|25.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c98b173430)|0.08295|0.08560|0.00067|0.80%|0.08365|-61.45%|0.08348|-61.52%|0.001|26.54 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|---------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.36951|1.56402|0.04278|3.08%|1.38962|0.00%|1.38075|0.00%|1.000|20.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d92675b6c1)|1.30379|1.32142|0.00461|0.35%|1.31044|-5.70%|1.31109|-5.04%|0.001|20.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/c98b173430)|1.29824|1.31437|0.00414|0.32%|1.30777|-5.89%|1.30864|-5.22%|0.001|20.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c98b173430)|0.54600|0.56871|0.00511|0.92%|0.55377|-60.15%|0.55375|-59.89%|0.001|22.30 MB|
