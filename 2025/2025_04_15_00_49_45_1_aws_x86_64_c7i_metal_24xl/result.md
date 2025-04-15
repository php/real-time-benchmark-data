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
| Time          |2025-04-15 00:49:45 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43800|0.44636|0.00141|0.43917|0.00%|0.43898|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8b3328996)|0.43935|0.44081|0.00036|0.44018|0.23%|0.44019|0.27%|41.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b87093bff)|0.43548|0.43879|0.00064|0.43681|-0.54%|0.43676|-0.51%|41.95 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b87093bff)|0.42361|0.42611|0.00065|0.42443|-3.36%|0.42424|-3.36%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71117|0.71538|0.00105|0.71288|0.00%|0.71293|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8b3328996)|0.69757|0.70983|0.00202|0.70782|-0.71%|0.70794|-0.70%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b87093bff)|0.70719|0.70975|0.00062|0.70799|-0.69%|0.70795|-0.70%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b87093bff)|0.66796|0.67637|0.00145|0.67540|-5.26%|0.67563|-5.23%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57995|0.58188|0.00046|0.58103|0.00%|0.58099|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8b3328996)|0.57955|0.58202|0.00058|0.58057|-0.08%|0.58051|-0.08%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b87093bff)|0.57818|0.58106|0.00055|0.57912|-0.33%|0.57908|-0.33%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b87093bff)|0.52065|0.52305|0.00056|0.52129|-10.28%|0.52111|-10.31%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21561|0.22026|0.00115|0.21719|0.00%|0.21677|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8b3328996)|0.21791|0.22197|0.00108|0.21964|1.12%|0.21957|1.29%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b87093bff)|0.21643|0.21954|0.00083|0.21789|0.32%|0.21800|0.57%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b87093bff)|0.07501|0.07860|0.00097|0.07680|-64.64%|0.07703|-64.47%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33654|1.35877|0.00540|1.34676|0.00%|1.34547|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8b3328996)|1.31114|1.32633|0.00379|1.31921|-2.05%|1.31974|-1.91%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/3b87093bff)|1.29140|1.30591|0.00344|1.29958|-3.50%|1.29956|-3.41%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3b87093bff)|0.52236|0.53960|0.00460|0.53262|-60.45%|0.53252|-60.42%|21.82 MB|
