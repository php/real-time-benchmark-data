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
| Kernel        |6.1.134-150.224.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250428|
| GCC           |11.5.0|
| Time          |2025-05-11 00:50:05 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43798|0.44930|0.00195|0.43906|0.00%|0.43867|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|0.43806|0.43931|0.00030|0.43877|-0.07%|0.43870|0.01%|41.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|0.43805|0.44021|0.00059|0.43879|-0.06%|0.43876|0.02%|41.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.42606|0.42754|0.00036|0.42688|-2.78%|0.42689|-2.69%|50.86 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71366|0.71680|0.00070|0.71462|0.00%|0.71447|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|0.70917|0.72302|0.00233|0.71122|-0.48%|0.71076|-0.52%|37.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|0.70921|0.71309|0.00108|0.71079|-0.54%|0.71063|-0.54%|37.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.68484|0.68915|0.00088|0.68603|-4.00%|0.68581|-4.01%|44.61 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58048|0.58356|0.00069|0.58176|0.00%|0.58168|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|0.58454|0.58932|0.00093|0.58590|0.71%|0.58576|0.70%|43.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|0.58507|0.58650|0.00036|0.58574|0.68%|0.58570|0.69%|43.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.52326|0.52481|0.00041|0.52415|-9.90%|0.52423|-9.88%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21527|0.21942|0.00097|0.21705|0.00%|0.21695|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|0.21278|0.21952|0.00143|0.21475|-1.06%|0.21455|-1.10%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|0.21230|0.21852|0.00189|0.21467|-1.10%|0.21425|-1.25%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.07551|0.07825|0.00069|0.07656|-64.73%|0.07633|-64.81%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33948|1.36006|0.00512|1.34774|0.00%|1.34686|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e11a702c05)|1.27356|1.29139|0.00495|1.28026|-5.01%|1.27906|-5.03%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/e11a702c05)|1.27349|1.29748|0.00557|1.28057|-4.98%|1.27924|-5.02%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/e11a702c05)|0.56117|0.57430|0.00357|0.56941|-57.75%|0.57002|-57.68%|21.83 MB|
