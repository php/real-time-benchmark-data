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
| Kernel        |6.1.141-155.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250623|
| GCC           |11.5.0|
| Time          |2025-07-01 00:50:02 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43655|0.45962|0.00346|0.44164|0.00%|0.44114|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/db157e3168)|0.44029|0.44357|0.00066|0.44106|-0.13%|0.44094|-0.05%|42.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a98b36416)|0.44152|0.44422|0.00063|0.44242|0.18%|0.44231|0.26%|42.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a98b36416)|0.42844|0.43026|0.00044|0.42941|-2.77%|0.42944|-2.65%|51.58 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71314|0.71644|0.00092|0.71461|0.00%|0.71448|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/db157e3168)|0.70482|0.71036|0.00115|0.70667|-1.11%|0.70648|-1.12%|38.40 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a98b36416)|0.70663|0.71094|0.00101|0.70812|-0.91%|0.70789|-0.92%|38.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a98b36416)|0.67935|0.68327|0.00086|0.68098|-4.71%|0.68074|-4.72%|45.20 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58291|0.58499|0.00056|0.58355|0.00%|0.58333|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/db157e3168)|0.58361|0.58622|0.00062|0.58483|0.22%|0.58480|0.25%|43.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a98b36416)|0.58332|0.58527|0.00052|0.58427|0.12%|0.58431|0.17%|43.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a98b36416)|0.52529|0.52893|0.00067|0.52673|-9.74%|0.52662|-9.72%|61.63 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21386|0.21969|0.00141|0.21607|0.00%|0.21552|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/db157e3168)|0.21533|0.21926|0.00091|0.21674|0.31%|0.21671|0.55%|26.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a98b36416)|0.21282|0.21653|0.00093|0.21468|-0.65%|0.21448|-0.49%|26.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a98b36416)|0.07570|0.07856|0.00076|0.07709|-64.32%|0.07689|-64.32%|28.00 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42207|1.43742|0.00400|1.42823|0.00%|1.42749|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/db157e3168)|1.29040|1.30637|0.00415|1.29942|-9.02%|1.30086|-8.87%|21.04 MB|
|[PHP - master](https://github.com/php/php-src/commit/4a98b36416)|1.30408|1.33075|0.00537|1.31831|-7.70%|1.31843|-7.64%|21.04 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4a98b36416)|0.55068|0.57650|0.00695|0.56517|-60.43%|0.56696|-60.28%|22.43 MB|
