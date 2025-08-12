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
| Kernel        |6.1.147-172.266.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250808|
| GCC           |11.5.0|
| Time          |2025-08-12 00:50:04 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74178|0.76411|0.00444|0.74827|0.00%|0.74745|0.00%|46.65 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|0.73499|0.76425|0.00708|0.74643|-0.25%|0.74528|-0.29%|47.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d74dd0395)|0.73940|0.75960|0.00537|0.74704|-0.17%|0.74627|-0.16%|46.98 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d74dd0395)|0.71843|0.74273|0.00655|0.72648|-2.91%|0.72395|-3.14%|58.03 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.00380|0.00394|0.00004|0.00385|0.00%|0.00385|0.00%|28.06 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|0.00383|0.00396|0.00003|0.00388|0.65%|0.00387|0.73%|27.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d74dd0395)|0.00376|0.00401|0.00005|0.00390|1.12%|0.00387|0.75%|27.84 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d74dd0395)|0.00385|0.00399|0.00003|0.00388|0.72%|0.00388|0.78%|29.19 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58085|0.64889|0.01194|0.58535|0.00%|0.58305|0.00%|43.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|0.57878|0.58256|0.00102|0.58048|-0.83%|0.58035|-0.46%|43.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d74dd0395)|0.57932|0.58356|0.00095|0.58114|-0.72%|0.58141|-0.28%|43.68 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d74dd0395)|0.52059|0.52349|0.00070|0.52204|-10.82%|0.52220|-10.44%|61.47 MB|

### bench.php - 20 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21518|0.22013|0.00127|0.21657|0.00%|0.21626|0.00%|25.35 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|0.21550|0.28201|0.02132|0.22495|3.87%|0.21659|0.15%|25.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d74dd0395)|0.21818|0.27968|0.01860|0.22734|4.97%|0.21921|1.36%|25.20 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d74dd0395)|0.08179|0.08366|0.00052|0.08284|-61.75%|0.08288|-61.68%|26.47 MB|

### micro_bench.php - 20 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.36738|1.39604|0.00787|1.37915|0.00%|1.37868|0.00%|20.66 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/8f1a627e79)|1.33054|1.34266|0.00359|1.33661|-3.08%|1.33666|-3.05%|20.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/4d74dd0395)|1.26898|1.28697|0.00411|1.27734|-7.38%|1.27711|-7.37%|20.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4d74dd0395)|0.55240|0.57739|0.00617|0.55836|-59.51%|0.55720|-59.58%|22.23 MB|
