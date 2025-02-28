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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-02-28 00:49:39 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43864|0.45051|0.00204|0.44007|0.00%|0.43963|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b2a70d45e)|0.43722|0.43933|0.00051|0.43826|-0.41%|0.43823|-0.32%|41.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/da1e254652)|0.43749|0.43936|0.00051|0.43820|-0.43%|0.43816|-0.33%|41.85 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da1e254652)|0.42557|0.42737|0.00039|0.42640|-3.11%|0.42641|-3.01%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71274|0.71589|0.00069|0.71387|0.00%|0.71375|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b2a70d45e)|0.70221|0.71241|0.00154|0.70937|-0.63%|0.70946|-0.60%|37.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/da1e254652)|0.70761|0.71043|0.00076|0.70861|-0.74%|0.70839|-0.75%|37.54 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da1e254652)|0.68041|0.68450|0.00088|0.68203|-4.46%|0.68185|-4.47%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58139|0.58348|0.00051|0.58250|0.00%|0.58255|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b2a70d45e)|0.58007|0.58223|0.00054|0.58108|-0.24%|0.58103|-0.26%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/da1e254652)|0.57687|0.57945|0.00060|0.57824|-0.73%|0.57824|-0.74%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da1e254652)|0.52133|0.52298|0.00037|0.52198|-10.39%|0.52204|-10.39%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21484|0.21917|0.00109|0.21642|0.00%|0.21598|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b2a70d45e)|0.25856|0.27555|0.00441|0.26618|23.00%|0.26665|23.46%|26.26 MB|
|[PHP - master](https://github.com/php/php-src/commit/da1e254652)|0.21588|0.21987|0.00121|0.21753|0.52%|0.21751|0.71%|26.26 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da1e254652)|0.07503|0.07724|0.00068|0.07617|-64.81%|0.07614|-64.75%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33738|1.36454|0.00605|1.34862|0.00%|1.34833|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b2a70d45e)|1.26193|1.27515|0.00362|1.26902|-5.90%|1.26977|-5.83%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/da1e254652)|1.36716|1.38283|0.00457|1.37357|1.85%|1.37392|1.90%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/da1e254652)|0.54248|0.56633|0.00483|0.55162|-59.10%|0.55068|-59.16%|21.79 MB|
