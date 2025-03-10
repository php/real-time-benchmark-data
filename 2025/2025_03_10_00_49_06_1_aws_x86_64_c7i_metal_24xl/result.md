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
| Time          |2025-03-10 00:49:06 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43841|0.44402|0.00102|0.43919|0.00%|0.43895|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30ce9acd33)|0.43636|0.43869|0.00054|0.43725|-0.44%|0.43721|-0.40%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/33c4ca36e4)|0.43670|0.43847|0.00045|0.43757|-0.37%|0.43753|-0.32%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33c4ca36e4)|0.42440|0.42592|0.00041|0.42506|-3.22%|0.42502|-3.17%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71306|0.71547|0.00066|0.71413|0.00%|0.71397|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30ce9acd33)|0.70455|0.70733|0.00068|0.70553|-1.20%|0.70534|-1.21%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/33c4ca36e4)|0.70501|0.70803|0.00067|0.70609|-1.12%|0.70601|-1.12%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33c4ca36e4)|0.67915|0.68135|0.00057|0.68037|-4.73%|0.68044|-4.70%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58144|0.58328|0.00053|0.58231|0.00%|0.58217|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30ce9acd33)|0.57113|0.57777|0.00175|0.57594|-1.09%|0.57652|-0.97%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/33c4ca36e4)|0.57814|0.58139|0.00082|0.57964|-0.46%|0.57938|-0.48%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33c4ca36e4)|0.51987|0.52232|0.00054|0.52112|-10.51%|0.52110|-10.49%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21507|0.21807|0.00076|0.21606|0.00%|0.21591|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30ce9acd33)|0.21645|0.21973|0.00079|0.21795|0.87%|0.21797|0.96%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/33c4ca36e4)|0.21276|0.21491|0.00047|0.21336|-1.25%|0.21332|-1.20%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33c4ca36e4)|0.07515|0.07732|0.00056|0.07626|-64.71%|0.07630|-64.66%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33962|1.36096|0.00536|1.34942|0.00%|1.34876|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/30ce9acd33)|1.26675|1.28379|0.00367|1.27817|-5.28%|1.27890|-5.18%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/33c4ca36e4)|1.26003|1.28053|0.00439|1.26837|-6.01%|1.26731|-6.04%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/33c4ca36e4)|0.52545|0.54005|0.00403|0.53347|-60.47%|0.53359|-60.44%|21.79 MB|
