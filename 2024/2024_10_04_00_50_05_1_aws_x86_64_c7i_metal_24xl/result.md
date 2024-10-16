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
| Time          |2024-10-04 00:50:05 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43745|0.44106|0.00073|0.43845|0.00%|0.43831|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/524f6dfb19)|0.43560|0.43802|0.00052|0.43673|-0.39%|0.43658|-0.40%|41.79 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8791e5581)|0.43678|0.43924|0.00050|0.43734|-0.25%|0.43727|-0.24%|41.80 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8791e5581)|0.43032|0.43167|0.00034|0.43084|-1.74%|0.43073|-1.73%|50.79 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71431|0.71717|0.00079|0.71559|0.00%|0.71543|0.00%|37.38 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/524f6dfb19)|0.70879|0.72515|0.00284|0.71062|-0.70%|0.70997|-0.76%|37.38 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8791e5581)|0.70893|0.71152|0.00072|0.71011|-0.77%|0.70999|-0.76%|37.38 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8791e5581)|0.68742|0.69308|0.00107|0.68878|-3.75%|0.68861|-3.75%|44.52 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.57973|0.58163|0.00051|0.58055|0.00%|0.58049|0.00%|43.00 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/524f6dfb19)|0.57753|0.58077|0.00056|0.57870|-0.32%|0.57855|-0.33%|42.93 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8791e5581)|0.57732|0.57933|0.00042|0.57817|-0.41%|0.57812|-0.41%|43.00 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8791e5581)|0.51817|0.52047|0.00057|0.51907|-10.59%|0.51888|-10.61%|61.92 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21497|0.21873|0.00095|0.21595|0.00%|0.21567|0.00%|26.17 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/524f6dfb19)|0.21502|0.21809|0.00074|0.21642|0.22%|0.21652|0.39%|26.16 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8791e5581)|0.21115|0.21397|0.00078|0.21257|-1.56%|0.21240|-1.52%|26.16 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8791e5581)|0.07456|0.07741|0.00067|0.07556|-65.01%|0.07549|-65.00%|27.29 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34262|1.36892|0.00716|1.35546|0.00%|1.35444|0.00%|20.42 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/524f6dfb19)|1.33984|1.36166|0.00546|1.34984|-0.41%|1.35065|-0.28%|20.42 MB|
|[PHP - master](https://github.com/php/php-src/commit/c8791e5581)|1.32280|1.35178|0.00684|1.33726|-1.34%|1.33895|-1.14%|20.42 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/c8791e5581)|0.61596|0.65706|0.00901|0.63347|-53.27%|0.63242|-53.31%|21.70 MB|