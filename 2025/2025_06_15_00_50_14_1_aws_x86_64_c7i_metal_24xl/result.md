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
| Kernel        |6.1.140-154.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250609|
| GCC           |11.5.0|
| Time          |2025-06-15 00:50:14 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43967|0.44190|0.00045|0.44056|0.00%|0.44045|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7361a1206d)|0.44026|0.44293|0.00061|0.44101|0.10%|0.44089|0.10%|42.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.43941|0.44166|0.00048|0.44034|-0.05%|0.44028|-0.04%|42.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.42393|0.42523|0.00033|0.42445|-3.66%|0.42440|-3.64%|51.32 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70758|0.71781|0.00159|0.71538|0.00%|0.71562|0.00%|37.54 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7361a1206d)|0.71145|0.71493|0.00088|0.71263|-0.38%|0.71247|-0.44%|38.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.71069|0.71397|0.00072|0.71249|-0.40%|0.71244|-0.44%|38.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.67993|0.68213|0.00056|0.68096|-4.81%|0.68084|-4.86%|45.00 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58065|0.58390|0.00072|0.58179|0.00%|0.58173|0.00%|43.11 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7361a1206d)|0.57939|0.58183|0.00057|0.58042|-0.24%|0.58039|-0.23%|43.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.57965|0.58219|0.00062|0.58042|-0.23%|0.58028|-0.25%|43.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.52422|0.52690|0.00067|0.52552|-9.67%|0.52544|-9.68%|61.31 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21515|0.22127|0.00137|0.21718|0.00%|0.21690|0.00%|26.26 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7361a1206d)|0.21637|0.22066|0.00103|0.21804|0.40%|0.21793|0.48%|26.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|0.21603|0.21922|0.00086|0.21755|0.17%|0.21753|0.29%|26.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.07565|0.07874|0.00076|0.07705|-64.52%|0.07691|-64.54%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34004|1.37363|0.00824|1.35377|0.00%|1.35308|0.00%|20.52 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/7361a1206d)|1.31365|1.33147|0.00429|1.32105|-2.42%|1.32071|-2.39%|20.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/2e2494fbef)|1.31181|1.33420|0.00545|1.32102|-2.42%|1.31980|-2.46%|20.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/2e2494fbef)|0.56247|0.57912|0.00443|0.56919|-57.95%|0.56916|-57.94%|22.23 MB|
