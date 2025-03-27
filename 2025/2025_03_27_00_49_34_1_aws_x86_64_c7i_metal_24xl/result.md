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
| Time          |2025-03-27 00:49:34 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44094|0.44293|0.00050|0.44187|0.00%|0.44181|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ce79eb219)|0.43895|0.44667|0.00130|0.44021|-0.37%|0.43996|-0.42%|41.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/0006522211)|0.44024|0.44388|0.00079|0.44142|-0.10%|0.44135|-0.10%|41.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0006522211)|0.43013|0.43225|0.00049|0.43095|-2.47%|0.43091|-2.47%|50.82 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71707|0.72009|0.00080|0.71843|0.00%|0.71827|0.00%|37.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ce79eb219)|0.71400|0.71882|0.00108|0.71549|-0.41%|0.71520|-0.43%|37.62 MB|
|[PHP - master](https://github.com/php/php-src/commit/0006522211)|0.71336|0.71718|0.00086|0.71427|-0.58%|0.71415|-0.57%|37.62 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0006522211)|0.68262|0.68542|0.00073|0.68387|-4.81%|0.68385|-4.79%|44.57 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58140|0.58396|0.00060|0.58266|0.00%|0.58265|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ce79eb219)|0.57894|0.59074|0.00204|0.58058|-0.36%|0.58007|-0.44%|43.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/0006522211)|0.58057|0.58276|0.00050|0.58155|-0.19%|0.58144|-0.21%|43.01 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0006522211)|0.52129|0.52612|0.00088|0.52231|-10.36%|0.52233|-10.35%|61.94 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21529|0.21815|0.00064|0.21659|0.00%|0.21651|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ce79eb219)|0.21692|0.22042|0.00066|0.21791|0.61%|0.21789|0.63%|26.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/0006522211)|0.21570|0.21922|0.00074|0.21731|0.33%|0.21737|0.39%|26.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0006522211)|0.07489|0.07721|0.00064|0.07582|-64.99%|0.07583|-64.98%|27.39 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33910|1.36568|0.00649|1.34749|0.00%|1.34655|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/1ce79eb219)|1.27478|1.29311|0.00458|1.28589|-4.57%|1.28727|-4.40%|20.60 MB|
|[PHP - master](https://github.com/php/php-src/commit/0006522211)|1.25924|1.27927|0.00447|1.26801|-5.90%|1.26828|-5.81%|20.60 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0006522211)|0.52312|0.53785|0.00420|0.52787|-60.83%|0.52611|-60.93%|21.81 MB|
