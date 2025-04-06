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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-06 00:49:48 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43900|0.44854|0.00167|0.43988|0.00%|0.43944|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d80682e753)|0.43735|0.44537|0.00141|0.43845|-0.33%|0.43820|-0.28%|41.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9392b855)|0.43725|0.43878|0.00037|0.43804|-0.42%|0.43801|-0.32%|41.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9392b855)|0.42657|0.43144|0.00097|0.42756|-2.80%|0.42730|-2.76%|50.87 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71148|0.71490|0.00083|0.71281|0.00%|0.71269|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d80682e753)|0.70823|0.71026|0.00051|0.70899|-0.54%|0.70902|-0.51%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9392b855)|0.70761|0.71042|0.00062|0.70859|-0.59%|0.70843|-0.60%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9392b855)|0.67847|0.68077|0.00055|0.67934|-4.70%|0.67927|-4.69%|44.71 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58007|0.58313|0.00069|0.58161|0.00%|0.58155|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d80682e753)|0.57898|0.58134|0.00054|0.58013|-0.25%|0.58015|-0.24%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9392b855)|0.57880|0.58198|0.00065|0.58004|-0.27%|0.57987|-0.29%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9392b855)|0.52056|0.52186|0.00037|0.52120|-10.39%|0.52121|-10.38%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21516|0.21961|0.00106|0.21712|0.00%|0.21713|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d80682e753)|0.25955|0.28733|0.00672|0.27436|26.36%|0.27492|26.62%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9392b855)|0.21627|0.21948|0.00069|0.21745|0.15%|0.21731|0.08%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9392b855)|0.07541|0.07803|0.00071|0.07647|-64.78%|0.07641|-64.81%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33741|1.35331|0.00418|1.34564|0.00%|1.34567|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d80682e753)|1.29291|1.31934|0.00631|1.30131|-3.29%|1.29930|-3.45%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/ac9392b855)|1.28994|1.30896|0.00573|1.29980|-3.41%|1.29871|-3.49%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ac9392b855)|0.53448|0.55917|0.00533|0.54877|-59.22%|0.54874|-59.22%|21.82 MB|
