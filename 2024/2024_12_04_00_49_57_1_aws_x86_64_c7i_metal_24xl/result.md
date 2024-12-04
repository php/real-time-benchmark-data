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
| Time          |2024-12-04 00:49:57 UTC|

### Laravel 11.1.2 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43914|0.44125|0.00051|0.44002|0.00%|0.43995|0.00%|41.82 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01093b7c13)|0.43672|0.43862|0.00047|0.43750|-0.57%|0.43745|-0.57%|41.69 MB|
|[PHP - master](https://github.com/php/php-src/commit/b01f5e367f)|0.43714|0.44355|0.00093|0.43813|-0.43%|0.43802|-0.44%|41.69 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b01f5e367f)|0.42518|0.42681|0.00038|0.42605|-3.18%|0.42606|-3.16%|50.75 MB|

### Symfony 2.6.0 demo app - 50 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71390|0.71667|0.00066|0.71502|0.00%|0.71498|0.00%|37.33 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01093b7c13)|0.71219|0.71559|0.00075|0.71345|-0.22%|0.71346|-0.21%|37.39 MB|
|[PHP - master](https://github.com/php/php-src/commit/b01f5e367f)|0.71171|0.72751|0.00294|0.71346|-0.22%|0.71285|-0.30%|37.39 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b01f5e367f)|0.68437|0.68890|0.00077|0.68572|-4.10%|0.68553|-4.12%|44.46 MB|

### Wordpress 6.2 main page - 50 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58039|0.58494|0.00074|0.58225|0.00%|0.58211|0.00%|42.95 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01093b7c13)|0.57716|0.57978|0.00052|0.57831|-0.68%|0.57829|-0.66%|42.78 MB|
|[PHP - master](https://github.com/php/php-src/commit/b01f5e367f)|0.57710|0.58045|0.00062|0.57810|-0.71%|0.57794|-0.72%|42.79 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b01f5e367f)|0.51930|0.52224|0.00057|0.52018|-10.66%|0.52010|-10.65%|61.63 MB|

### bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21507|0.22442|0.00146|0.21706|0.00%|0.21679|0.00%|26.12 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01093b7c13)|0.21468|0.21854|0.00094|0.21624|-0.38%|0.21605|-0.34%|26.12 MB|
|[PHP - master](https://github.com/php/php-src/commit/b01f5e367f)|0.21461|0.21810|0.00081|0.21598|-0.50%|0.21591|-0.41%|26.12 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b01f5e367f)|0.07416|0.07748|0.00065|0.07542|-65.25%|0.07539|-65.22%|27.29 MB|

### micro_bench.php - 50 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33747|1.36054|0.00552|1.34899|0.00%|1.35014|0.00%|20.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/01093b7c13)|1.25516|1.27532|0.00508|1.26374|-6.32%|1.26207|-6.52%|20.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/b01f5e367f)|1.24804|1.26629|0.00433|1.25659|-6.85%|1.25647|-6.94%|20.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/b01f5e367f)|0.53483|0.56619|0.00620|0.55154|-59.11%|0.55243|-59.08%|21.70 MB|
