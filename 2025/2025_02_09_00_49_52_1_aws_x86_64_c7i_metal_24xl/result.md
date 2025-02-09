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
| Time          |2025-02-09 00:49:52 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43904|0.44593|0.00094|0.43993|0.00%|0.43981|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3e5dbe45b)|0.43669|0.44348|0.00100|0.43765|-0.52%|0.43750|-0.52%|41.82 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e55889dca)|0.43787|0.44551|0.00104|0.43889|-0.23%|0.43878|-0.23%|41.83 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e55889dca)|0.42514|0.42878|0.00057|0.42778|-2.76%|0.42780|-2.73%|50.80 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71245|0.71554|0.00071|0.71358|0.00%|0.71347|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3e5dbe45b)|0.70940|0.71260|0.00076|0.71048|-0.44%|0.71035|-0.44%|37.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e55889dca)|0.70809|0.71170|0.00071|0.70926|-0.61%|0.70914|-0.61%|37.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e55889dca)|0.68314|0.68626|0.00063|0.68437|-4.09%|0.68446|-4.07%|44.52 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58011|0.58386|0.00068|0.58221|0.00%|0.58226|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3e5dbe45b)|0.57801|0.58208|0.00074|0.57990|-0.40%|0.57982|-0.42%|42.96 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e55889dca)|0.57079|0.57775|0.00234|0.57524|-1.20%|0.57634|-1.02%|42.96 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e55889dca)|0.51841|0.52041|0.00050|0.51953|-10.77%|0.51947|-10.78%|61.93 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21458|0.21861|0.00096|0.21598|0.00%|0.21577|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3e5dbe45b)|0.21176|0.21580|0.00090|0.21410|-0.87%|0.21414|-0.75%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e55889dca)|0.21495|0.21863|0.00081|0.21631|0.15%|0.21626|0.23%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e55889dca)|0.07383|0.07608|0.00055|0.07490|-65.32%|0.07491|-65.28%|27.35 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34303|1.36064|0.00413|1.35083|0.00%|1.35061|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d3e5dbe45b)|1.25750|1.28325|0.00611|1.26818|-6.12%|1.26712|-6.18%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/4e55889dca)|1.27633|1.29359|0.00415|1.28249|-5.06%|1.28146|-5.12%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/4e55889dca)|0.51633|0.54254|0.00616|0.53081|-60.70%|0.53100|-60.68%|21.77 MB|
