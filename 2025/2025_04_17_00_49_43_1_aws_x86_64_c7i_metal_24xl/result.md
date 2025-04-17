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
| Kernel        |6.1.132-147.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250414|
| GCC           |11.5.0|
| Time          |2025-04-17 00:49:43 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43839|0.44881|0.00179|0.43950|0.00%|0.43919|0.00%|41.86 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea387fcfb7)|0.43656|0.43938|0.00065|0.43761|-0.43%|0.43743|-0.40%|41.97 MB|
|[PHP - master](https://github.com/php/php-src/commit/87499e44f2)|0.43636|0.43823|0.00053|0.43739|-0.48%|0.43746|-0.39%|41.97 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87499e44f2)|0.42294|0.42443|0.00038|0.42359|-3.62%|0.42358|-3.55%|50.87 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71617|0.73012|0.00244|0.71777|0.00%|0.71721|0.00%|37.51 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea387fcfb7)|0.70974|0.71246|0.00062|0.71055|-1.01%|0.71056|-0.93%|37.65 MB|
|[PHP - master](https://github.com/php/php-src/commit/87499e44f2)|0.70969|0.71234|0.00063|0.71061|-1.00%|0.71047|-0.94%|37.65 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87499e44f2)|0.68168|0.68469|0.00065|0.68286|-4.86%|0.68280|-4.80%|44.62 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58163|0.58438|0.00062|0.58263|0.00%|0.58262|0.00%|43.07 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea387fcfb7)|0.57926|0.58173|0.00054|0.57990|-0.47%|0.57992|-0.46%|43.05 MB|
|[PHP - master](https://github.com/php/php-src/commit/87499e44f2)|0.58169|0.58418|0.00054|0.58263|0.00%|0.58253|-0.02%|43.05 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87499e44f2)|0.52200|0.52369|0.00041|0.52288|-10.25%|0.52277|-10.27%|62.15 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21558|0.21998|0.00112|0.21715|0.00%|0.21684|0.00%|26.23 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea387fcfb7)|0.21522|0.21898|0.00081|0.21668|-0.22%|0.21681|-0.01%|26.25 MB|
|[PHP - master](https://github.com/php/php-src/commit/87499e44f2)|0.21662|0.21994|0.00080|0.21786|0.33%|0.21779|0.44%|26.25 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87499e44f2)|0.07590|0.07884|0.00079|0.07705|-64.52%|0.07686|-64.55%|27.41 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.34225|1.36767|0.00687|1.35165|0.00%|1.35073|0.00%|20.49 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/ea387fcfb7)|1.26229|1.27906|0.00461|1.26961|-6.07%|1.26853|-6.09%|20.51 MB|
|[PHP - master](https://github.com/php/php-src/commit/87499e44f2)|1.30584|1.32280|0.00439|1.31225|-2.91%|1.31223|-2.85%|20.51 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/87499e44f2)|0.54392|0.56386|0.00497|0.55500|-58.94%|0.55578|-58.85%|21.83 MB|
