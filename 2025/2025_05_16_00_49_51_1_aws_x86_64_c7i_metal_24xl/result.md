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
| Kernel        |6.1.134-152.225.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250512|
| GCC           |11.5.0|
| Time          |2025-05-16 00:49:51 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43769|0.45248|0.00253|0.43916|0.00%|0.43866|0.00%|41.92 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89dc8d79a7)|0.43885|0.44202|0.00072|0.43981|0.15%|0.43957|0.21%|42.06 MB|
|[PHP - master](https://github.com/php/php-src/commit/3367f17f60)|0.43831|0.43998|0.00043|0.43902|-0.03%|0.43892|0.06%|42.06 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3367f17f60)|0.42487|0.42594|0.00030|0.42533|-3.15%|0.42530|-3.04%|50.93 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71315|0.71599|0.00067|0.71437|0.00%|0.71431|0.00%|37.57 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89dc8d79a7)|0.69997|0.72057|0.00281|0.70970|-0.65%|0.70958|-0.66%|37.72 MB|
|[PHP - master](https://github.com/php/php-src/commit/3367f17f60)|0.70809|0.71136|0.00075|0.70961|-0.67%|0.70960|-0.66%|37.72 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3367f17f60)|0.68429|0.68726|0.00068|0.68558|-4.03%|0.68567|-4.01%|44.69 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58088|0.58330|0.00052|0.58205|0.00%|0.58199|0.00%|43.13 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89dc8d79a7)|0.58109|0.58334|0.00049|0.58203|-0.00%|0.58204|0.01%|43.34 MB|
|[PHP - master](https://github.com/php/php-src/commit/3367f17f60)|0.58139|0.58465|0.00071|0.58249|0.08%|0.58239|0.07%|43.34 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3367f17f60)|0.52144|0.52359|0.00049|0.52217|-10.29%|0.52202|-10.30%|62.25 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21526|0.22020|0.00107|0.21706|0.00%|0.21690|0.00%|26.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89dc8d79a7)|0.21724|0.22403|0.00131|0.22002|1.36%|0.22023|1.53%|26.32 MB|
|[PHP - master](https://github.com/php/php-src/commit/3367f17f60)|0.21737|0.22039|0.00086|0.21886|0.83%|0.21875|0.85%|26.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3367f17f60)|0.07546|0.07856|0.00087|0.07681|-64.61%|0.07664|-64.67%|27.49 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34340|1.36146|0.00471|1.35184|0.00%|1.35113|0.00%|20.55 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/89dc8d79a7)|1.29444|1.30810|0.00370|1.30129|-3.74%|1.30106|-3.71%|20.58 MB|
|[PHP - master](https://github.com/php/php-src/commit/3367f17f60)|1.29483|1.31047|0.00371|1.30108|-3.75%|1.30058|-3.74%|20.58 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/3367f17f60)|0.54983|0.56619|0.00465|0.55836|-58.70%|0.55943|-58.60%|21.91 MB|
