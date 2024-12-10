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
| Time          |2024-12-10 00:49:43 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.44026|0.44873|0.00123|0.44141|0.00%|0.44122|0.00%|41.81 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0385e978a)|0.43799|0.44555|0.00105|0.43911|-0.52%|0.43904|-0.49%|41.68 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ef9302c31)|0.43733|0.43963|0.00051|0.43849|-0.66%|0.43847|-0.62%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ef9302c31)|0.42537|0.42801|0.00061|0.42635|-3.41%|0.42633|-3.37%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71392|0.71725|0.00075|0.71537|0.00%|0.71515|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0385e978a)|0.71120|0.71521|0.00099|0.71290|-0.35%|0.71270|-0.34%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ef9302c31)|0.70091|0.71328|0.00164|0.71034|-0.70%|0.71044|-0.66%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ef9302c31)|0.68154|0.68546|0.00082|0.68315|-4.50%|0.68310|-4.48%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58066|0.58336|0.00058|0.58158|0.00%|0.58158|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0385e978a)|0.57732|0.58840|0.00152|0.57880|-0.48%|0.57855|-0.52%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ef9302c31)|0.57726|0.57925|0.00053|0.57809|-0.60%|0.57802|-0.61%|42.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ef9302c31)|0.51958|0.52378|0.00068|0.52131|-10.36%|0.52130|-10.36%|61.62 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21447|0.21944|0.00103|0.21606|0.00%|0.21593|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0385e978a)|0.21562|0.21921|0.00091|0.21683|0.36%|0.21661|0.31%|26.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ef9302c31)|0.21524|0.21942|0.00105|0.21673|0.31%|0.21652|0.27%|26.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ef9302c31)|0.07389|0.07698|0.00081|0.07524|-65.18%|0.07505|-65.25%|27.22 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34178|1.36285|0.00464|1.35352|0.00%|1.35366|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c0385e978a)|1.33856|1.36509|0.00534|1.35291|-0.05%|1.35317|-0.04%|20.31 MB|
|[PHP - master](https://github.com/php/php-src/commit/8ef9302c31)|1.32739|1.35280|0.00517|1.33941|-1.04%|1.33975|-1.03%|20.31 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/8ef9302c31)|0.53368|0.55918|0.00628|0.54486|-59.74%|0.54456|-59.77%|21.64 MB|
