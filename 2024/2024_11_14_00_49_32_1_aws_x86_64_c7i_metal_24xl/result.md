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
| Kernel        |6.1.112-124.190.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241031|
| GCC           |11.4.1|
| Time          |2024-11-14 00:49:32 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43874|0.45278|0.00190|0.43993|0.00%|0.43960|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33ba1a4ab9)|0.43621|0.44441|0.00112|0.43715|-0.63%|0.43694|-0.61%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/3815a773a1)|0.43568|0.43763|0.00042|0.43652|-0.78%|0.43647|-0.71%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3815a773a1)|0.42517|0.42713|0.00040|0.42623|-3.11%|0.42620|-3.05%|50.85 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71949|0.72403|0.00088|0.72083|0.00%|0.72066|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33ba1a4ab9)|0.71520|0.72066|0.00123|0.71681|-0.56%|0.71644|-0.59%|37.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/3815a773a1)|0.71644|0.71896|0.00056|0.71739|-0.48%|0.71727|-0.47%|37.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3815a773a1)|0.68887|0.69362|0.00076|0.69057|-4.20%|0.69043|-4.20%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57796|0.58513|0.00225|0.58084|0.00%|0.57954|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33ba1a4ab9)|0.57875|0.58299|0.00095|0.58017|-0.12%|0.58013|0.10%|43.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/3815a773a1)|0.57941|0.58279|0.00066|0.58055|-0.05%|0.58046|0.16%|43.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3815a773a1)|0.52122|0.52355|0.00053|0.52213|-10.11%|0.52211|-9.91%|62.00 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21491|0.21903|0.00100|0.21647|0.00%|0.21635|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33ba1a4ab9)|0.21529|0.22005|0.00107|0.21712|0.30%|0.21698|0.29%|26.23 MB|
|[PHP - master](https://github.com/php/php-src/commit/3815a773a1)|0.21172|0.21593|0.00094|0.21342|-1.41%|0.21339|-1.37%|26.23 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3815a773a1)|0.07293|0.07647|0.00089|0.07461|-65.53%|0.07439|-65.62%|27.39 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33763|1.35749|0.00443|1.34819|0.00%|1.34828|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/33ba1a4ab9)|1.29019|1.32322|0.00704|1.30718|-3.04%|1.30717|-3.05%|20.48 MB|
|[PHP - master](https://github.com/php/php-src/commit/3815a773a1)|1.27489|1.29408|0.00414|1.28597|-4.62%|1.28600|-4.62%|20.48 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3815a773a1)|0.53479|0.56001|0.00511|0.54378|-59.67%|0.54305|-59.72%|21.80 MB|
