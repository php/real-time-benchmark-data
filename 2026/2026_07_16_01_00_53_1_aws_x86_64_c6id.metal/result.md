### AWS x86_64 (c6id.metal)

|  Attribute    |     Value      |
|---------------|----------------|
| Environment   |aws|
| Instance type |c6id.metal|
| Architecture  |x86_64|
| CPU           |Intel(R) Xeon(R) Platinum 8375C CPU @ 2.90GHz, 64 cores @ 2900 MHz|
| CPU settings  |disabled deeper C-states, disabled turbo boost, disabled hyper-threading|
| RAM           |251 GB|
| Kernel        |6.18.20-20.229.amzn2023.x86_64|
| OS            |Amazon Linux 2023.11.20260427|
| GCC           |14.2.1|
| Time          |2026-07-16 01:00:53 UTC|
| Job details  |https://github.com/php/php-src/actions/runs/29462981192 ([Artifacts](https://github.com/php/php-src/actions/runs/29462981192/artifacts/8362684015))|
| Changeset  |https://github.com/php/php-src/compare/b6ebae1fbf..6441f89857|

### Laravel 12.11.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.39823|0.40051|0.00067|0.17%|0.39902|0.00%|0.39868|0.00%|1.300|0.000|1.000|26.71 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b6ebae1fbf)|0.38990|0.39150|0.00039|0.10%|0.39063|-2.10%|0.39055|-2.04%|0.535|8.614|0.000|25.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/6441f89857)|0.38966|0.39099|0.00034|0.09%|0.39007|-2.24%|0.39000|-2.18%|1.229|8.614|0.000|25.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6441f89857)|0.36166|0.36600|0.00067|0.18%|0.36257|-9.13%|0.36250|-9.07%|3.038|8.614|0.000|25.73 MB|

### Symfony 2.8.0 demo app - 50 iterations, 50 warmups, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.67748|0.67940|0.00056|0.08%|0.67830|0.00%|0.67808|0.00%|0.473|0.000|1.000|26.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b6ebae1fbf)|0.67160|0.67384|0.00053|0.08%|0.67233|-0.88%|0.67217|-0.87%|1.156|8.614|0.000|25.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/6441f89857)|0.67029|0.67288|0.00056|0.08%|0.67111|-1.06%|0.67099|-1.05%|1.391|8.614|0.000|25.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6441f89857)|0.63863|0.64409|0.00077|0.12%|0.63936|-5.74%|0.63923|-5.73%|4.976|8.614|0.000|26.21 MB|

### Wordpress 6.9 main page - 50 iterations, 20 warmups, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.59171|0.59596|0.00103|0.17%|0.59373|0.00%|0.59370|0.00%|0.137|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b6ebae1fbf)|0.58727|0.59758|0.00162|0.28%|0.58848|-0.88%|0.58806|-0.95%|4.392|8.159|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/6441f89857)|0.58665|0.59095|0.00097|0.16%|0.58799|-0.97%|0.58782|-0.99%|1.379|8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6441f89857)|0.51714|0.52248|0.00114|0.22%|0.51869|-12.64%|0.51839|-12.69%|1.476|8.614|0.000|26.30 MB|

### bench.php - 50 iterations, 20 warmups, 2 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   | Rel std dev % |  Mean  | Mean diff % |   Median   | Median diff % | Skewness |  Z-stat  | P-value |     Memory    |
|-------------|-------------|-------------|--------------|---------------|--------|-------------|------------|---------------|----------|----------|---------|---------------|
|[PHP - baseline@d5f6e56](https://github.com/php/php-src/commit/d5f6e56610)|0.44338|0.44867|0.00078|0.18%|0.44464|0.00%|0.44460|0.00%|2.827|0.000|1.000|26.67 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b6ebae1fbf)|0.45019|0.45259|0.00068|0.15%|0.45129|1.49%|0.45115|1.47%|0.315|-8.614|0.000|26.18 MB|
|[PHP - master](https://github.com/php/php-src/commit/6441f89857)|0.44928|0.45302|0.00070|0.16%|0.45111|1.45%|0.45101|1.44%|0.211|-8.614|0.000|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6441f89857)|0.14427|0.14513|0.00019|0.13%|0.14466|-67.47%|0.14463|-67.47%|0.141|8.614|0.000|26.30 MB|
