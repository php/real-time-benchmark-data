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
| Time          |2024-11-29 00:49:38 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43920|0.44121|0.00046|0.43999|0.00%|0.43987|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17187c4646)|0.43702|0.43920|0.00051|0.43788|-0.48%|0.43780|-0.47%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c05e6c247)|0.43744|0.43995|0.00045|0.43834|-0.37%|0.43831|-0.35%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c05e6c247)|0.42464|0.42659|0.00040|0.42553|-3.29%|0.42555|-3.25%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71294|0.72798|0.00210|0.71465|0.00%|0.71413|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17187c4646)|0.70768|0.71190|0.00098|0.70921|-0.76%|0.70913|-0.70%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c05e6c247)|0.70750|0.71213|0.00089|0.70888|-0.81%|0.70870|-0.76%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c05e6c247)|0.68137|0.68425|0.00061|0.68245|-4.51%|0.68237|-4.45%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58060|0.58428|0.00076|0.58202|0.00%|0.58185|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17187c4646)|0.58002|0.58357|0.00082|0.58136|-0.11%|0.58115|-0.12%|42.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c05e6c247)|0.57816|0.58910|0.00195|0.57985|-0.37%|0.57947|-0.41%|42.82 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c05e6c247)|0.52040|0.52298|0.00057|0.52168|-10.37%|0.52159|-10.36%|60.58 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21468|0.21876|0.00116|0.21623|0.00%|0.21594|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17187c4646)|0.21135|0.21498|0.00078|0.21258|-1.68%|0.21244|-1.62%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c05e6c247)|0.21155|0.21684|0.00099|0.21308|-1.45%|0.21282|-1.44%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c05e6c247)|0.07328|0.07717|0.00078|0.07525|-65.20%|0.07527|-65.14%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33547|1.36565|0.00623|1.35200|0.00%|1.35206|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/17187c4646)|1.27225|1.28936|0.00410|1.28004|-5.32%|1.27938|-5.38%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/5c05e6c247)|1.28628|1.31152|0.00478|1.30177|-3.72%|1.30182|-3.72%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/5c05e6c247)|0.53803|0.55953|0.00490|0.54871|-59.42%|0.54925|-59.38%|21.70 MB|
