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
| Time          |2024-12-07 00:49:47 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43873|0.45309|0.00194|0.43969|0.00%|0.43940|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b80b2e5ec)|0.43707|0.43884|0.00044|0.43798|-0.39%|0.43802|-0.31%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7aba3571f)|0.43815|0.44020|0.00051|0.43903|-0.15%|0.43896|-0.10%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7aba3571f)|0.42476|0.42665|0.00041|0.42553|-3.22%|0.42548|-3.17%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71223|0.71568|0.00070|0.71369|0.00%|0.71357|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b80b2e5ec)|0.71149|0.71582|0.00102|0.71284|-0.12%|0.71258|-0.14%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7aba3571f)|0.70990|0.71346|0.00083|0.71142|-0.32%|0.71138|-0.31%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7aba3571f)|0.67765|0.68597|0.00110|0.68327|-4.26%|0.68338|-4.23%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58069|0.58335|0.00057|0.58187|0.00%|0.58179|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b80b2e5ec)|0.58035|0.58343|0.00066|0.58147|-0.07%|0.58132|-0.08%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7aba3571f)|0.57662|0.57911|0.00059|0.57789|-0.68%|0.57790|-0.67%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7aba3571f)|0.51845|0.52108|0.00056|0.52001|-10.63%|0.52005|-10.61%|60.84 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21477|0.21966|0.00097|0.21633|0.00%|0.21617|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b80b2e5ec)|0.21126|0.21598|0.00101|0.21303|-1.52%|0.21278|-1.57%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7aba3571f)|0.21467|0.21880|0.00077|0.21586|-0.21%|0.21567|-0.23%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7aba3571f)|0.07365|0.07630|0.00060|0.07499|-65.33%|0.07495|-65.33%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33711|1.36581|0.00618|1.35288|0.00%|1.35241|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/2b80b2e5ec)|1.27074|1.29348|0.00428|1.27955|-5.42%|1.27916|-5.42%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/a7aba3571f)|1.24866|1.27223|0.00503|1.26199|-6.72%|1.26217|-6.67%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/a7aba3571f)|0.53428|0.55900|0.00594|0.54531|-59.69%|0.54537|-59.67%|21.64 MB|
