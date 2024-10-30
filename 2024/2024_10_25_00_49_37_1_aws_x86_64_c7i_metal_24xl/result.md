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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-10-25 00:49:37 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43875|0.44102|0.00050|0.43961|0.00%|0.43954|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/551a9ef5e6)|0.43578|0.43953|0.00058|0.43667|-0.67%|0.43659|-0.67%|41.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/1e08c15512)|0.43623|0.43806|0.00043|0.43707|-0.58%|0.43707|-0.56%|41.74 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1e08c15512)|0.42728|0.42941|0.00048|0.42806|-2.63%|0.42806|-2.61%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71518|0.72292|0.00119|0.72094|0.00%|0.72090|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/551a9ef5e6)|0.71155|0.71461|0.00070|0.71296|-1.11%|0.71285|-1.12%|37.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/1e08c15512)|0.70196|0.71431|0.00159|0.71192|-1.25%|0.71194|-1.24%|37.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1e08c15512)|0.68910|0.69138|0.00053|0.69007|-4.28%|0.69008|-4.28%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58132|0.58613|0.00093|0.58331|0.00%|0.58312|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/551a9ef5e6)|0.57869|0.58505|0.00126|0.58028|-0.52%|0.58011|-0.52%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/1e08c15512)|0.57904|0.58187|0.00049|0.58016|-0.54%|0.58012|-0.51%|42.88 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1e08c15512)|0.52226|0.52538|0.00096|0.52388|-10.19%|0.52420|-10.10%|61.88 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21457|0.22009|0.00111|0.21628|0.00%|0.21603|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/551a9ef5e6)|0.21575|0.22064|0.00108|0.21741|0.52%|0.21724|0.56%|26.07 MB|
|[PHP - master](https://github.com/php/php-src/commit/1e08c15512)|0.21571|0.21946|0.00078|0.21694|0.30%|0.21686|0.38%|26.10 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1e08c15512)|0.07438|0.07717|0.00064|0.07558|-65.06%|0.07547|-65.06%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33576|1.36132|0.00519|1.34916|0.00%|1.34936|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/551a9ef5e6)|1.28242|1.30620|0.00430|1.28993|-4.39%|1.28976|-4.42%|20.33 MB|
|[PHP - master](https://github.com/php/php-src/commit/1e08c15512)|1.28057|1.29561|0.00284|1.28706|-4.60%|1.28716|-4.61%|20.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/1e08c15512)|0.52921|0.54838|0.00381|0.53927|-60.03%|0.53914|-60.04%|21.64 MB|