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
| Time          |2025-04-21 00:49:58 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43900|0.44078|0.00044|0.44002|0.00%|0.44004|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f39c07a3bb)|0.43836|0.44597|0.00133|0.43971|-0.07%|0.43953|-0.12%|41.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/158181ff37)|0.43760|0.43984|0.00051|0.43857|-0.33%|0.43859|-0.33%|41.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/158181ff37)|0.42482|0.42739|0.00054|0.42598|-3.19%|0.42588|-3.22%|50.85 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71624|0.72239|0.00128|0.71776|0.00%|0.71741|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f39c07a3bb)|0.71010|0.71255|0.00061|0.71145|-0.88%|0.71156|-0.81%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/158181ff37)|0.71068|0.71378|0.00080|0.71182|-0.83%|0.71170|-0.80%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/158181ff37)|0.68240|0.68512|0.00066|0.68380|-4.73%|0.68366|-4.70%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57996|0.59101|0.00187|0.58169|0.00%|0.58130|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f39c07a3bb)|0.58031|0.58338|0.00059|0.58122|-0.08%|0.58120|-0.02%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/158181ff37)|0.57975|0.58332|0.00066|0.58140|-0.05%|0.58134|0.01%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/158181ff37)|0.51945|0.52259|0.00066|0.52104|-10.43%|0.52108|-10.36%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21538|0.21886|0.00083|0.21669|0.00%|0.21668|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f39c07a3bb)|0.21532|0.22034|0.00090|0.21685|0.07%|0.21681|0.06%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/158181ff37)|0.21761|0.21969|0.00056|0.21861|0.89%|0.21865|0.91%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/158181ff37)|0.07557|0.07890|0.00090|0.07698|-64.47%|0.07683|-64.54%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34102|1.36655|0.00643|1.35188|0.00%|1.35238|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f39c07a3bb)|1.26918|1.29265|0.00487|1.28065|-5.27%|1.28031|-5.33%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/158181ff37)|1.29844|1.31945|0.00484|1.31087|-3.03%|1.31159|-3.02%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/158181ff37)|0.54560|0.56169|0.00427|0.55189|-59.18%|0.55126|-59.24%|21.82 MB|
