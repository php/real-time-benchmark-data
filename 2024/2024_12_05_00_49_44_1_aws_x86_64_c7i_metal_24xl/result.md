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
| Kernel        |6.1.115-126.197.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241121|
| GCC           |11.4.1|
| Time          |2024-12-05 00:49:44 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43990|0.44776|0.00110|0.44085|0.00%|0.44066|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b01f5e367f)|0.43700|0.44023|0.00060|0.43808|-0.63%|0.43801|-0.60%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/bef96f35fd)|0.43861|0.44623|0.00098|0.44002|-0.19%|0.43991|-0.17%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bef96f35fd)|0.42654|0.42828|0.00041|0.42727|-3.08%|0.42729|-3.03%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71451|0.71746|0.00069|0.71575|0.00%|0.71579|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b01f5e367f)|0.71242|0.71574|0.00076|0.71368|-0.29%|0.71362|-0.30%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/bef96f35fd)|0.71334|0.71964|0.00092|0.71480|-0.13%|0.71474|-0.15%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bef96f35fd)|0.68443|0.68812|0.00080|0.68579|-4.18%|0.68574|-4.20%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57889|0.58332|0.00075|0.58201|0.00%|0.58206|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b01f5e367f)|0.57762|0.58022|0.00067|0.57871|-0.57%|0.57857|-0.60%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/bef96f35fd)|0.58131|0.58439|0.00067|0.58235|0.06%|0.58224|0.03%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bef96f35fd)|0.52058|0.52258|0.00045|0.52136|-10.42%|0.52132|-10.43%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21533|0.21973|0.00097|0.21702|0.00%|0.21701|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b01f5e367f)|0.21518|0.21941|0.00090|0.21665|-0.17%|0.21637|-0.30%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/bef96f35fd)|0.21224|0.21584|0.00076|0.21356|-1.60%|0.21342|-1.65%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bef96f35fd)|0.07380|0.07826|0.00088|0.07519|-65.36%|0.07503|-65.42%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33668|1.36428|0.00635|1.34919|0.00%|1.34851|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/b01f5e367f)|1.24918|1.27190|0.00476|1.26376|-6.33%|1.26305|-6.34%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/bef96f35fd)|1.26858|1.28867|0.00445|1.27860|-5.23%|1.27763|-5.26%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/bef96f35fd)|0.54863|0.57048|0.00491|0.56040|-58.46%|0.56123|-58.38%|21.70 MB|
