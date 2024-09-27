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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20240916|
| GCC           |11.4.1|
| Time          |2024-09-27 00:49:22 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43797|0.44704|0.00151|0.43932|0.00%|0.43914|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/531b94359e)|0.43872|0.44169|0.00071|0.44032|0.23%|0.44023|0.25%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/b32a941b8e)|0.43759|0.44074|0.00083|0.43929|-0.01%|0.43941|0.06%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b32a941b8e)|0.43711|0.43984|0.00077|0.43851|-0.19%|0.43874|-0.09%|41.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71518|0.71949|0.00101|0.71689|0.00%|0.71662|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/531b94359e)|0.71428|0.71657|0.00064|0.71536|-0.21%|0.71549|-0.16%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/b32a941b8e)|0.71543|0.71978|0.00095|0.71701|0.02%|0.71681|0.03%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b32a941b8e)|0.70829|0.71831|0.00167|0.71662|-0.04%|0.71691|0.04%|37.38 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57940|0.58242|0.00060|0.58091|0.00%|0.58087|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/531b94359e)|0.57795|0.58200|0.00071|0.57947|-0.25%|0.57939|-0.26%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/b32a941b8e)|0.57890|0.58123|0.00050|0.58019|-0.12%|0.58013|-0.13%|43.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b32a941b8e)|0.57839|0.58055|0.00058|0.57962|-0.22%|0.57961|-0.22%|43.00 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21462|0.21973|0.00119|0.21616|0.00%|0.21578|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/531b94359e)|0.21443|0.21722|0.00083|0.21576|-0.19%|0.21579|0.01%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/b32a941b8e)|0.21894|0.22307|0.00105|0.22091|2.19%|0.22063|2.25%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b32a941b8e)|0.21948|0.22230|0.00079|0.22058|2.04%|0.22072|2.29%|26.23 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34408|1.36396|0.00529|1.35499|0.00%|1.35490|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/531b94359e)|1.41236|1.43401|0.00571|1.42375|5.07%|1.42346|5.06%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/b32a941b8e)|1.36653|1.37818|0.00335|1.37126|1.20%|1.37103|1.19%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b32a941b8e)|1.36465|1.38057|0.00367|1.37193|1.25%|1.37134|1.21%|20.49 MB|
