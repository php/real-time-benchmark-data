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
| Kernel        |6.1.112-122.189.amzn2023.x86_64|
| OS            |Amazon Linux 2023.6.20241010|
| GCC           |11.4.1|
| Time          |2024-10-18 00:49:21 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43976|0.44770|0.00132|0.44102|0.00%|0.44066|0.00%|41.88 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3351daee61)|0.43779|0.44049|0.00056|0.43869|-0.53%|0.43856|-0.48%|41.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/42e179ef9d)|0.43756|0.44145|0.00073|0.43884|-0.49%|0.43880|-0.42%|41.78 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42e179ef9d)|0.42843|0.43094|0.00056|0.42937|-2.64%|0.42928|-2.58%|50.83 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.72204|0.72805|0.00110|0.72342|0.00%|0.72313|0.00%|37.39 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3351daee61)|0.71793|0.72177|0.00078|0.71937|-0.56%|0.71932|-0.53%|37.36 MB|
|[PHP - master](https://github.com/php/php-src/commit/42e179ef9d)|0.71653|0.72019|0.00083|0.71841|-0.69%|0.71837|-0.66%|37.36 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42e179ef9d)|0.69513|0.69888|0.00064|0.69648|-3.72%|0.69646|-3.69%|44.53 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58219|0.58444|0.00051|0.58330|0.00%|0.58326|0.00%|43.01 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3351daee61)|0.57817|0.58095|0.00059|0.57942|-0.66%|0.57935|-0.67%|42.92 MB|
|[PHP - master](https://github.com/php/php-src/commit/42e179ef9d)|0.57834|0.58092|0.00057|0.57920|-0.70%|0.57908|-0.72%|42.92 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42e179ef9d)|0.52178|0.52466|0.00046|0.52341|-10.27%|0.52339|-10.27%|61.95 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21447|0.22048|0.00124|0.21633|0.00%|0.21597|0.00%|26.18 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3351daee61)|0.21517|0.21947|0.00094|0.21701|0.32%|0.21695|0.46%|26.21 MB|
|[PHP - master](https://github.com/php/php-src/commit/42e179ef9d)|0.21529|0.21851|0.00063|0.21623|-0.04%|0.21616|0.09%|26.15 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42e179ef9d)|0.07403|0.07716|0.00065|0.07505|-65.31%|0.07492|-65.31%|27.31 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33785|1.36206|0.00569|1.35036|0.00%|1.35053|0.00%|20.44 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/3351daee61)|1.30058|1.31477|0.00355|1.30771|-3.16%|1.30745|-3.19%|20.47 MB|
|[PHP - master](https://github.com/php/php-src/commit/42e179ef9d)|1.29451|1.30947|0.00391|1.30357|-3.46%|1.30406|-3.44%|20.41 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/42e179ef9d)|0.53278|0.55154|0.00408|0.54159|-59.89%|0.54119|-59.93%|21.72 MB|
