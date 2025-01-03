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
| Kernel        |6.1.119-129.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241212|
| GCC           |11.4.1|
| Time          |2025-01-03 00:49:28 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43894|0.44132|0.00051|0.43968|0.00%|0.43960|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/249d2dac28)|0.43520|0.43682|0.00040|0.43608|-0.82%|0.43605|-0.81%|41.70 MB|
|[PHP - master](https://github.com/php/php-src/commit/60252b7845)|0.43569|0.43749|0.00048|0.43649|-0.73%|0.43644|-0.72%|41.70 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60252b7845)|0.42665|0.42824|0.00035|0.42764|-2.74%|0.42762|-2.73%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71362|0.71727|0.00073|0.71493|0.00%|0.71479|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/249d2dac28)|0.70942|0.71484|0.00089|0.71086|-0.57%|0.71070|-0.57%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/60252b7845)|0.70843|0.71261|0.00095|0.71042|-0.63%|0.71020|-0.64%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60252b7845)|0.68218|0.68527|0.00073|0.68341|-4.41%|0.68329|-4.41%|44.48 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58171|0.58483|0.00067|0.58287|0.00%|0.58282|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/249d2dac28)|0.57799|0.58068|0.00055|0.57904|-0.66%|0.57892|-0.67%|42.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/60252b7845)|0.57344|0.57952|0.00172|0.57753|-0.92%|0.57822|-0.79%|42.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60252b7845)|0.51943|0.52175|0.00051|0.52057|-10.69%|0.52052|-10.69%|61.91 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21535|0.21925|0.00096|0.21733|0.00%|0.21732|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/249d2dac28)|0.21481|0.21892|0.00100|0.21620|-0.52%|0.21611|-0.55%|26.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/60252b7845)|0.21489|0.21867|0.00088|0.21595|-0.64%|0.21577|-0.71%|26.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60252b7845)|0.07425|0.07900|0.00096|0.07576|-65.14%|0.07533|-65.34%|27.23 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34342|1.37062|0.00606|1.35508|0.00%|1.35530|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/249d2dac28)|1.30759|1.33083|0.00568|1.31852|-2.70%|1.31736|-2.80%|20.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/60252b7845)|1.30792|1.33805|0.00703|1.32134|-2.49%|1.32050|-2.57%|20.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/60252b7845)|0.52896|0.55163|0.00453|0.54003|-60.15%|0.53963|-60.18%|21.66 MB|
