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
| Kernel        |6.1.109-118.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.5.20241001|
| GCC           |11.4.1|
| Time          |2024-10-05 00:49:21 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43783|0.44087|0.00056|0.43886|0.00%|0.43866|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8791e5581)|0.43639|0.43797|0.00034|0.43722|-0.38%|0.43726|-0.32%|41.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed8d6b5b25)|0.43620|0.43794|0.00040|0.43701|-0.42%|0.43693|-0.39%|41.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed8d6b5b25)|0.42753|0.43187|0.00077|0.42856|-2.35%|0.42854|-2.31%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71420|0.72054|0.00125|0.71567|0.00%|0.71524|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8791e5581)|0.70901|0.71154|0.00048|0.70983|-0.82%|0.70967|-0.78%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed8d6b5b25)|0.70704|0.70957|0.00050|0.70798|-1.07%|0.70795|-1.02%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed8d6b5b25)|0.68596|0.68985|0.00074|0.68780|-3.89%|0.68776|-3.84%|44.52 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57963|0.58224|0.00065|0.58080|0.00%|0.58071|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8791e5581)|0.57940|0.58236|0.00060|0.58048|-0.06%|0.58042|-0.05%|42.99 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed8d6b5b25)|0.57571|0.57831|0.00069|0.57682|-0.69%|0.57689|-0.66%|42.99 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed8d6b5b25)|0.51880|0.52148|0.00053|0.51984|-10.50%|0.51974|-10.50%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21454|0.21742|0.00075|0.21578|0.00%|0.21564|0.00%|26.16 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8791e5581)|0.21204|0.21522|0.00082|0.21340|-1.11%|0.21322|-1.12%|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed8d6b5b25)|0.21512|0.22052|0.00150|0.21729|0.70%|0.21751|0.87%|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed8d6b5b25)|0.07442|0.07665|0.00055|0.07524|-65.13%|0.07528|-65.09%|27.28 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34091|1.36799|0.00643|1.35405|0.00%|1.35433|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/c8791e5581)|1.32325|1.34905|0.00704|1.33681|-1.27%|1.33848|-1.17%|20.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/ed8d6b5b25)|1.33485|1.36570|0.00665|1.35108|-0.22%|1.35111|-0.24%|20.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/ed8d6b5b25)|0.62362|0.64062|0.00474|0.63344|-53.22%|0.63280|-53.28%|21.69 MB|
