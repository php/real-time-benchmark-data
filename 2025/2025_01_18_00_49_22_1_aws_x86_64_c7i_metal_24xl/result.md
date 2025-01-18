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
| OS            |Amazon Linux 2023.6.20250115|
| GCC           |11.4.1|
| Time          |2025-01-18 00:49:22 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43910|0.44112|0.00043|0.43979|0.00%|0.43970|0.00%|41.87 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0d8e6867a)|0.43866|0.44482|0.00090|0.43987|0.02%|0.43980|0.02%|41.77 MB|
|[PHP - master](https://github.com/php/php-src/commit/709c0a9905)|0.43849|0.44502|0.00096|0.43955|-0.05%|0.43936|-0.08%|41.77 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/709c0a9905)|0.42622|0.42856|0.00044|0.42712|-2.88%|0.42708|-2.87%|50.82 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71339|0.71600|0.00057|0.71455|0.00%|0.71457|0.00%|37.41 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0d8e6867a)|0.70966|0.71254|0.00075|0.71100|-0.50%|0.71097|-0.50%|37.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/709c0a9905)|0.71151|0.71470|0.00073|0.71262|-0.27%|0.71251|-0.29%|37.47 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/709c0a9905)|0.68173|0.68472|0.00068|0.68292|-4.43%|0.68275|-4.45%|44.55 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58115|0.58407|0.00064|0.58255|0.00%|0.58250|0.00%|43.02 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0d8e6867a)|0.57831|0.58071|0.00063|0.57951|-0.52%|0.57955|-0.51%|42.87 MB|
|[PHP - master](https://github.com/php/php-src/commit/709c0a9905)|0.57882|0.58050|0.00044|0.57962|-0.50%|0.57957|-0.50%|42.87 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/709c0a9905)|0.52078|0.52310|0.00049|0.52188|-10.41%|0.52182|-10.42%|61.98 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21545|0.21829|0.00071|0.21661|0.00%|0.21662|0.00%|26.19 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0d8e6867a)|0.21537|0.21843|0.00074|0.21676|0.07%|0.21667|0.02%|26.14 MB|
|[PHP - master](https://github.com/php/php-src/commit/709c0a9905)|0.21415|0.21920|0.00107|0.21635|-0.12%|0.21629|-0.15%|26.14 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/709c0a9905)|0.07526|0.07877|0.00068|0.07648|-64.69%|0.07641|-64.73%|27.31 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33846|1.37287|0.00600|1.35215|0.00%|1.35227|0.00%|20.45 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/d0d8e6867a)|1.26635|1.28712|0.00434|1.27725|-5.54%|1.27680|-5.58%|20.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/709c0a9905)|1.32992|1.34931|0.00477|1.33967|-0.92%|1.33961|-0.94%|20.40 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/709c0a9905)|0.53318|0.55304|0.00403|0.54032|-60.04%|0.54022|-60.05%|21.73 MB|
