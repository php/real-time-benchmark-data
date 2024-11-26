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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241121|
| GCC           |11.4.1|
| Time          |2024-11-26 00:50:38 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43918|0.44499|0.00081|0.44009|0.00%|0.43996|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32ff46b633)|0.43605|0.44336|0.00098|0.43724|-0.65%|0.43716|-0.64%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba6c00505d)|0.43642|0.43878|0.00045|0.43737|-0.62%|0.43736|-0.59%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba6c00505d)|0.42513|0.42677|0.00037|0.42587|-3.23%|0.42583|-3.21%|50.74 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71312|0.71630|0.00065|0.71437|0.00%|0.71433|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32ff46b633)|0.70760|0.71179|0.00104|0.70909|-0.74%|0.70894|-0.76%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba6c00505d)|0.70620|0.71363|0.00121|0.70917|-0.73%|0.70899|-0.75%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba6c00505d)|0.68157|0.68424|0.00071|0.68275|-4.43%|0.68253|-4.45%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58066|0.58345|0.00069|0.58188|0.00%|0.58183|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32ff46b633)|0.57719|0.57956|0.00055|0.57817|-0.64%|0.57811|-0.64%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba6c00505d)|0.57703|0.57952|0.00063|0.57826|-0.62%|0.57822|-0.62%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba6c00505d)|0.52026|0.52336|0.00066|0.52172|-10.34%|0.52158|-10.36%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21478|0.22166|0.00141|0.21648|0.00%|0.21623|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32ff46b633)|0.21597|0.21889|0.00062|0.21689|0.19%|0.21677|0.25%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba6c00505d)|0.21577|0.21895|0.00080|0.21709|0.28%|0.21682|0.27%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba6c00505d)|0.07403|0.07787|0.00091|0.07568|-65.04%|0.07559|-65.04%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34098|1.36652|0.00573|1.35231|0.00%|1.35269|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/32ff46b633)|1.34133|1.36716|0.00589|1.35615|0.28%|1.35630|0.27%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba6c00505d)|1.34461|1.36444|0.00498|1.35674|0.33%|1.35694|0.31%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba6c00505d)|0.52910|0.54585|0.00325|0.53785|-60.23%|0.53806|-60.22%|21.69 MB|
