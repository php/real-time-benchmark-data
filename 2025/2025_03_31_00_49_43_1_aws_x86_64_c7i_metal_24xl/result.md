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
| Kernel        |6.1.130-139.222.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250317|
| GCC           |11.5.0|
| Time          |2025-03-31 00:49:43 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43704|0.45112|0.00238|0.43854|0.00%|0.43809|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0607c22f8e)|0.43386|0.44103|0.00125|0.43477|-0.86%|0.43452|-0.82%|41.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/334d9bbc09)|0.43424|0.43681|0.00057|0.43513|-0.78%|0.43505|-0.69%|41.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/334d9bbc09)|0.42405|0.42778|0.00069|0.42497|-3.09%|0.42483|-3.03%|50.81 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.70644|0.71377|0.00121|0.71170|0.00%|0.71174|0.00%|37.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0607c22f8e)|0.70415|0.70735|0.00083|0.70544|-0.88%|0.70537|-0.89%|37.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/334d9bbc09)|0.70327|0.70595|0.00065|0.70441|-1.02%|0.70432|-1.04%|37.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/334d9bbc09)|0.67588|0.67938|0.00090|0.67740|-4.82%|0.67730|-4.84%|44.58 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57997|0.58213|0.00058|0.58115|0.00%|0.58119|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0607c22f8e)|0.57602|0.57922|0.00065|0.57716|-0.69%|0.57709|-0.71%|43.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/334d9bbc09)|0.57719|0.57879|0.00037|0.57799|-0.54%|0.57801|-0.55%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/334d9bbc09)|0.51622|0.52141|0.00109|0.51983|-10.55%|0.52004|-10.52%|61.94 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21491|0.21830|0.00072|0.21582|0.00%|0.21576|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0607c22f8e)|0.25486|0.27694|0.00514|0.26719|23.80%|0.26745|23.96%|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/334d9bbc09)|0.21567|0.21873|0.00075|0.21729|0.68%|0.21733|0.73%|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/334d9bbc09)|0.07541|0.07735|0.00051|0.07621|-64.69%|0.07623|-64.67%|27.39 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33879|1.36168|0.00566|1.35090|0.00%|1.35136|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0607c22f8e)|1.26224|1.28486|0.00482|1.26965|-6.01%|1.26881|-6.11%|20.60 MB|
|[PHP - master](https://github.com/php/php-src/commit/334d9bbc09)|1.26568|1.27915|0.00356|1.27159|-5.87%|1.27085|-5.96%|20.60 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/334d9bbc09)|0.53229|0.54713|0.00365|0.53902|-60.10%|0.53881|-60.13%|21.81 MB|
