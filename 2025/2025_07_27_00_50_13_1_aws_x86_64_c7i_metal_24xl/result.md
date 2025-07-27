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
| Kernel        |6.1.144-170.251.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250721|
| GCC           |11.5.0|
| Time          |2025-07-27 00:50:13 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44141|0.45405|0.00212|0.44314|0.00%|0.44276|0.00%|42.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/747ecce51f)|0.43845|0.44157|0.00062|0.43927|-0.87%|0.43919|-0.81%|42.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f3bc59950)|0.43779|0.43986|0.00057|0.43883|-0.97%|0.43884|-0.89%|42.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f3bc59950)|0.42471|0.42750|0.00052|0.42541|-4.00%|0.42533|-3.94%|51.46 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71820|0.72143|0.00072|0.71992|0.00%|0.71978|0.00%|37.68 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/747ecce51f)|0.71135|0.71448|0.00072|0.71285|-0.98%|0.71281|-0.97%|38.29 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f3bc59950)|0.71138|0.72481|0.00231|0.71302|-0.96%|0.71260|-1.00%|38.29 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f3bc59950)|0.67780|0.68226|0.00104|0.67979|-5.57%|0.67966|-5.57%|45.07 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58238|0.58477|0.00064|0.58379|0.00%|0.58390|0.00%|43.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/747ecce51f)|0.57974|0.58186|0.00052|0.58073|-0.52%|0.58080|-0.53%|43.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f3bc59950)|0.57981|0.58278|0.00074|0.58121|-0.44%|0.58109|-0.48%|43.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f3bc59950)|0.52512|0.52727|0.00045|0.52613|-9.88%|0.52612|-9.89%|62.18 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21373|0.21841|0.00140|0.21579|0.00%|0.21550|0.00%|26.40 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/747ecce51f)|0.21874|0.22338|0.00112|0.22032|2.10%|0.22024|2.20%|26.71 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f3bc59950)|0.21727|0.22201|0.00136|0.21915|1.55%|0.21878|1.52%|26.71 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f3bc59950)|0.07728|0.07950|0.00056|0.07799|-63.86%|0.07773|-63.93%|27.92 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42417|1.43923|0.00387|1.43229|0.00%|1.43228|0.00%|20.63 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/747ecce51f)|1.28135|1.30282|0.00539|1.29114|-9.85%|1.29040|-9.91%|21.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/6f3bc59950)|1.28238|1.30433|0.00482|1.29187|-9.80%|1.29138|-9.84%|21.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/6f3bc59950)|0.55706|0.57146|0.00435|0.56367|-60.65%|0.56228|-60.74%|22.36 MB|
