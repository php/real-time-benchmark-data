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
| OS            |Amazon Linux 2023.6.20250107|
| GCC           |11.4.1|
| Time          |2025-01-14 00:49:16 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43858|0.44867|0.00176|0.43984|0.00%|0.43939|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99d62013b)|0.43744|0.44470|0.00097|0.43844|-0.32%|0.43831|-0.25%|41.76 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e1fbf97f4)|0.43836|0.44147|0.00056|0.43918|-0.15%|0.43913|-0.06%|41.76 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e1fbf97f4)|0.42745|0.42908|0.00032|0.42820|-2.65%|0.42818|-2.55%|50.81 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71168|0.72659|0.00203|0.71336|0.00%|0.71288|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99d62013b)|0.71056|0.71485|0.00072|0.71180|-0.22%|0.71174|-0.16%|37.46 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e1fbf97f4)|0.70611|0.70942|0.00076|0.70749|-0.82%|0.70731|-0.78%|37.46 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e1fbf97f4)|0.68165|0.68490|0.00075|0.68279|-4.29%|0.68264|-4.24%|44.54 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58002|0.58390|0.00091|0.58174|0.00%|0.58194|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99d62013b)|0.57719|0.58113|0.00075|0.57865|-0.53%|0.57863|-0.57%|42.85 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e1fbf97f4)|0.57934|0.58295|0.00068|0.58059|-0.20%|0.58054|-0.24%|42.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e1fbf97f4)|0.51963|0.52427|0.00069|0.52249|-10.18%|0.52254|-10.21%|61.97 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21495|0.21875|0.00076|0.21621|0.00%|0.21620|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99d62013b)|0.21610|0.22011|0.00104|0.21821|0.93%|0.21823|0.94%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e1fbf97f4)|0.21538|0.21890|0.00085|0.21687|0.31%|0.21678|0.27%|26.13 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e1fbf97f4)|0.07482|0.07820|0.00074|0.07637|-64.68%|0.07628|-64.72%|27.30 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34217|1.36960|0.00560|1.35320|0.00%|1.35378|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f99d62013b)|1.29416|1.30988|0.00421|1.30186|-3.79%|1.30178|-3.84%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/0e1fbf97f4)|1.29256|1.31672|0.00534|1.30474|-3.58%|1.30480|-3.62%|20.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/0e1fbf97f4)|0.53025|0.55202|0.00439|0.54052|-60.06%|0.54130|-60.02%|21.72 MB|
