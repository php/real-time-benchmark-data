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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-11 00:49:36 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43927|0.44707|0.00135|0.44021|0.00%|0.43999|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/787f26c882)|0.43898|0.44133|0.00055|0.43978|-0.10%|0.43965|-0.08%|41.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/10b2754056)|0.43867|0.44072|0.00054|0.43955|-0.15%|0.43943|-0.13%|41.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10b2754056)|0.42666|0.42813|0.00037|0.42722|-2.95%|0.42717|-2.92%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71261|0.72904|0.00276|0.71448|0.00%|0.71396|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/787f26c882)|0.70749|0.71325|0.00117|0.70903|-0.76%|0.70880|-0.72%|37.57 MB|
|[PHP - master](https://github.com/php/php-src/commit/10b2754056)|0.70414|0.71024|0.00106|0.70818|-0.88%|0.70818|-0.81%|37.57 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10b2754056)|0.67845|0.68044|0.00048|0.67948|-4.90%|0.67949|-4.83%|44.60 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57939|0.58259|0.00073|0.58062|0.00%|0.58054|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/787f26c882)|0.58194|0.58410|0.00060|0.58298|0.41%|0.58282|0.39%|42.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/10b2754056)|0.58214|0.58524|0.00059|0.58308|0.42%|0.58300|0.42%|42.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10b2754056)|0.52229|0.52449|0.00055|0.52342|-9.85%|0.52348|-9.83%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21536|0.21843|0.00068|0.21689|0.00%|0.21687|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/787f26c882)|0.21431|0.21813|0.00096|0.21562|-0.59%|0.21533|-0.71%|26.17 MB|
|[PHP - master](https://github.com/php/php-src/commit/10b2754056)|0.26150|0.28033|0.00509|0.27215|25.48%|0.27141|25.15%|26.17 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10b2754056)|0.07491|0.07869|0.00094|0.07654|-64.71%|0.07654|-64.71%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34123|1.36067|0.00470|1.34951|0.00%|1.34990|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/787f26c882)|1.29061|1.31354|0.00646|1.30000|-3.67%|1.30064|-3.65%|20.44 MB|
|[PHP - master](https://github.com/php/php-src/commit/10b2754056)|1.28760|1.30835|0.00549|1.29760|-3.85%|1.29658|-3.95%|20.44 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/10b2754056)|0.53628|0.56732|0.00650|0.54627|-59.52%|0.54543|-59.59%|21.82 MB|
