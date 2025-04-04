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
| Kernel        |6.1.131-143.221.amzn2023.x86_64|
| OS            |Amazon Linux 2023.7.20250331|
| GCC           |11.5.0|
| Time          |2025-04-04 00:49:42 UTC|

### Laravel 11.1.2 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.43875|0.45028|0.00197|0.44013|0.00%|0.43985|0.00%|41.84 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4954df0c9)|0.43952|0.44412|0.00103|0.44122|0.25%|0.44114|0.29%|41.89 MB|
|[PHP - master](https://github.com/php/php-src/commit/68665d3cb5)|0.43948|0.44229|0.00067|0.44057|0.10%|0.44054|0.16%|41.89 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/68665d3cb5)|0.42962|0.43333|0.00062|0.43080|-2.12%|0.43073|-2.07%|50.87 MB|

### Symfony 2.6.0 demo app - 30 consecutive runs, 100 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.71514|0.72014|0.00101|0.71622|0.00%|0.71594|0.00%|37.50 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4954df0c9)|0.71242|0.71539|0.00079|0.71339|-0.39%|0.71310|-0.40%|37.63 MB|
|[PHP - master](https://github.com/php/php-src/commit/68665d3cb5)|0.71376|0.71621|0.00060|0.71510|-0.16%|0.71505|-0.12%|37.63 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/68665d3cb5)|0.68197|0.68499|0.00070|0.68297|-4.64%|0.68291|-4.61%|44.71 MB|

### Wordpress 6.2 main page - 30 consecutive runs, 20 requests (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.58150|0.58589|0.00094|0.58256|0.00%|0.58232|0.00%|43.05 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4954df0c9)|0.57956|0.58176|0.00055|0.58029|-0.39%|0.58021|-0.36%|43.03 MB|
|[PHP - master](https://github.com/php/php-src/commit/68665d3cb5)|0.57868|0.58148|0.00068|0.58010|-0.42%|0.58005|-0.39%|43.03 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/68665d3cb5)|0.52079|0.52297|0.00044|0.52199|-10.40%|0.52198|-10.36%|62.14 MB|

### bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|0.21531|0.22174|0.00131|0.21712|0.00%|0.21705|0.00%|26.22 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4954df0c9)|0.21569|0.22118|0.00122|0.21780|0.31%|0.21764|0.27%|26.24 MB|
|[PHP - master](https://github.com/php/php-src/commit/68665d3cb5)|0.21544|0.21894|0.00082|0.21697|-0.07%|0.21677|-0.13%|26.24 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/68665d3cb5)|0.07526|0.07852|0.00088|0.07648|-64.78%|0.07630|-64.85%|27.40 MB|

### micro_bench.php - 25 consecutive runs (sec)

|     PHP     |     Min     |     Max     |    Std dev   |   Average  |  Average diff % |   Median   | Median diff % |     Memory    |
|-------------|-------------|-------------|--------------|------------|-----------------|------------|---------------|---------------|
|[PHP - baseline@d5f6](https://github.com/php/php-src/commit/d5f6e56610)|1.33817|1.35808|0.00584|1.34823|0.00%|1.34940|0.00%|20.48 MB|
|[PHP - previous master](https://github.com/php/php-src/commit/f4954df0c9)|1.24749|1.26977|0.00575|1.25870|-6.64%|1.25801|-6.77%|20.50 MB|
|[PHP - master](https://github.com/php/php-src/commit/68665d3cb5)|1.25510|1.26699|0.00378|1.26103|-6.47%|1.26032|-6.60%|20.50 MB|
|[PHP - master (JIT)](https://github.com/php/php-src/commit/68665d3cb5)|0.53020|0.54924|0.00416|0.54233|-59.77%|0.54356|-59.72%|21.82 MB|
