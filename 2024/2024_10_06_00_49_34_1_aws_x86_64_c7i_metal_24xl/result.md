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
| Time          |2024-10-06 00:49:34 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43756|0.44418|0.00113|0.43843|0.00%|0.43814|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed8d6b5b25)|0.43573|0.43763|0.00043|0.43639|-0.46%|0.43630|-0.42%|41.80 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ae00fa0a)|0.43592|0.43797|0.00053|0.43689|-0.35%|0.43674|-0.32%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ae00fa0a)|0.42862|0.43046|0.00042|0.42935|-2.07%|0.42933|-2.01%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71429|0.71740|0.00071|0.71539|0.00%|0.71521|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed8d6b5b25)|0.70699|0.70948|0.00062|0.70807|-1.02%|0.70822|-0.98%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ae00fa0a)|0.70701|0.71071|0.00074|0.70787|-1.05%|0.70783|-1.03%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ae00fa0a)|0.68635|0.68833|0.00055|0.68719|-3.94%|0.68718|-3.92%|44.52 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58035|0.59041|0.00179|0.58137|0.00%|0.58082|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed8d6b5b25)|0.57607|0.57811|0.00047|0.57683|-0.78%|0.57682|-0.69%|43.00 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ae00fa0a)|0.57653|0.57849|0.00047|0.57756|-0.66%|0.57748|-0.58%|43.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ae00fa0a)|0.51982|0.52192|0.00052|0.52084|-10.41%|0.52078|-10.34%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21456|0.21857|0.00109|0.21621|0.00%|0.21608|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed8d6b5b25)|0.21526|0.21904|0.00099|0.21672|0.24%|0.21656|0.22%|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ae00fa0a)|0.21655|0.21857|0.00054|0.21764|0.66%|0.21772|0.76%|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ae00fa0a)|0.07466|0.07672|0.00063|0.07542|-65.12%|0.07529|-65.15%|27.29 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34327|1.36324|0.00457|1.35484|0.00%|1.35430|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ed8d6b5b25)|1.33084|1.36317|0.00721|1.35248|-0.17%|1.35217|-0.16%|20.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/39ae00fa0a)|1.40845|1.43191|0.00565|1.42063|4.86%|1.42001|4.85%|20.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/39ae00fa0a)|0.63975|0.65965|0.00547|0.64611|-52.31%|0.64425|-52.43%|21.70 MB|
