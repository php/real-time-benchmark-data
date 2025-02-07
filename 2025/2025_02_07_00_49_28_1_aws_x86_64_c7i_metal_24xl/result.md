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
| Kernel        |6.1.127-135.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250203|
| GCC           |11.4.1|
| Time          |2025-02-07 00:49:28 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44042|0.44262|0.00055|0.44146|0.00%|0.44147|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cdaa69e122)|0.43798|0.44116|0.00058|0.43887|-0.59%|0.43886|-0.59%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/459fc9de78)|0.43968|0.44263|0.00058|0.44080|-0.15%|0.44086|-0.14%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459fc9de78)|0.42669|0.42863|0.00045|0.42741|-3.18%|0.42731|-3.21%|50.80 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71367|0.71813|0.00091|0.71605|0.00%|0.71590|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cdaa69e122)|0.71486|0.71842|0.00079|0.71645|0.06%|0.71639|0.07%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/459fc9de78)|0.71229|0.71473|0.00060|0.71367|-0.33%|0.71375|-0.30%|37.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459fc9de78)|0.68687|0.69003|0.00071|0.68814|-3.90%|0.68813|-3.88%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58119|0.58391|0.00052|0.58271|0.00%|0.58259|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cdaa69e122)|0.57801|0.58251|0.00076|0.57977|-0.50%|0.57970|-0.50%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/459fc9de78)|0.57784|0.58128|0.00063|0.57934|-0.58%|0.57933|-0.56%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459fc9de78)|0.52233|0.52785|0.00078|0.52321|-10.21%|0.52306|-10.22%|61.93 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21450|0.21860|0.00111|0.21616|0.00%|0.21586|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cdaa69e122)|0.21512|0.22081|0.00112|0.21705|0.41%|0.21698|0.52%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/459fc9de78)|0.21524|0.22004|0.00106|0.21704|0.41%|0.21691|0.49%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459fc9de78)|0.07377|0.07738|0.00077|0.07523|-65.20%|0.07520|-65.16%|27.35 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33442|1.36682|0.00753|1.34895|0.00%|1.34810|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/cdaa69e122)|1.36621|1.38465|0.00455|1.37556|1.97%|1.37577|2.05%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/459fc9de78)|1.36688|1.38354|0.00397|1.37595|2.00%|1.37611|2.08%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/459fc9de78)|0.53513|0.56711|0.00697|0.54760|-59.41%|0.54763|-59.38%|21.77 MB|
