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
| Kernel        |6.1.129-138.220.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250303|
| GCC           |11.4.1|
| Time          |2025-03-26 00:49:32 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43692|0.43852|0.00039|0.43784|0.00%|0.43789|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fec4f7f389)|0.43574|0.43772|0.00045|0.43651|-0.30%|0.43642|-0.34%|41.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ce79eb219)|0.43564|0.43748|0.00045|0.43652|-0.30%|0.43655|-0.30%|41.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ce79eb219)|0.42540|0.42688|0.00040|0.42617|-2.66%|0.42617|-2.68%|50.81 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71130|0.71446|0.00079|0.71279|0.00%|0.71269|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fec4f7f389)|0.70673|0.71047|0.00085|0.70793|-0.68%|0.70762|-0.71%|37.61 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ce79eb219)|0.70647|0.71846|0.00200|0.70833|-0.63%|0.70802|-0.66%|37.61 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ce79eb219)|0.67935|0.68151|0.00050|0.68045|-4.54%|0.68041|-4.53%|44.57 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57623|0.58266|0.00194|0.57801|0.00%|0.57700|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fec4f7f389)|0.57677|0.57884|0.00059|0.57762|-0.07%|0.57755|0.10%|43.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ce79eb219)|0.57679|0.57939|0.00074|0.57785|-0.03%|0.57775|0.13%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ce79eb219)|0.51830|0.52020|0.00045|0.51924|-10.17%|0.51922|-10.01%|61.93 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21482|0.21805|0.00085|0.21628|0.00%|0.21622|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fec4f7f389)|0.21792|0.22054|0.00059|0.21904|1.28%|0.21894|1.26%|26.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ce79eb219)|0.21655|0.22040|0.00081|0.21826|0.92%|0.21806|0.85%|26.33 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ce79eb219)|0.07452|0.07708|0.00073|0.07594|-64.89%|0.07625|-64.74%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33381|1.36140|0.00676|1.34831|0.00%|1.34937|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/fec4f7f389)|1.27959|1.29819|0.00383|1.28631|-4.60%|1.28582|-4.71%|20.60 MB|
|[PHP - master](https://github.com/php/php-src/commit/1ce79eb219)|1.27885|1.29651|0.00419|1.28710|-4.54%|1.28698|-4.62%|20.60 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1ce79eb219)|0.52378|0.53621|0.00282|0.53024|-60.67%|0.53014|-60.71%|21.80 MB|
