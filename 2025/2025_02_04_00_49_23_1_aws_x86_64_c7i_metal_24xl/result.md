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
| Kernel        |6.1.124-134.200.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250128|
| GCC           |11.4.1|
| Time          |2025-02-04 00:49:23 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43852|0.45295|0.00196|0.43951|0.00%|0.43931|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/caf5e8a167)|0.43761|0.44051|0.00055|0.43858|-0.21%|0.43850|-0.18%|41.83 MB|
|[PHP - master](https://github.com/php/php-src/commit/9040e795ed)|0.43849|0.44027|0.00042|0.43946|-0.01%|0.43948|0.04%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9040e795ed)|0.42471|0.42688|0.00046|0.42555|-3.18%|0.42552|-3.14%|50.79 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71228|0.71561|0.00072|0.71337|0.00%|0.71320|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/caf5e8a167)|0.70949|0.71343|0.00080|0.71098|-0.33%|0.71091|-0.32%|37.52 MB|
|[PHP - master](https://github.com/php/php-src/commit/9040e795ed)|0.70294|0.71404|0.00146|0.71194|-0.20%|0.71200|-0.17%|37.52 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9040e795ed)|0.68413|0.68686|0.00064|0.68551|-3.91%|0.68537|-3.90%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58049|0.59004|0.00127|0.58164|0.00%|0.58146|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/caf5e8a167)|0.57586|0.58076|0.00087|0.57732|-0.74%|0.57715|-0.74%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/9040e795ed)|0.57599|0.57861|0.00054|0.57720|-0.76%|0.57714|-0.74%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9040e795ed)|0.51956|0.52242|0.00055|0.52082|-10.46%|0.52069|-10.45%|61.92 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21487|0.21782|0.00068|0.21574|0.00%|0.21559|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/caf5e8a167)|0.21426|0.21874|0.00091|0.21597|0.11%|0.21578|0.09%|26.19 MB|
|[PHP - master](https://github.com/php/php-src/commit/9040e795ed)|0.21439|0.21828|0.00090|0.21570|-0.02%|0.21563|0.02%|26.19 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9040e795ed)|0.07358|0.07668|0.00079|0.07498|-65.25%|0.07483|-65.29%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34010|1.36860|0.00620|1.35029|0.00%|1.35029|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/caf5e8a167)|1.23603|1.25951|0.00521|1.24833|-7.55%|1.24829|-7.55%|20.45 MB|
|[PHP - master](https://github.com/php/php-src/commit/9040e795ed)|1.23762|1.26050|0.00417|1.24939|-7.47%|1.24914|-7.49%|20.45 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/9040e795ed)|0.52748|0.55035|0.00498|0.53980|-60.02%|0.53935|-60.06%|21.71 MB|
