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
| OS            |Amazon Linux 2023.6.20241111|
| GCC           |11.4.1|
| Time          |2024-11-20 00:49:37 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43949|0.44147|0.00045|0.44017|0.00%|0.44007|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff5b42b839)|0.43700|0.43977|0.00057|0.43797|-0.50%|0.43789|-0.49%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba0ecaa107)|0.43700|0.43884|0.00039|0.43791|-0.51%|0.43787|-0.50%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba0ecaa107)|0.42518|0.42690|0.00035|0.42595|-3.23%|0.42599|-3.20%|50.74 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71307|0.71542|0.00059|0.71432|0.00%|0.71441|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff5b42b839)|0.70951|0.71396|0.00108|0.71080|-0.49%|0.71060|-0.53%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba0ecaa107)|0.70920|0.71339|0.00087|0.71064|-0.52%|0.71054|-0.54%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba0ecaa107)|0.68121|0.68430|0.00069|0.68232|-4.48%|0.68222|-4.51%|44.45 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57691|0.58438|0.00225|0.58086|0.00%|0.58189|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff5b42b839)|0.57706|0.57975|0.00060|0.57835|-0.43%|0.57835|-0.61%|42.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba0ecaa107)|0.57725|0.57948|0.00049|0.57812|-0.47%|0.57801|-0.67%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba0ecaa107)|0.51901|0.59153|0.02713|0.53559|-7.79%|0.52071|-10.51%|61.89 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21451|0.21920|0.00106|0.21620|0.00%|0.21600|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff5b42b839)|0.21481|0.21905|0.00093|0.21637|0.08%|0.21621|0.09%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba0ecaa107)|0.21517|0.21940|0.00092|0.21666|0.21%|0.21653|0.25%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba0ecaa107)|0.07373|0.07704|0.00073|0.07534|-65.15%|0.07526|-65.16%|27.28 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33826|1.36427|0.00605|1.34970|0.00%|1.34924|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ff5b42b839)|1.27170|1.29961|0.00637|1.28694|-4.65%|1.28603|-4.69%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/ba0ecaa107)|1.27746|1.30584|0.00575|1.28787|-4.58%|1.28781|-4.55%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ba0ecaa107)|0.52188|0.54875|0.00606|0.53437|-60.41%|0.53447|-60.39%|21.69 MB|
