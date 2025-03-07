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
| Kernel        |6.1.128-136.201.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20250218|
| GCC           |11.4.1|
| Time          |2025-03-07 00:49:31 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43974|0.44224|0.00058|0.44080|0.00%|0.44073|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0dede83264)|0.43831|0.43999|0.00041|0.43913|-0.38%|0.43921|-0.35%|41.86 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd586623b6)|0.43865|0.44036|0.00043|0.43938|-0.32%|0.43932|-0.32%|41.86 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd586623b6)|0.42777|0.42949|0.00037|0.42830|-2.84%|0.42830|-2.82%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71376|0.71813|0.00109|0.71531|0.00%|0.71504|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0dede83264)|0.70351|0.70947|0.00110|0.70784|-1.04%|0.70788|-1.00%|37.55 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd586623b6)|0.70539|0.70854|0.00069|0.70671|-1.20%|0.70661|-1.18%|37.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd586623b6)|0.67846|0.68087|0.00070|0.67966|-4.98%|0.67973|-4.94%|44.55 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58091|0.58277|0.00043|0.58209|0.00%|0.58213|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0dede83264)|0.57674|0.57901|0.00052|0.57785|-0.73%|0.57793|-0.72%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd586623b6)|0.57697|0.57910|0.00053|0.57782|-0.73%|0.57770|-0.76%|42.93 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd586623b6)|0.52072|0.52320|0.00055|0.52161|-10.39%|0.52151|-10.41%|61.91 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21553|0.21882|0.00090|0.21679|0.00%|0.21659|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0dede83264)|0.21692|0.22085|0.00091|0.21861|0.84%|0.21861|0.93%|26.27 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd586623b6)|0.21860|0.22131|0.00067|0.21983|1.40%|0.21988|1.52%|26.27 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd586623b6)|0.07492|0.07731|0.00067|0.07583|-65.02%|0.07560|-65.09%|27.37 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33704|1.35753|0.00502|1.34836|0.00%|1.34833|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/0dede83264)|1.27319|1.29688|0.00473|1.28230|-4.90%|1.28129|-4.97%|20.53 MB|
|[PHP - master](https://github.com/php/php-src/commit/cd586623b6)|1.27161|1.28707|0.00406|1.27991|-5.08%|1.28029|-5.05%|20.53 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/cd586623b6)|0.52475|0.53942|0.00388|0.53265|-60.50%|0.53254|-60.50%|21.79 MB|
