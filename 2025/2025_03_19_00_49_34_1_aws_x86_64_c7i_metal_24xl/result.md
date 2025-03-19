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
| Time          |2025-03-19 00:49:34 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43836|0.44070|0.00051|0.43930|0.00%|0.43925|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81ef122ca9)|0.43558|0.43731|0.00039|0.43627|-0.69%|0.43620|-0.70%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/b450a9c826)|0.43575|0.43726|0.00044|0.43633|-0.68%|0.43614|-0.71%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b450a9c826)|0.42418|0.42618|0.00049|0.42490|-3.28%|0.42475|-3.30%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71305|0.71839|0.00111|0.71495|0.00%|0.71494|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81ef122ca9)|0.70853|0.71150|0.00081|0.71020|-0.66%|0.71023|-0.66%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/b450a9c826)|0.69905|0.71106|0.00207|0.70882|-0.86%|0.70927|-0.79%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b450a9c826)|0.67964|0.68334|0.00087|0.68121|-4.72%|0.68120|-4.72%|44.56 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58112|0.58460|0.00093|0.58271|0.00%|0.58264|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81ef122ca9)|0.57614|0.57921|0.00081|0.57744|-0.90%|0.57750|-0.88%|42.94 MB|
|[PHP - master](https://github.com/php/php-src/commit/b450a9c826)|0.57708|0.58110|0.00077|0.57843|-0.73%|0.57830|-0.75%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b450a9c826)|0.51979|0.52249|0.00054|0.52080|-10.62%|0.52076|-10.62%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21475|0.21857|0.00081|0.21621|0.00%|0.21628|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81ef122ca9)|0.21687|0.22183|0.00120|0.21832|0.98%|0.21808|0.83%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/b450a9c826)|0.21568|0.21972|0.00086|0.21732|0.51%|0.21726|0.45%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b450a9c826)|0.07470|0.07722|0.00063|0.07557|-65.05%|0.07535|-65.16%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34005|1.36441|0.00594|1.34997|0.00%|1.34982|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/81ef122ca9)|1.27070|1.28974|0.00458|1.27931|-5.23%|1.27847|-5.29%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/b450a9c826)|1.27113|1.28367|0.00321|1.27775|-5.35%|1.27715|-5.38%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b450a9c826)|0.53023|0.55617|0.00610|0.54275|-59.80%|0.54326|-59.75%|21.80 MB|
