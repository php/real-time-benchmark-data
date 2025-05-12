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
| Kernel        |6.1.134-150.224.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250428|
| GCC           |11.5.0|
| Time          |2025-05-12 00:49:53 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43765|0.43957|0.00044|0.43855|0.00%|0.43857|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|0.43796|0.44010|0.00051|0.43874|0.04%|0.43869|0.03%|41.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/331ac35f58)|0.43810|0.43975|0.00044|0.43868|0.03%|0.43864|0.02%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/331ac35f58)|0.42593|0.42869|0.00049|0.42667|-2.71%|0.42654|-2.74%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71339|0.71732|0.00089|0.71481|0.00%|0.71471|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|0.70832|0.71320|0.00106|0.71015|-0.65%|0.70998|-0.66%|37.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/331ac35f58)|0.70855|0.71159|0.00075|0.70972|-0.71%|0.70962|-0.71%|37.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/331ac35f58)|0.67698|0.68693|0.00157|0.68445|-4.25%|0.68454|-4.22%|44.61 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58109|0.59162|0.00182|0.58244|0.00%|0.58207|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|0.58520|0.58684|0.00049|0.58598|0.61%|0.58592|0.66%|43.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/331ac35f58)|0.58521|0.58752|0.00047|0.58618|0.64%|0.58625|0.72%|43.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/331ac35f58)|0.52360|0.52526|0.00042|0.52445|-9.96%|0.52447|-9.90%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21583|0.21902|0.00089|0.21717|0.00%|0.21696|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|0.21419|0.22050|0.00161|0.21606|-0.51%|0.21572|-0.57%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/331ac35f58)|0.21183|0.21621|0.00111|0.21360|-1.65%|0.21333|-1.67%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/331ac35f58)|0.07593|0.07798|0.00063|0.07686|-64.61%|0.07684|-64.58%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34432|1.36721|0.00553|1.35372|0.00%|1.35313|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|1.27171|1.29193|0.00559|1.28181|-5.31%|1.28160|-5.29%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/331ac35f58)|1.27113|1.29743|0.00602|1.27879|-5.54%|1.27788|-5.56%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/331ac35f58)|0.57680|0.59429|0.00389|0.58726|-56.62%|0.58797|-56.55%|21.83 MB|
