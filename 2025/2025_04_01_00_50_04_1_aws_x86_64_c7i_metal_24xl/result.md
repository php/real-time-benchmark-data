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
| Time          |2025-04-01 00:50:04 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43807|0.44061|0.00057|0.43923|0.00%|0.43930|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/334d9bbc09)|0.43531|0.44218|0.00120|0.43608|-0.72%|0.43576|-0.80%|41.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/13e0fb92b4)|0.43640|0.43868|0.00050|0.43713|-0.48%|0.43706|-0.51%|41.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/13e0fb92b4)|0.42542|0.42980|0.00078|0.42626|-2.95%|0.42615|-2.99%|50.83 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71247|0.71610|0.00089|0.71389|0.00%|0.71375|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/334d9bbc09)|0.70497|0.70767|0.00068|0.70636|-1.06%|0.70635|-1.04%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/13e0fb92b4)|0.70597|0.70936|0.00079|0.70713|-0.95%|0.70704|-0.94%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/13e0fb92b4)|0.67784|0.68084|0.00073|0.67885|-4.91%|0.67870|-4.91%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57966|0.58328|0.00086|0.58165|0.00%|0.58169|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/334d9bbc09)|0.57837|0.58025|0.00051|0.57909|-0.44%|0.57908|-0.45%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/13e0fb92b4)|0.57696|0.58276|0.00097|0.58127|-0.06%|0.58122|-0.08%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/13e0fb92b4)|0.52063|0.52314|0.00055|0.52137|-10.36%|0.52131|-10.38%|61.96 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21531|0.21865|0.00091|0.21649|0.00%|0.21624|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/334d9bbc09)|0.21555|0.21821|0.00063|0.21663|0.06%|0.21658|0.16%|26.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/13e0fb92b4)|0.21168|0.21446|0.00067|0.21279|-1.71%|0.21271|-1.63%|26.35 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/13e0fb92b4)|0.07502|0.07721|0.00052|0.07601|-64.89%|0.07611|-64.80%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33174|1.35900|0.00596|1.34841|0.00%|1.35012|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/334d9bbc09)|1.26565|1.27687|0.00306|1.27187|-5.68%|1.27192|-5.79%|20.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/13e0fb92b4)|1.25747|1.27456|0.00442|1.26569|-6.13%|1.26451|-6.34%|20.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/13e0fb92b4)|0.54281|0.55994|0.00444|0.54928|-59.26%|0.54822|-59.39%|21.83 MB|
