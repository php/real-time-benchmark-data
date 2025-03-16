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
| Time          |2025-03-16 00:49:45 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43942|0.44841|0.00156|0.44040|0.00%|0.44003|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e954bf6750)|0.43759|0.44075|0.00063|0.43857|-0.42%|0.43850|-0.35%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e7f362dd)|0.43638|0.43935|0.00068|0.43723|-0.72%|0.43709|-0.67%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e7f362dd)|0.42103|0.43044|0.00129|0.42680|-3.09%|0.42690|-2.98%|50.80 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71433|0.71788|0.00091|0.71592|0.00%|0.71567|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e954bf6750)|0.70707|0.71091|0.00092|0.70823|-1.07%|0.70791|-1.08%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e7f362dd)|0.70707|0.71058|0.00091|0.70868|-1.01%|0.70871|-0.97%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e7f362dd)|0.68117|0.68452|0.00073|0.68255|-4.66%|0.68244|-4.64%|44.56 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58097|0.59107|0.00167|0.58263|0.00%|0.58236|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e954bf6750)|0.58144|0.58341|0.00051|0.58247|-0.03%|0.58249|0.02%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e7f362dd)|0.57613|0.57812|0.00047|0.57698|-0.97%|0.57691|-0.94%|42.94 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e7f362dd)|0.52096|0.52268|0.00050|0.52192|-10.42%|0.52186|-10.39%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21539|0.21854|0.00086|0.21690|0.00%|0.21689|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e954bf6750)|0.25909|0.28637|0.00570|0.27115|25.01%|0.27112|25.00%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e7f362dd)|0.21600|0.22122|0.00130|0.21773|0.38%|0.21747|0.27%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e7f362dd)|0.07443|0.07668|0.00058|0.07571|-65.09%|0.07572|-65.09%|27.38 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.35331|1.37095|0.00441|1.36064|0.00%|1.35930|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/e954bf6750)|1.25232|1.26847|0.00387|1.26027|-7.38%|1.26073|-7.25%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/d8e7f362dd)|1.27950|1.29616|0.00395|1.28695|-5.42%|1.28736|-5.29%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/d8e7f362dd)|0.52845|0.54115|0.00300|0.53477|-60.70%|0.53550|-60.60%|21.80 MB|
