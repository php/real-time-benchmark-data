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
| Kernel        |6.1.144-170.251.amzn2023.x86_64|
| OS            |Amazon Linux 2023.8.20250721|
| GCC           |11.5.0|
| Time          |2025-08-02 00:50:14 UTC|

### Laravel 12.2.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.47068|0.48437|0.00236|0.47245|0.00%|0.47186|0.00%|43.29 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f3bc59950)|0.46558|0.46800|0.00067|0.46650|-1.26%|0.46632|-1.18%|43.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/55a3e33bb1)|0.46568|0.46797|0.00040|0.46650|-1.26%|0.46648|-1.14%|43.56 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55a3e33bb1)|0.44908|0.45095|0.00041|0.44988|-4.78%|0.44990|-4.65%|53.75 MB|

### Symfony 2.7.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.74335|0.74761|0.00098|0.74477|0.00%|0.74466|0.00%|39.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f3bc59950)|0.73239|0.74394|0.00207|0.73447|-1.38%|0.73406|-1.42%|40.35 MB|
|[PHP - master](https://github.com/php/php-src/commit/55a3e33bb1)|0.72890|0.74083|0.00210|0.73042|-1.93%|0.73002|-1.96%|40.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55a3e33bb1)|0.69913|0.70383|0.00089|0.70028|-5.97%|0.70006|-5.99%|47.78 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57928|0.58106|0.00051|0.58009|0.00%|0.58000|0.00%|43.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f3bc59950)|0.58008|0.58174|0.00044|0.58079|0.12%|0.58070|0.12%|43.54 MB|
|[PHP - master](https://github.com/php/php-src/commit/55a3e33bb1)|0.57802|0.58131|0.00068|0.57917|-0.16%|0.57913|-0.15%|43.32 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55a3e33bb1)|0.51659|0.51896|0.00073|0.51763|-10.77%|0.51750|-10.78%|61.39 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21405|0.21824|0.00110|0.21539|0.00%|0.21479|0.00%|26.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f3bc59950)|0.21803|0.22310|0.00118|0.21984|2.07%|0.21963|2.25%|26.73 MB|
|[PHP - master](https://github.com/php/php-src/commit/55a3e33bb1)|0.21874|0.22146|0.00075|0.22001|2.15%|0.22013|2.48%|26.55 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55a3e33bb1)|0.07378|0.07642|0.00063|0.07462|-65.35%|0.07453|-65.30%|27.78 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.42384|1.43973|0.00461|1.43214|0.00%|1.43216|0.00%|20.64 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/6f3bc59950)|1.28122|1.29524|0.00394|1.28780|-10.08%|1.28780|-10.08%|21.01 MB|
|[PHP - master](https://github.com/php/php-src/commit/55a3e33bb1)|1.24531|1.27260|0.00690|1.25931|-12.07%|1.26043|-11.99%|20.84 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/55a3e33bb1)|0.53259|0.55141|0.00448|0.54433|-61.99%|0.54565|-61.90%|22.23 MB|
